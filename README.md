# CakePHP Test Application for DDEV

This repository is currently using the version 5.0.4 of `cakephp/app`. To update the current version you need:

1. Clone/Pull this repository (main branch).
2. Add git@github.com:cakephp/app.git as a remote: `git remote add cakephg git@github.com:cakephp/app.git`.
3. Pull latest changes from `5.x` branch
4. Run `composer update` to update vendor folder
5. Ensure `vendor` folder is added to commit
6. Push changes to origin (main branch): `ddev/test-cakephp`
7. Download https://github.com/ddev/test-cakephp/releases/download/5.0.1.1/db.sql.tar.gz
8. Update TestPkgCakePHP in `ddevapp_test.go` to point to next release OR remove release and tag 5.0.1.1
9. Create release (including tag)  and upload `db.sql.tar.gz` as a release artifact.
