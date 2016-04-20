App Dev Cloud with JBoss Insurance Demo 
=======================================
This demo is to install JBoss Insurance Demo in the Cloud based on leveraging the Red Hat 
Container Development Kit (CDK) and the provided OpenShift Enterprise (OSE) image. 
It delivers a fully functioning JBoss BPM insurance example containerized on OSE.


Install on Red Hat CDK OpenShift Enterprise image
-------------------------------------------------
1. First complete the installation and start the OpenShift image supplied in the
	 [cdk-install-demo](https://github.com/eschabell/cdk-install-demo).

2. Install [OpenShift Client Tools](https://developers.openshift.com/managing-your-applications/client-tools.html) if you have not
	 done so previously.

2. [Download and unzip this demo.](https://github.com/redhatdemocentral/rhcs-mortgage-demo/archive/master.zip)

3. Add products to installs directory.

5. Run 'init.sh' or 'init.bat' file. 'init.bat' must be run with Administrative privileges.

6. Login to JBoss BPM Suite to start developing your BPM projects:

    [http://insurance.10.1.2.2.xip.io/business-central](http://insurance.10.1.2.2.xip.io/business-central)
    ( u:erics / p:bpmsuite1! )


Note before running demo:
-------------------------
Should your local network DNS not handle the resolution of the above address, giving you page not found errors, you can apply the
following to your local hosts file:

    ```
    $ sudo vi /etc/hosts

    # add host for CDK demo resolution.
    10.1.2.2   insurance.10.1.2.2.xip.io    insurance.10.1.2.2.xip.io
    ```


Supporting Articles
-------------------
- coming soon...


Released versions
-----------------
See the tagged releases for the following versions of the product:

- v1.0 - JBoss BPM Suite 6.2.0-BZ-1299002, JBoss EAP 6.4.4 with insurance process installed on Red Hat CDK using OpenShift Enterprise image.


