# Setting Up Your Local Coding Environment

Most of the projects in this program are designed to be completed in a Linux (Ubuntu) environment. To facilitate this, it's recommended that you set up your own local coding environment. While sandboxes are available, having your local environment allows you to work offline.

This project serves as a guide for setting up the necessary coding environment regardless of the operating system you are using. Once set up, you can transition from using sandboxes to working entirely in your local environment.

## Guide to Running Ubuntu 20.04 on Different Operating Systems

### Windows

You have three options for running Ubuntu on Windows:

1. **WSL (Windows Subsystem for Linux):**
   - WSL allows you to run Linux distributions natively on Windows.
   - It is easy to set up and provides a good introduction to Ubuntu.

2. **Vagrant:**
   - Vagrant is a tool for creating and managing virtual machines.
   - It's a good option for development or testing purposes, providing isolated and replicable environments.

3. **Docker:**
   - Docker is a tool for containerizing applications.
   - It's useful for specific tasks, such as running a web server or database, but requires WSL for installation.

### macOS

Your options for running Ubuntu on macOS depend on your machine's chip architecture:

1. **Apple Silicon chip:**
   - Docker is the only option for running Ubuntu.

2. **Intel chip:**
   - You can use either Vagrant or Docker.

Explore each option in this project and choose the one that best suits your needs.

## Vagrant - Coding on Your Local Computer

While sandboxes are convenient, you can also conduct your ALX assessments on your local computer by using a virtual machine (VM) managed by Vagrant. This project guides you through using Vagrant for this purpose.

### Note:

- This project cannot be completed in sandboxes; it's intended for your local computer.

## Resources

Read or watch:

- [Virtual machine](#)
- `man uname`

## Learning Objectives

By the end of this project, you should be able to explain, without using Google:

**General:**
- What is a virtual machine?
- What is Vagrant?
- Who wrote Vagrant?
- What is Ubuntu?
- What does "Ubuntu" mean?
- How to use VMs with Vagrant.
- What does the command `uname` do?

## Copyright - Plagiarism

You are responsible for solving the tasks below independently to meet the learning objectives. Copying and pasting someone else's work, as well as publishing any content of this project, is strictly prohibited and will result in removal from the program.

## Requirements

**General:**
- A `README.md` file at the root of the repo containing a description of the repository.
- A `README.md` file at the root of the folder of this project (i.e., `0x00-vagrant`), describing the purpose of this project.

## More Info

### Install Git

If Git is not installed on your terminal, run the following commands:

```bash
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
