# Vagrant Examples

## What is Vagrant?

Vagrant is a tool that uses Oracle's VirtualBox to dynamically build configurable, lightweight, and portable virtual machines. Vagrant supports the use of either Puppet or Chef for managing the configuration. Much more information is available on the [Vagrant web site](http://www.vagrantup.com).

## What is this project?

This is a collection of sample Vagrant configurations for my lecturing. They start out very simple with the bare minimum and gradually get more complex.

## How do I install Vagrant?

but any OS should work as long as VirtualBox can be installed.  The [Vagrant download page](https://www.vagrantup.com/downloads.html) lists several options for installing v1.1.0.

## How do I run the examples?

From one of the example directories, type the following commands...

```
vagrant up
vagrant ssh
  {test it..}
  exit
vagrant destroy
```

These commands will bring up the Vagrant box, SSH into it, and then remove it respectively.

## Summary of examples

1. basic
2. provider
3. MultiBox
4. ProvisionScript
5. Docker Build Example

## List of example
* 01.skel
* 02.basic
* 03.provider
* 04.MultiBox
* 05.MultiBox_parameter_if
* 06.ClientServer
* 07.ProvisionScript
* 08.InstallDocker
* 09.Argument
* 10.ShareFolder
* 11.skelAll
* 12.WithConfigFile
* 13.QuickMultiBox


# etc
* Powered by [finfra.com](http://finfra.com)
