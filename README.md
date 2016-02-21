# atom-backup
My config and packages for atom editor 

## Backup

### First

`apm install package-sync` and run Package Sync:create package list to backup packages.

## Second

git commit and push to backup `.atom` files

## Restore

### First 

clone this repository to `~/.atom` directory, and replace the old files.

### Second

`apm install package-sync` and run Package Sync:sync to sync packages.
