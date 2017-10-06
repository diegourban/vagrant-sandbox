# vagrant-sandbox

## Requirements

* Vagrant
* VirtualBox
* Ubuntu 32 box, available at http://files.vagrantup.com/precise32.box

## Installation

```vagrant up``` - to start the VM

```vagrant destroy``` - to destroy the VM

```vagrant destroy``` - to reload configs

```vagrant ssh``` - to connect to the VM with ssh

```sudo puppet apply /vagrant/manifests/web.pp``` - to run config tasks with puppet

## Usage

```http://192.168.50.10:8080``` - open tomcat

```http://192.168.50.10:8080/vraptor-musicjungle ``` - access the deployed app
