# Using CircleCI orbs to streamline configuration #

Orbs are shareable packages of CircleCI configuration you can use to simplify your builds and help automate processes.
It simplifies your configuration by allowing you to write a parameterized configuration once and then use it across multiple similar projects. More specifically, an orb is a reusable package of YAML configuration that condenses repeated pieces of config into a single line of code.  

Orbs help you: 
* save time configuring projects.
* increase organizational efficiency.
* simplify third-party integrations.

Thousands of organizations use CircleCI orbs every day to improve and streamline their processes. If you're not already using CircleCI pre-built orbs, check out the [orbs registry](https://circleci.com/developer/orbs), where you can browse CircleCI-authored orbs and those of our many partners and the CircleCI community. 

## Types of Orbs ##
You can use CircleCI's pre-built orbs or create your own.

**Using a pre-built orb**
To use a pre-built orb, copy the config code from the [orbs registry](https://circleci.com/developer/orbs) into your team’s config file. Our extensive list of orbs are held in an open source code library. Try something new without committing days of engineering time to setting up a new system, feature, or DevOps practice.

**Creating your own orb** 
If you don’t see an orb that fits your needs, create a specialized orb using our Best Practices and Getting Started guides. Our Orb Development Kit makes the authoring process simple, with automated testing and deployment on CircleCI. If your team wants to share configuration across multiple projects, exclusive to your organization, you can create private orbs.

## Private vs. Public Orbs ##
You can choose to create a private or public orb. Private orbs are now available to all [paid plans.] https://circleci.com/pricing

### Private orbs ###
 Using a private orb enables you to author an orb while ensuring the following:
* your orb does not appear in the CircleCI Orb Registry.
* your orb cannot be viewed or used by someone outside of your organization.
* your orb cannot be used in a pipeline that does not belong to your organization.

Public orbs are used by most users when authoring and publishing orbs to the CircleCI Orb Registry. When authoring a public orb, you are enabling all CircleCI users to use your orb in their own configurations.

To illustrate this, the following example shows a typical configuration for testing a Node.js application – defining a job with the required steps for testing the application – versus using the test job provided by the circleci/node orb. With orbs, it is possible to write a parameterized configuration once and utilize it across multiple similar projects.

## Learn more about orbs ##

* [Browse the CircleCI pre-built Orb Registry](https://circleci.com/developer/orbs)
* [View orb use case studies](https://circleci.com/orbs/)
* [View orb best practices](https://circleci.com/docs/2.0/orbs-best-practices/#orb-best-practices-guidelines)
* [View orb getting started guide](https://circleci.com/docs/2.0/orb-author-intro/)
* [View the orb development kit](https://circleci.com/docs/2.0/orb-author/#orb-development-kit) 