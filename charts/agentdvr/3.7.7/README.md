Agent DVR (iSpy)
=====

[Agent DVR](https://www.ispyconnect.com) iSpy's Agent DVR, a standalone DVR service to manage IP cameras.

Introduction
------------

This chart bootstraps Agent DVR deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.


Configuration
-------------

The following table lists the configurable parameters of the IPFS chart and their default values.

| Parameter                                        | Description                                                                                                                             | Default                          |
|:-------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------|
| `image.repository`                               | Image repository                                                                                                                        | `doitandbedone/ispyagentdvr`                    |
| `image.tag`                                      | AgentDVR image tag. Possible values listed [here](https://hub.docker.com/r/doitandbedone/ispyagentdvr/tags).                                              | `latest`   |
| `image.pullPolicy`                               | Image pull policy                                                                                                                       | `IfNotPresent`                   |
| `extraArgs`                                      | Additional command line arguments to pass to Agent DVR                                                                            | `[]`                             |
