Code based on <https://github.com/josefkarasek/origin-aggregated-logging/tree/bz-1559219-precreate/yacht>

The original python code was modified to run only once and not in infinite loop. The code is called from operator instead.
The base image `registry.svc.ci.openshift.org/openshift/origin-v4.0:base` contains Python 2.7.5 but does not contain pip and elasticsearch client.