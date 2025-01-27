## Description
This repo is a used to setup a pre-configured development environment tailored for the **Quotify** project.

## Requirements
- vagrant
- virtualbox

## Usage
First generate a **new** Github ssh private key and copy into ./ansible/assets/id_rsa. Then in the project directory execute the command to boot up the virtual machine:
```bash
vagrant up
```
Note that you may need to reload the virtual machine after virtual box guest additions has been installed. Afterwards execute the following command to install the necessary software packages:
```bash
vagrant provision
```
