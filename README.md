https://docs.rivalz.ai/rclients-ocy-depin/rclient-cli-guide

```shell
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn
```

`yarn --version`

`yarn global add rivalz-node-cli`

`rivalz run`

