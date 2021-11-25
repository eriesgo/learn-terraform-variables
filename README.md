# Learn Terraform variables

You can use input variables to customize your Terraform configuration with
values that can be assigned by end users of your configuration. Input variables
allow users to re-use and customize configuration by providing a consistent
interface to change how a given configuration behaves.

Follow along with this [tutorial on HashiCorp
Learn](https://learn.hashicorp.com/tutorials/terraform/variables?in=terraform/configuration-language).

# Personal notes

Updated the Terraform configuration.

Terraform supports several collection variable types.

- List: A sequence of values of the same type.
- Map: A lookup table, matching keys to values, all of the same type.
- Set: An unordered collection of unique values, all of the same type.

You can use `terraform console` to explore functions and manipulate variables

You can use `terraform.tfvars` to store values for variables without default values out of the configuration files. These *.tfvars files should be not tracked in git.

