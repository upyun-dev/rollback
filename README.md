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
ansistrano_deploy_to: "/var/www/my-app"

# Folder name for the releases
ansistrano_version_dir: "releases"

# Softlink name for the current release
ansistrano_current_dir: "current"

# Remove rolled back release?
ansistrano_remove_rolled_back: yes
```