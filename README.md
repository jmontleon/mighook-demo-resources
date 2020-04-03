# Mediawiki Hook Demo Resources
These resources were used to produce the MigHook demo at [Youtube Demo](https://www.youtube.com/watch?v=so5UJENeB-4).

In order to reproduce the demo run these commands on your source cluster:
`oc create project mediawiki`
`oc create -f mariadb.yml`
`oc create -f mediawiki.yml`

When done setup CAM if you have not already. Run a migration and add a postRestore hook uploading `mediawiki-playbook.yml` as the playbook to run. Complete plan configuration and run a migration of the namespace.
