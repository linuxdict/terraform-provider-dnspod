# Terraform Provider DNSPOD

put ```terraform-provider-dnspod``` to .terraform/plugins/linux_amd64/

## Build provider

Run the following command to build the provider

```shell
$ go build -o terraform-provider-dnspod
```

## Test sample configuration

First, build and install the provider.

```shell
$ make install
```

Then, navigate to the `examples` directory. 

```shell
$ cd examples
```

Run the following command to initialize the workspace and apply the sample configuration.

```shell
$ terraform init && terraform apply
```
