## dodas

A self-sufficient client for DODAS deployments

### Synopsis

A self-sufficient client for DODAS deployments.
Default configuration file searched in $HOME/.dodas.yaml

Usage examples:
"""
# CREATE A CLUSTER FROM TEMPLATE
dodas create --template my_tosca_template.yml

# VALIDATE TOSCA TEMPLATE
dodas validate --template my_tosca_template.yml
"""

```
dodas [flags]
```

### Options

```
      --config string   DODAS config file (default is $HOME/.dodas.yaml)
  -h, --help            help for dodas
  -v, --version         DODAS client version
```

### SEE ALSO

* [dodas create](dodas_create.md)	 - Create a cluster from a TOSCA template
* [dodas destroy](dodas_destroy.md)	 - Destroy infrastructure with this InfID
* [dodas get](dodas_get.md)	 - Wrapper command for get operations
* [dodas list](dodas_list.md)	 - Wrapper function for list operations
* [dodas login](dodas_login.md)	 - WIP feature: ssh login into a deployed vm
* [dodas validate](dodas_validate.md)	 - Validate your tosca template
* [dodas version](dodas_version.md)	 - Client version

###### Auto generated by spf13/cobra on 2-Dec-2019
