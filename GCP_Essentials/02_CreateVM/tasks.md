# Tasks

- [x] Create VM with GCP console
- [x] Create VM with `gcloud` command line
- [x] Deploy a web server and connect it to a virtual machine

## Create VM with GCP console

GCP console (web) -> Open Cloud Shell button (top right) -> START CLOUD SHELL

List the active account name with this command: `gcloud auth list`

List the porject ID: `gcloud config list project`

Full documentation of gcloud is available on [Google Cloud gcloud Overview](https://cloud.google.com/sdk/gcloud/).

Learn more about regions and zones and see a complete list in [Regions & Zones documentation](https://cloud.google.com/compute/docs/regions-zones/).

## Create VM with `gcloud` command line

If you want to try this on your own machine in the future, read the [gcloud command line tool guide](https://cloud.google.com/sdk/gcloud/).

Create VM from command line using `gcloud`.

```shell
# create VM from command line using gcloud
gcloud compute instances create gcelab2 --machine-type n1-standard-2 --zone us-central1-c #[your_zone]
```

Run `gcloud compute instances create --help` to see all the defaults.

```shell
# Run gcloud compute instances create --help to see all the defaults.
gcloud compute instances create --help

# Set default region and zones
gcloud config set compute/zone $zone

gcloud config set compute/region $region
```

Finally, you can SSH into your instance using gcloud as well. Make sure you add your zone, or omit the --zone flag if you've set the option globally:

```shell
gcloud compute ssh gcelab2 --zone $your_zone
```
