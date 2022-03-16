cf-scp
======

Script to copy data via scp to and from CloudFoundry instances. This follows the [official guide of CloudFoundry](https://docs.cloudfoundry.org/devguide/deploy-apps/ssh-apps.html#other-ssh-access).

### Usage

```cf-scp-get $APP_NAME $SOURCE $TARGET```
```cf-scp-put $APP_NAME $SOURCE $TARGET```

Example:

```cf-scp-get my_fancy_app /tmp/on-cf/data.json /tmp/local/data.json```

Required tools:

* cf-cli
* jq
* scp
