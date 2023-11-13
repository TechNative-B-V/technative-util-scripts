# technative-util-scripts

Utility scripts for a better workflow.

## Setup Terraform plugin cache

This first use is generally only needed if you use Terraform for the first time on your machine.

It's recommended to setup the Terraform plugin cache to prevent full disk situations. The downloaded providers can be quite big (~500 Mb).

Run `./terraform_plugin_cache.sh` to set this up automatically. If already setup then the script should abort indicating this.
