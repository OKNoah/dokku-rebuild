## [Dokku](https://github.com/progrium/dokku) plugin to rebuild an app without a git push

NOTICE: As of dokku v0.3.14, this functionality is included and this plugin is deprecated. Use the command dokku ps:rebuild [app-name] in the official dokku release.

Commands
--------
```
$ dokku help
     rebuild <app>     Rebuilds specified app
     rebuild:all       Rebuilds all apps
```

Installation
------------
```
cd /var/lib/dokku/plugins
git clone https://github.com/scottatron/dokku-rebuild rebuild
```

Tagged releases are compatible with the equivalent Dokku release e.g. Dokku v0.2.x / Dokku Rebuild v0.2.x
