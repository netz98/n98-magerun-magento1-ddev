# Magerun Magento 1 ddev

This project contains the files to test the locallaly cloned source code
of n98-magerun in a ddev docker environment.

## Setup Dev Environment

### Setup n98-magerun source code

1. Fork n98-magerun
1. Clone the source code of your fork to anywhere on the machine.
1. Run composer install in the n98-magerun directory.

### Setup Magento 1

1. Download Magento source
1. Copy the .ddev directory in the root directory of your Magento project
1. Edit the file `.ddev/docker-compose.magerun.yaml` and change the path to match the n98-magerun source directory.
1. Run ddev start
1. Run Magento installation (see https://ddev.readthedocs.io/en/latest/users/cli-usage/#magento-1-quickstart)

## Run n98-magerun


```
ddev mr-dev
```

