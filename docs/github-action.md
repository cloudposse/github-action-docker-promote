<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| from | Source tag | N/A | false |
| login | Docker login |  | false |
| organization | Organization | N/A | true |
| password | Docker password |  | false |
| registry | Docker registry | N/A | true |
| repository | Repository | N/A | true |
| to | Target tags | N/A | false |
| use\_metadata | Extract target tags from Git reference and GitHub events | true | false |


## Outputs

| Name | Description |
|------|-------------|
| image | Docker image name |
| tag | Docker image tag |
<!-- markdownlint-restore -->
