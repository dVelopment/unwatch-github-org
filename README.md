# unwatch-github

This is a simple tool to automtically unwatch all repositories for a given
organization. It assumes you have 2 factor authentication turned on. I have not
tested what happens if you don't have 2 factor authentication turned on. It could
just work if you then enter _anything_ when prompted to.

## Usage

```shell
git clone https://github.com/dVelopment/unwatch-github-org.git
cd unwatch-github-org
# optionally: nvm use
yarn # or `npm i`

# create .env file containing GITHUB_USERNAME and GITHUB_PASSWORD
echo 'GITHUB_USERNAME=myUserName\nGITHUB_PASSWORD=mySecretPassword!' > .env

./unwatch
```
