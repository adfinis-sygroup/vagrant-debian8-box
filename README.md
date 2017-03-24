# Jessie box for Vagrant (virtualbox)

This repo contain definition files to build a
[Vagrant](http://www.vagrantup.com) box based on the weekly Debian Jessie
images.

## Dependencies

You need to install [Vagrant](http://www.vagrantup.com) and
[veewee](https://github.com/jedi4ever/veewee) with your favorite package
manager to build the image.

## Running

Just run the following command in the repository root:

    veewee vbox build adsy-debian-8.0.0
    veewee vbox export adsy-debian-8.0.0

## Issues

Before installing anything you need to call:

    apt-get update
    
The image doesn't contain any repository data to make it smaller.
