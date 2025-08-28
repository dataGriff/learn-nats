# learn-nats

## pre-requisites

### install homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
export PATH="/home/linuxbrew/.linuxbrew/bin:$PATH"
echo 'export PATH="/home/linuxbrew/.linuxbrew/bin:$PATH"' >> ~/.bashrc
```

### Taskfile

```bash
# install taskfile
brew install go-task/tap/go-task
```

### Nats

```bash
# install nats cli
brew install nats-server
brew tap nats-io/nats-tools
brew install nats-io/nats-tools/nats
```

```bash
docker pull nats
```
