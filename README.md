openshift-diy-maven
===================

This project provides an example set for a [Dropwizard][dw] Java application that is
packaged so it can be deployed to [OpenShift][os] in a DIY-cartridge.

Although this project uses Dropwizard as the example being built and deployed,
the build and deploy steps can be reused for any Java application which uses
an embedded server as it just executes [Maven][mvn] steps.

This source project accompanies the blog post here:

http://tearsofaunicorn.com/articles/deploying-dropwizard-to-openshift.html


Building the project and running the tests
------------------------------------------

The project can be built using the standard Maven commands:

   mvn clean package

The project can be deployed to OpenShift by:

1. Creating a DIY application on OpenShift
2. Pushing the code to the Git repository for the created application and
   letting OpenShift build and deploy it
   
[dw]: http://dropwizard.io
[os]: http://www.openshift.com
[mvn]: http://maven.apache.org   
