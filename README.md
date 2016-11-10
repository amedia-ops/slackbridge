Docker container for [slack-irc](https://github.com/ekmartin/slack-irc)
===

### Installation
```
git clone https://github.com/amedia-ops/slackbridge
```

### Configuration

Use a kubernetes secret. For contents, see
https://github.com/ekmartin/slack-irc#configuration

### Building and running

Build the docker container and run it with:

```
cd slackbridge/docker
docker build -t slackbridge .
docker run -d -t slackbridge
```
