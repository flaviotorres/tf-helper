## `tfh ssh assign`

Assign an SSH key to a Terraform Enterprise workspace

### Synopsis

    tfh ssh assign [OPTIONS]

### Description

Assign a Terraform Enterprise SSH key to a workspace. The workspace and SSH key must already exist.

### Positional parameters

* `NAME`

Workspace name to assign the ssh key to. Overrides the `-name` common option.

### Options

* `-ssh-name NAME`

The name of the SSH key in TFE to assign.

* `-ssh-id ID`

The ID of the SSH key to assign.
