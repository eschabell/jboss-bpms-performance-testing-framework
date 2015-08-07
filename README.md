JBoss BPM Suite Performance Testing Framework Project
=====================================================

This project hosts the JBoss BPM Suite performance testing project that is used to test various aspects of the product and
provide metrics when put under stress.


Setup and Configuration
-----------------------
1. [Download and unzip.](https://github.com/eschabell/jboss-bpms-performance-testing-framework/archive/master.zip)

2. Add products to installs directory. For example download and add BPMS installer jar into the installs directory.

3. Run 'init.sh' or 'init.bat' file. 'init.bat' must be run with Administrative privileges.

4. Start JBoss BPMS Server by running 'standalone.sh' or 'standalone.bat' in the <path-to-project>/target/jboss-eap-6.4/bin
	 directory.

5. Login to [http://localhost:8080/business-central](http://localhost:8080/business-central)

    ```
     - login for admin and other roles (u:erics / p:bpmsuite1!)
    ```

7. (TODO: project does not build, update to 6.1 product) Login to BRMS testing applicaiton (http://localhost:8080/brms-testing) and start testing and measuring!


Released versions
-----------------
See the tagged releases for the following versions of the product:

- v0.1 is initial migration to JBoss BPM Suite 6.1 running on JBoss EAP 6.4 with rules and human task node examples.


![Demo projects](https://raw.githubusercontent.com/eschabell/jboss-bpms-performance-testing-framework/master/docs/demo-images/projects.png)
