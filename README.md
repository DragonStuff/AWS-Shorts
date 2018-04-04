# AWS-Shorts
[![Green Tea Licence Badge](https://img.shields.io/badge/LICENCE-Green%20Tea-brightgreen.svg?link=https://github.com/DragonStuff/GreenTeaLicence&link=https://github.com/DragonStuff/GreenTeaLicence)](https://github.com/DragonStuff/GreenTeaLicence)

Amazon Web Service Explorations ‍🚀🌍

## OpsWorks

- OpsWorks is a configuration management service that relies heavy on Chef or Puppet for configuration-as-code deployment automation. The service lets you configure and launch stacks specific to your application's needs.
- OpsWorks has three offerings, AWS Opsworks for Chef Automate, AWS OpsWorks for Puppet Enterprise, and AWS OpsWorks Stacks.
- AWS OpsWorks for Chef Automate provides a fully managed Chef server and suite of automation tools that give you workflow automation for continuous deployment, automated testing for compliance and security, and a user interface that gives you visibility into your nodes and their status. The Chef server gives you full stack automation by handling operational tasks such as software and operating system configurations, package installations, database setups, and more. The Chef server centrally stores your configuration tasks and provides them to each node in your compute environment at any scale, from a few nodes to thousands of nodes. OpsWorks for Chef Automate is completely compatible with tooling and cookbooks from the Chef community and automatically registers new nodes with your Chef server.
- AWS OpsWorks for Puppet Enterprise is a fully-managed configuration management service that hosts Puppet Enterprise, a set of automation tools from Puppet for infrastructure and application management. OpsWorks also maintains your Puppet master server by automatically patching, updating, and backing up your server. OpsWorks eliminates the need to operate your own configuration management systems or worry about maintaining its infrastructure. OpsWorks gives you access to all of the Puppet Enterprise features, which you manage through the Puppet console. It also works seamlessly with your existing Puppet code.
- A Puppet master manages the configuration of nodes in your environment by serving configuration catalogs for specific nodes to the puppet-agent software, and serves as a central repository for your Puppet modules. A Puppet master in AWS OpsWorks for Puppet Enterprise deploys puppet-agent to your managed nodes, and provides premium features of Puppet Enterprise. An AWS OpsWorks for Puppet Enterprise master runs on an Amazon Elastic Compute Cloud instance.
AWS OpsWorks for Puppet Enterprise servers are configured to run the newest version of Amazon Linux (2017.09), and the most current version of Puppet Enterprise Master, version 2017.3.x.
- AWS OpsWorks Stacks lets you manage applications and servers on AWS and on-premises. With OpsWorks Stacks, you can model your application as a stack containing different layers, such as load balancing, database, and application server. You can deploy and configure Amazon EC2 instances in each layer or connect other resources such as Amazon RDS databases. OpsWorks Stacks lets you set automatic scaling for your servers based on preset schedules or in response to changing traffic levels, and it uses lifecycle hooks to orchestrate changes as your environment scales. You run Chef recipes using Chef Solo, allowing you to automate tasks such as installing packages and programming languages or frameworks, configuring software, and more.

__*Project*__: Deploy an OpsWorks for Chef Automate instance that talks to a server with Docker installed. The aim is to deploy a Docker database instance (Postgres), plus a Python instance (w/ Django) and deploy Swarm using Chef.


Next: CloudFront
