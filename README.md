<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="Terraform Boilerplate" />

  &#xa0;

  <!-- <a href="https://bciinfra.netlify.app">Demo</a> -->
</div>

<h1 align="center">Terraform Boilerplate</h1>

<!-- Status -->

<h4 align="center"> 
	🚧  Terraform Boilerplate 🚀 Under construction...  🚧
</h4> 
<hr>
<br>

## :dart: About ##

Describe your project

## :sparkles: Features ##

:heavy_check_mark: Modular;\
:heavy_check_mark: Allows different ENV;\

## :rocket: Technologies ##

The following tools were used in this project:

- [Terraform](https://expo.io/)

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Git](https://git-scm.com) and [Node](https://nodejs.org/en/) installed.

## :checkered_flag: Starting ##

```bash
# Clone this project
$ git clone https://github.com/nebnhoj/terraform-boilerplate-aws

# Access
$ cd terraform-boilerplate-aws

# Add terraform Environment
$ cp ./environment/sample.tfvars.tpl ./environment/{{environment}}.tfvars

# Install dependencies
$ terraform plan -var-file=./environments/{{environment}}.tfvars

# Run the project
$ terraform apply -var-file=./environments/{{environment}}.tfvars

# Check if the instance are being initialize
```

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with :heart: by <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">{{YOUR_NAME}}</a>

&#xa0;

<a href="#top">Back to top</a>
