# Jazz Serverless Platform
**Seamlessly build, deploy & manage cloud-native applications.**

Jazz addresses gaps and pain points with serverless, particularly for production applications. It is not another FaaS implementation. Rather, it enhances the usability of existing FaaS systems. Jazz has a beautiful UI designed to let devs quickly self-start and focus on code. Its modular design makes it easy to add new integrations:

* **Services** - Today devs can build functions, APIs and static websites. The template-based system makes it easy to define new ones.
* **Deployment Targets** - Currently we deploy to AWS (Lambda, API gateway and S3). We plan to support Azure Functions and Docker containers in the near future.
* **Features** - Services seamlessly integrate features like monitoring (CloudWatch), logging (ElasticSearch), authentication (Cognito) and secret management (KMS, Vault coming soon).
* **Deployment & CI/CD** - We leverage [Serverless Framework](http://www.serverless.com) and Git/Artifactory/Jenkins.

Jazz is [open-sourced](http://opensource.corporate.t-mobile.com) and under active development by T-Mobile's Cloud Center of Excellence.

## Installation

You can [try the Developer Preview](https://github.com/tmobile/jazz-installer) by using the automated installer.

## User Guide

For more details, see the [Wiki](https://github.com/tmobile/jazz-core/wiki).

## License

Jazz is released under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0).
