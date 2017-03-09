# kraken-services
DEPRECATION NOTICE:  this project has been superceded by [K2-Charts](https://github.com/samsung-cnct/k2-charts).  Issues have been locked
and all work going forward will be against the K2-charts repository.



Services for use on a kraken cluster.

Each directory contains a set of kubernetes resources intended to be deployed onto a kraken-managed kubernetes cluster.

The resources are not always complete, and may require environment-varables-as-templtaes to be substituted in

Some services also contain a build directory for the Docker images referenced in the kubernetes resources.
