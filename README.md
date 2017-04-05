### UPYUN Node.js Application version control utility (Rollback)

folk from ansistrano-deployment

for internal used.

## usage

```yaml
- roles:
  - upyun-dev.rollback
```

## variables

```yml
# Path where the code must be deployed to
rollback_from: "/var/www/my-app"

# Folder name for the releases
rollback_version_dir: "releases"

# Softlink name for the current release
rollback_current_dir: "current"

# Remove rolled back release?
remove_rolled_back: yes
```