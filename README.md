***WARNING: THIS REPO IS AN AUTO-GENERATED COPY.*** *This repo has been copied from [Gruntwork’s](https://gruntwork.io/) GitHub repositories so that you can consume it from your company’s own internal Git repositories. This copy is automatically created and updated by the `repo-copier` CLI tool. If you need to make changes to this repo, you should make the changes in a separate fork, and NOT make changes directly in this repo, as otherwise, the `repo-copier` will overwrite your changes! Please see the `repo-copier` [documentation](https://github.com/terraform-modules-krish/repo-copier) for more information on how the code is copied, how cross-references are updated, how the changelog is handled, etc.*

***

_You may find it valuable to view the following resources in the original repo. If these links give you a 404, visit https://app.gruntwork.io to gain access or email support@gruntwork.io if you need assistance._

[Home Page](https://github.com/gruntwork-io/infrastructure-as-code-testing-talk/) |
[Pull Requests](https://github.com/gruntwork-io/infrastructure-as-code-testing-talk/pulls) |
[Issues](https://github.com/gruntwork-io/infrastructure-as-code-testing-talk/issues) |
[Releases and Assets](https://github.com/gruntwork-io/infrastructure-as-code-testing-talk/releases)

_Alternatively, you can view a copied version of the resources listed above._

[Pull Requests](https://github.com/terraform-modules-krish/infrastructure-as-code-testing-talk/blob/master/.github/PULL_REQUESTS.md) |
[Issues](https://github.com/terraform-modules-krish/infrastructure-as-code-testing-talk/blob/master/.github/ISSUES.md) |
[ChangeLog](https://github.com/terraform-modules-krish/infrastructure-as-code-testing-talk/blob/master/.github/CHANGELOG.md)

***

# Infrastructure as code testing talk

This repo contains sample code for the talk [How to test your infrastructure code: automated testing for Terraform,
Docker, Packer, Kubernetes, and more](https://www.infoq.com/presentations/automated-testing-terraform-docker-packer/) by
[Yevgeniy Brikman](https://www.ybrikman.com/), with updates for AWS CDK by Ben Whaley.

**Note**: This repo is for demonstration and learning purposes only and should NOT be used to run anything important.
For production-ready versions of this code and many other types of infrastructure, check out
[Gruntwork](https://gruntwork.io/).

## Overview of the repo

This repo contains:

* [modules](https://github.com/terraform-modules-krish/infrastructure-as-code-testing-talk/blob/master/modules): a simple Terraform module and [AWS CDK](https://github.com/aws/aws-cdk/) app used throughout the talk to demonstrate automated testing practices.
* [examples](https://github.com/terraform-modules-krish/infrastructure-as-code-testing-talk/blob/master/examples): examples of (a) how to use the Terraform module in `/modules` and (b) how to deploy
  Dockerized apps to Kubernetes.
* [test](https://github.com/terraform-modules-krish/infrastructure-as-code-testing-talk/blob/master/test): automated tests for each of the examples in the `/examples` folder.

Dive into each of the folders above for more information!

## Running the examples manually

Check out the README in each of the examples in the [examples](https://github.com/terraform-modules-krish/infrastructure-as-code-testing-talk/blob/master/examples) folder for instructions on how to run them
manually.

## Running the automated tests

Check out the README in the [test](https://github.com/terraform-modules-krish/infrastructure-as-code-testing-talk/blob/master/test) folder for instructions on how to run the automated tests.

## License

See [LICENSE.txt](LICENSE.txt).
