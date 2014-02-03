# Vagarnt WordPress (Amimoto)

## Description

Amimoto WordPressStack greatly simplifies the development and management of WordPress hosting.
WordPress is a content management platform that allows users to easily publish, manage, and organize a wide variety of content on a website.
Amimoto Stack includes ready-to-run versions of WordPress. It is completely integrated and configured, so you’ll be ready to start developing your WordPress as soon as the AMI is launched onto Amazon EC2.

## Getting Started

### 1. Install VirtualBox.

 * https://www.virtualbox.org/

### 2. Install Vagrant.

 * http://www.vagrantup.com/

### 3. Install the vagrant plugins.

```
$ vagrant plugin install vagrant-aws
```

### 6. Set shell environment variables to .bash_profile like below.

```
export AWS_ACCESS_KEY="your aws access key"
export AWS_SECRET_ACCESS_KEY="your aws secret key"
export AWS_EC2_KEYPAIR="your key pairs" # https://console.aws.amazon.com/ec2/v2/home#KeyPairs:
export AWS_EC2_KEYPAIR_PATH="/path/to/.ssh/id_rsa"
```

Reload environment variables.

```
$ source .bash_profile
```

### 5. Clone the repository into a local directory.

```
$ git clone https://github.com/Launch-with-1-Click/vagrant-wordpress.git
```

### 6. Change into a new directory.

```
$ cd vagrant-concrete5
```

### 7. Start a Vagrant environment.

```
$ vagrant up
```