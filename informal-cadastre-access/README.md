# Informal Cadastre Mirror Access

Public signed access files for the QGIS Informal Cadastre Mirror plugin.

The files are public so plugin users do not need a GitHub token. Access control is still owner-controlled because the plugin verifies `access.yml` against `access.yml.sig` using a public key embedded in the plugin. Only the private signing key can create a valid signature after changing `access: granted` or `access: denied`.

To change access, edit and sign from the plugin project, then upload both:

- `access.yml`
- `access.yml.sig`
