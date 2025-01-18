 ____  _            _
|  _ \(_)_   ____ _| |____
| |_) | \ \ / / _` | |_  /
|  _ <| |\ V / (_| | |/ /
|_| \_\_| \_/ \__,_|_/___| v3.0.1

https://docs.rivalz.ai/rclients-ocy-depin/rclient-cli-guide

```shell
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn
```

`yarn --version`
1.22.22

`yarn global add rivalz-node-cli`

"yarn global v1.22.22
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
[4/4] Building fresh packages...
"

`rivalz run`

