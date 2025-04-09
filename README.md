# dab_training

The dab_training repo contains examples of Databricks Asset Bundles deployments for several scenarios organized in separate folders. You will find more details inside the different folders:

* **dab_examples:** Contains a series of databricks jobs deployments that range from basic serveless notebook jobs to orchestrations where a job triggers another job.

* **wheel_poetry:** Job deployment that uses two wheels created and managed through **Poetry**.

* **wheel_uv:** Job deployment that uses two wheels created and managed through **UV**.

* **wheel_uv_serverless:** Job deployment that uses two wheels created and managed through **UV** and its compute is **serverless**.

* **yellow_nyc:** Example Job orchestration using auto-loader and public data from the NYC Taxi @ Limousine Commission.

* **.github/workflows:** contains a cicd.yml file for configuring the dev environment of this repo so the bundles are validated and deployed to DEV on PR requests.<br>
#### Disclosure:
The examples have been modified and documentation created by David Flores from what he learned in the udemy course [master-of-databricks-asset-bundle](https://www.udemy.com/course/master-of-databricks-asset-bundle/?couponCode=FAFAB8F0EFCE8251E56A) by [Glib Martinenko](https://www.linkedin.com/in/glibmartynenko/). Not to be shared in a commercial transaction.
