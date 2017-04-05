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
updeployment_deploy_to: "/var/www/my-app"

# Folder name for the releases
updeployment_version_dir: "releases"

# Softlink name for the current release
updeployment_current_dir: "current"

# Remove rolled back release?
updeployment_remove_rolled_back: yes
```