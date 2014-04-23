# DEPRECATED

Elastic Beanstalk has long since added support first-class support for PHP. There are still advantages to running PHP via Quercus, but for >99% of applications the basic PHP support is likely fine.

## Introduction 

This project is meant to show how you can run PHP on Amazon's Elastic Beanstalk service.

It's setup as a Maven project and uses [Quercus](http://quercus.caucho.com/), a "100% Java implementation of PHP 5," to run PHP in a Tomcat container.

## Getting Started

From the project root, run 'mvn package' to create the deployable war file. Once complete, upload to AWS Elastic Beanstalk.
