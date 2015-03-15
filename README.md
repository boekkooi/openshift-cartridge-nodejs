# Openshift NodeJS Plugin Cartridge
A basic [nodejs](https://nodejs.org/) plugin cartridge for usage with the [boekkooi nginx cartridge](https://github.com/boekkooi/openshift-cartridge-nginx).

## Install
You can add this cartridge to your application using:
```BASH
rhc cartridge add -a myapp http://cartreflect-claytondev.rhcloud.com/github/boekkooi/openshift-cartridge-nodejs
```

If you want to install a specific NodeJS version you can add `--env OPENSHIFT_NODEJS_VERSION=<version>` to the command.
For example to install NodeJS 0.10.37 you can use:
```BASH
rhc cartridge add -a myapp --env OPENSHIFT_NODEJS_VERSION=0.10.37 http://cartreflect-claytondev.rhcloud.com/github/boekkooi/openshift-cartridge-nodejs
```
