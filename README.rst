Simphony remote docker : Jupyter
================================

Docker image for jupyter webapp.
Additional information available in simphonyproject/simphony-remote-docker.


Build
-----

- Edit the file build.conf to verify the right information is present
- Run ``simphony-remote-docker/scripts/create_production_app.sh build.conf``. 
  This will create a production directory. It _MUST_ be added and committed for
  Hub Docker autobuild to create the image for us.
- (optional) Build can be obtained locally by issuing
  ``simphony-remote-docker/scripts/build_app.sh build.conf``. 

