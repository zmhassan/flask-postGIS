# Map of US National Parks
*powered by Flask, PostGIS, and Leaflet maps*

## OpenShift Hosting
[![Build Status](https://build-shifter.rhcloud.com/buildStatus/icon?job=parkgis-build)](http://parkgis-shifter.rhcloud.com/)

To deploy a clone of this application using the [`rhc` command line tool](http://rubygems.org/gems/rhc):

    rhc app create parks python-2.6 postgresql-9.2 --from-code=https://github.com/ryanj/flask-postGIS.git
    
Or [link to a web-based clone+deploy](https://openshift.redhat.com/app/console/application_type/custom?cartridges%5B%5D=python-2.6&cartridges%5B%5D=postgresql-9.2&initial_git_url=https%3A%2F%2Fgithub.com%2Fryanj%2Fflask-postGIS.git) on [OpenShift Online](http://OpenShift.com) or on [your own OpenShift cloud](http://openshift.github.io): 

    https://openshift.redhat.com/app/console/application_type/custom?cartridges%5B%5D=python-2.6&cartridges%5B%5D=postgresql-9.2&initial_git_url=https%3A%2F%2Fgithub.com%2Fryanj%2Fflask-postGIS.git

A demo is available at: [http://parkgis-shifter.rhcloud.com/](http://parkgis-shifter.rhcloud.com/)

## License
This code is dedicated to the public domain to the maximum extent permitted by applicable law, pursuant to CC0 (http://creativecommons.org/publicdomain/zero/1.0/)
