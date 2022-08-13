# LaravelAutoDeployCPanel-
Auto deploy yml for auto deploying Laravel on CPanel

```yaml
deployment:
  tasks:
    - export DEPLOYPATH=/home/cpanel_user_name/public_html/
    - /bin/cp -R app $DEPLOYPATH
    - /bin/cp -R bootstrap $DEPLOYPATH
    - /bin/cp -R config $DEPLOYPATH
    - /bin/cp -R database $DEPLOYPATH
    - /bin/cp -R public $DEPLOYPATH
    - /bin/cp -R resources $DEPLOYPATH
    - /bin/cp -R routes $DEPLOYPATH
    - /bin/cp -R storage $DEPLOYPATH
    - /bin/cp -R tests $DEPLOYPATH
    - /bin/cp -R .editorconfig $DEPLOYPATH
    - /bin/cp -R .env.example $DEPLOYPATH
    - /bin/cp -R .gitattributes $DEPLOYPATH
    - /bin/cp -R .gitignore $DEPLOYPATH
    - /bin/cp -R .php-cs-fixer.cache $DEPLOYPATH
    - /bin/cp -R .php-cs-fixer.dist.php $DEPLOYPATH
    - /bin/cp -R .styleci.yml $DEPLOYPATH
    - /bin/cp -R README.md $DEPLOYPATH
    - /bin/cp -R artisan $DEPLOYPATH
    - /bin/cp -R composer.json $DEPLOYPATH
    - /bin/cp -R package-lock.json $DEPLOYPATH
    - /bin/cp -R phpunit.xml $DEPLOYPATH
    - /bin/cp -R server.php $DEPLOYPATH
    - /bin/cp -R tailwind.config.js   $DEPLOYPATH
    - /bin/cp -R composer.lock $DEPLOYPATH
    - /bin/cp -R package.json $DEPLOYPATH
    - /bin/cp -R webpack.mix.js  $DEPLOYPATH
```
