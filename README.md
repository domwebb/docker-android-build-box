# Docker Android Build Box

## Introduction

A **docker** image with Android build enviroment for React Native. 

Based on the excellent [mingc/android-build-box](https://github.com/mingchen/docker-android-build-box) docker image, with some components removed and others updated.

Yarn and NPM package managers. Ruby and Ruby Gems (latest). Fastlane and AWS CLI.

## What Is Inside

It includes the following components:

* Ubuntu 18.04
* Android SDK 29
* Android build tools 29.0.2
* extra-google-google\_play\_services
* Google API add-ons
* Constraint Layout
* Python 2, Python 3, PIP
* Node.js, 
* NPM
* Yarn
* Ruby
* RubyGems
* Fastlane
* AWS Cli


## Pull Docker Image

The docker image is publicly automated build on [Docker Hub](https://hub.docker.com/r/thebiggerfish/react-native-build-image) based on the Dockerfile in this repo, so there is no hidden stuff in it. To pull the latest docker image:

    docker pull thebiggerfish/react-native-build-image:latest

## Contribution

If you want to enhance this docker image or fix something, feel free to send [pull request](https://github.com/rewrite3/docker-android-build-box/pull/new/master).