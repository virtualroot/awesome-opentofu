# Awesome OpenTofu [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- omit in toc -->

A refined list of OpenTofu resources and tools.

> OpenTofu lets you declaratively manage your infrastructure. It's an open-source and community-driven alternative to Terraform.

## Contents <!-- omit in toc -->

- [Official](#official)
- [Community](#community)
- [Features](#features)
- [Tools](#tools)
  - [Environment managers](#environment-managers)
  - [Wrappers](#wrappers)
  - [CI](#ci)
  - [Tests](#tests)
  - [State](#state)
  - [Providers](#providers)
  - [Platforms](#platforms)
  - [Registry](#registry)
  - [Helpers](#helpers)
- [Media](#media)
- [Podcasts](#podcasts)

## Official

- [Website](https://opentofu.org/)
- [Fork announcement](https://opentofu.org/announcement)
- [OpenTofu repository](https://github.com/opentofu/opentofu) 🎉
- [Official registry](https://github.com/opentofu/registry)
- [Weekly Updates](https://github.com/opentofu/opentofu/blob/main/WEEKLY_UPDATES.md#weekly-updates)
- [Office Hours](https://www.youtube.com/watch?v=aEoMzUza6Ok&list=PLnVotLM2QsyhCc1_8PA7fbVF-ixt4_XAY)
- [Technical Steering Committee Updates](https://github.com/opentofu/opentofu/blob/main/TSC_SUMMARY.md#technical-steering-committee-tsc-summary)

## Community

*Communication channels, meetups, newsletters and forums.*

- [OpenTofu GitHub Discussion](https://github.com/orgs/opentofu/discussions)
- [OpenTofu LinkedIn](https://www.linkedin.com/company/opentofuorg/)
- [OpenTofu Reddit](https://www.reddit.com/r/opentf/)
- [OpenTofu Slack](https://opentofu.org/slack)
- [OpenTofu Twitter](https://twitter.com/opentofuorg)

## Features

- [End-to-end encryption for state files](https://twitter.com/OpenTofuOrg/status/1696597790661677207) 🚧
- [OCI-compliant registry support](https://twitter.com/OpenTofuOrg/status/1696913055576387599) 🚧

## Tools

### Environment managers

- [asdf-opentofu](https://github.com/virtualroot/asdf-opentofu) - OpenTofu plugin for asdf version manager.
- [tenv](https://github.com/tofuutils/tenv) - Terraform and OpenTofu version manager written in Go.
- [tfswitcher](https://github.com/ASleepyCat/tfswitcher) - Terraform and OpenTofu version switcher written in Rust.
- [tofuenv](https://github.com/tofuutils/tofuenv) - OpenTofu version manager inspired by tfenv.

### Wrappers

*Simplify your OpenTofu workflows with a thin wrapper*

- [Terragrunt](https://terragrunt.gruntwork.io/) - A thin wrapper for OpenTofu that provides extra tools for working with multiple modules.
- [Terramate](https://github.com/terramate-io/terramate) - Automation, orchestration and code generation for OpenTofu, Terraform, Kubernetes, and others.
- [easy_infra](https://github.com/SeisoLLC/easy_infra) - A docker container to simplify and secure the use of Infrastructure as Code.
- [tfam](https://github.com/Ant0wan/tfam) - Rust-based wrapper for concurrent Terraform/OpenTofu apply, enabling multi-deployment support.
- [tfexe](https://github.com/Ant0wan/tfexe) - Rust-powered wrapper for seamless execution of tfswitch and Terraform/OpenTofu with version control.
- [tfwrapper](https://github.com/claranet/tfwrapper) - `tfwrapper` is a Python wrapper that aims to simplify OpenTofu usage and enforce best practices.

### CI

- [pre-commit-opentofu](https://github.com/tofuutils/pre-commit-opentofu) - Git pre-commit hooks plugin for OpenTofu.
- [setup-opentofu](https://github.com/opentofu/setup-opentofu) - Set up OpenTofu CLI in your GitHub Actions workflow.
- [terraform-github-actions](https://github.com/dflook/terraform-github-actions) - GitHub Actions for OpenTofu.
- [tf-via-pr-comments](https://github.com/devsectop/tf-via-pr-comments) - GitHub Action to run Terraform or OpenTofu CLI commands via PR comments.

### Tests

- [Terratest](https://terratest.gruntwork.io/) - Terratest is a Go library that makes it easier to write automated tests for your infrastructure code.

### State

- [tfmigrate](https://github.com/minamijoyo/tfmigrate) - A Terraform state migration tool for GitOps.

### Providers

- [tfschema](https://github.com/minamijoyo/tfschema) - A schema inspector for Terraform / OpenTofu providers.

### Platforms

*Alternatives to Terraform Cloud*

- [digger](https://github.com/diggerhq/digger) - Digger is an open source IaC orchestration tool. Digger allows you to run IaC in your existing CI pipeline.
- [terrakube](https://terrakube.org/) - Open Source alternative to Terraform Enterprise with private registry, remote state, custom flows, scheduled workspaces, and visual states that is compatible with OpenTofu.
- [walrus](https://github.com/seal-io/walrus) - Walrus is an open-source application management platform based on IaC tools including OpenTofu, Terraform and others. It helps platform engineers build golden paths for developers and empowers developers with self-service capabilities.

### Registry

- [boring-registry](https://github.com/boring-registry/boring-registry) - Boring-registry is an open source module and provider registry compatible with Terraform and OpenTofu.

### Helpers

- [terratag](https://github.com/env0/terratag) - Terratag is a CLI tool allowing for tags or labels to be applied across an entire set of OpenTofu/Terraform files. Terratag will apply tags or labels to any AWS, GCP and Azure resources.

## Media

- [OSS EU 2023 - Announcement](https://www.youtube.com/watch?v=Ha77rpusEDM&t=1190s)
- [OSS EU 2023 - Project overview](https://www.youtube.com/watch?v=-8sOE9-icmY&t=15116s)
- [Code To Cloud - Getting Started With OpenTofu](https://www.youtube.com/watch?v=HeUz6TMg82U)

## Podcasts

<!-- DESC, from most recent to oldest. -->
- [TheIaCPodcast - Expert Panel on OpenTofu GA Release, Licensing, and OSS Future](https://www.theiacpodcast.com/episode/expert-panel-on-opentofu-ga-release-licensing-and-oss-future)
- [Contributor - Community Driven IaC](https://www.contributor.fyi/opentofu)
- [Ned in the Cloud - IaC Live Stream](https://www.youtube.com/watch?v=p0vDydkUWB4)
- [Arrested DevOps - What's Up With Open Terraform?](https://www.arresteddevops.com/open-tofu/)
- [OpenObservability - Terraform is no longer open source. Is OpenTF the successor?](https://www.youtube.com/watch?v=5QdUs9VKq5g)
- [TheCloudGambit - The Future of OpenTF](https://www.thecloudgambit.com/2236725/13576531-the-future-of-opentf-with-ohad-maislish)
- [Oxide and Friends - Fork in the road for Terraform?](https://www.youtube.com/watch?v=QaU94LY891M)
- [Changelog -  OpenTF for an open Terraform](https://changelog.com/podcast/556)
