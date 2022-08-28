# CDK for Terraform

All commands listed below where done using [Install CDK for Terraform and Run a Quick Start Demo](https://learn.hashicorp.com/tutorials/terraform/cdktf-install?in=terraform/cdktf):

```
# init CDKTF
cdktf init --template=python --local

# activate project
pipenv shell

# compile
pipenv run ./main.py

# synthesize
cdktf synth

# diff
cdktf diff

# deploy
cdktf deploy

# destroy
cdktf destroy

# add Docker provider
cdktf provider add kreuzwerker/docker
```