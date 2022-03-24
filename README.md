# Ansible script for extending a windows pertition or mounting a new one using VMware shell

## Table of contents
  * [Index](#index)
  * [Introduction](#introduction)
  * [Requirements](#requirements)
  * [How to use it](#how-to-use-it)
  * [Contributors](#contributors)


## Introduction

This repo was created from the need to repeatedly create Windows virtual machines and extend their space/mount new partitions
    

## Requirements

Ansible - minimum version: 2.11
VMware vCenter
Community.vmware collection (which you can install from [here]: https://github.com/ansible-collections/community.vmware)

You will need to modify in both roles vars/main.yml :variables according to each role. For more about that see each role README.

## How to use it
Run it with:

    ansible-playbook main.yml

Now you have to:

    Sit back and enjoy

## Contributors
    Creator: Alexandru Nișulescu
    Contact: alex.nisulescu1998@gmail.com
    Linkedin: https://www.linkedin.com/in/alex-nisulescu-45822b178/
