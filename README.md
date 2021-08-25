### Gitlab ci
## Caveats:
* to reuse gitlab-ci pipeline, you can create one or many gitlab ci templated pipeline, just like gitlab-ci-template.yml

* then, in your gitlab-ci.yml file, include this template, overwrite with variables

* from time to time, when you want build docker image from dockernized gitlab runner, you have to set DOCKER_HOST env var so that docker client cli like dokcer build can talk to localhost docker daemon
