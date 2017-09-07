# Easy node version manager

https://github.com/creationix/nvm

Install nvm with 

``` curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.4/install.sh | bash ```

List all node versions 
``` nvm ls-remote ```

Install lts

``` nvm install 6.11.3 ```

Then set it up to your env

``` nvm use 6.11.3 ```

Set a version to default version

``` nvm alias default 6.1.0 ```
