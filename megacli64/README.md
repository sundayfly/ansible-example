## How to: Install LSI Command Line Tool

LSI hardware RAID  has a command line tool to manage RAID related commands and configuration. It is called MegaCLI. MegaCLI is available at broadcom doc downloads. Use the following to download MegaCLI:

> wget https://docs.broadcom.com/docs-and-downloads/raid-controllers/raid-controllers-common-files/8-07-14_MegaCLI.zip

Unzip the MegaCLI file:

> unzip 8-07-14_MegaCLI.zip
> cd Linux

Run the rpm file:

> rpm -ivh MegaCli-8.07.14-1.noarch.rpm

## check log
> cat ansible.log
[Ansiable Tasks: Disk Failure info] host=10.71.12.89
