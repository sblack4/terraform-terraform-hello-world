# terraform-terraform-hello-world
hewwo world!

[![tflint](https://github.com/sblack4/terraform-terraform-hello-world/workflows/tflint/badge.svg?branch=master&event=push)](https://github.com/sblack4/terraform-terraform-hello-world/actions?query=workflow%3Atflint+event%3Apush+branch%3Amaster)
[![tfsec](https://github.com/sblack4/terraform-terraform-hello-world/workflows/tfsec/badge.svg?branch=master&event=push)](https://github.com/sblack4/terraform-terraform-hello-world/actions?query=workflow%3Atfsec+event%3Apush+branch%3Amaster)
[![yamllint](https://github.com/sblack4/terraform-terraform-hello-world/workflows/yamllint/badge.svg?branch=master&event=push)](https://github.com/sblack4/terraform-terraform-hello-world/actions?query=workflow%3Ayamllint+event%3Apush+branch%3Amaster)
[![misspell](https://github.com/sblack4/terraform-terraform-hello-world/workflows/misspell/badge.svg?branch=master&event=push)](https://github.com/sblack4/terraform-terraform-hello-world/actions?query=workflow%3Amisspell+event%3Apush+branch%3Amaster)
[![pre-commit-check](https://github.com/sblack4/terraform-terraform-hello-world/workflows/pre-commit-check/badge.svg?branch=master&event=push)](https://github.com/sblack4/terraform-terraform-hello-world/actions?query=workflow%3Apre-commit-check+event%3Apush+branch%3Amaster)
<a href="https://twitter.com/intent/follow?screen_name=RhythmicTech"><img src="https://img.shields.io/twitter/follow/RhythmicTech?style=social&logo=twitter" alt="follow on Twitter"></a>

## Example
Here's what using the module will look like
```hcl
module "example" {
  source = "rhythmictech/terraform-mycloud-mymodule
}
```

## About
A bit about this module

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| terraform | >= 0.12.14 |

## Providers

No provider.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| name | Moniker to apply to all resources in the module | `string` | n/a | yes |
| tags | User-Defined tags | `map(string)` | `{}` | no |

## Outputs

| Name | Description |
|------|-------------|
| hello | We want to cordinally greet all newcomers to terraform |
| tags\_module | Tags Module in it's entirety |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

## The Giants Underneath this Module
- [pre-commit.com](pre-commit.com)
- [terraform.io](terraform.io)
- [github.com/tfutils/tfenv](github.com/tfutils/tfenv)
- [github.com/segmentio/terraform-docs](github.com/segmentio/terraform-docs)
