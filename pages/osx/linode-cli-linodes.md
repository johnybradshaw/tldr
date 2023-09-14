# linode-cli linodes

> Command-line interface to manage Linode instances via `linode-cli`.

- List all Linodes:

`linode-cli linodes list`

- Create a new Linode:

`linode-cli linodes create --type [linode-type] --region [region] --image [image-id]`

- View details of a specific Linode:

`linode-cli linodes view [linode-id]`

- Update settings for a Linode:

`linode-cli linodes update [linode-id] --label [new-label]`

- Delete a Linode:

`linode-cli linodes delete [linode-id]`

- Boot/reboot/shutdown a Linode:

`linode-cli linodes boot [linode-id]
linode-cli linodes reboot [linode-id]
linode-cli linodes shutdown [linode-id]`

- List available backups for a Linode:

`linode-cli linodes backups-list [linode-id]`

- Restore a backup to a Linode:

`linode-cli linodes backups-restore [linode-id] --backup-id [backup-id]`

For more commands and options, consider using the `--help` flag (e.g., `linode-cli linodes --help`).
