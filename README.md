# CarND Term1 Starter Kit

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

The purpose of this project is to provide unified software dependency support for students enrolled in Term 1 of the [Udacity Self-Driving Car Engineer Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).

Python 3 is used for entirety of term 1.

There are three ways to get up and running:

## [FloydHub](doc/configure_via_floydhub.md)

Get started [here](doc/configure_via_floydhub.md). More info [here](https://www.floydhub.com).

Supported Systems : AWS (CPU, [GPU](doc/docker_for_aws.md))

| Pros                                    | Cons                                 |
|-----------------------------------------|--------------------------------------|
| Simple to use                           | No local environment                 |
| Zero setup (managed service)            | |
| AWS, GPU support                        | |
| Cheaper than AWS (pay only for runtime) | |

## [Anaconda Environment](doc/configure_via_anaconda.md)

Get started [here](doc/configure_via_anaconda.md). More info [here](http://conda.pydata.org/docs/).

Supported Sytems: Linux (CPU), Mac (CPU), Windows (CPU)     

| Pros                         | Cons                                               |
|------------------------------|----------------------------------------------------|
| More straight-forward to use | AWS or GPU support is not built in (have to do this yourself)              |
| More community support       | Implementation is local and OS specific            |
| More heavily adopted         |                                                    |

## [Docker](doc/configure_via_docker.md)

Get started [here](doc/configure_via_docker.md). More info [here](http://docker.com).

Supported Systems : AWS (CPU, [GPU](doc/docker_for_aws.md)), Linux (CPU), Mac (CPU), Windows (CPU)     

| Pros                                | Cons                                 |
|-------------------------------------|--------------------------------------|
| Configure once for all environments | More challenging to use              |
| AWS, GPU support                    | Less community support               |
| Practice with Docker              | Have to manage images and containers |
