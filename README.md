# OpenShift Lightblue Cartridge

See documentation on our [User Guide](http://docs.lightblue.io):
* Installation with [Install lightblue on OpenShift](http://docs.lightblue.io/cookbook/install_lightblue_on_openshift.html)
* Using the service with sections of the [Quickstart](http://docs.lightblue.io/cookbook/quickstart.html)

## NOTE for Developers!
If you fork this you'll need to use something to set the `source-url` correctly in your manifest.

Info on how the download works: https://developers.openshift.com/en/get-involved-extend-openshift.html#how-cartridges-are-downloaded

Easy way to work around issues: https://developers.openshift.com/en/get-involved-extend-openshift.html#the-cartridge-reflector

For example, to install a fork of this repo for user 'jewzaam' with branch 'lightblue-1.2':
```
rhc app create http://cartreflect-claytondev.rhcloud.com/github/jewzaam/openshift-lightblue-cart?commit=lightblue-1.2 -a test
```

# License
