# Unraid templates

Docker container templates for Unraid.

| Template | Image |
|---|---|
| [ornge-tracker](ornge-tracker/ornge-tracker.xml) | `ghcr.io/hazardousmedic/ornge-tracker:latest`, a live map of Ornge air ambulance aircraft |

## Installing a template

1. Download the template's `.xml` file and copy it to the Unraid flash drive as
   `config/plugins/dockerMan/templates-user/my-<name>.xml`, which over the network is
   `\\<server>\flash\config\plugins\dockerMan\templates-user\`.
2. In Unraid, go to Docker → Add Container → Template, and pick it under "User templates".
