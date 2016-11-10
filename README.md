Docker container for [slack-irc](https://github.com/ekmartin/slack-irc)
===

### Installation
```
git clone https://github.com/amedia-ops/slackbridge
```

### Configuration

Use a kubernetes secret. For contents, see
https://github.com/amedia-ops/puppet-env-docker/blob/master/kubernetes/slackbridge/config.json
https://github.com/ekmartin/slack-irc#configuration

### Building and running

Build the docker container and push it with:

```
docker build -t dr.api.no/operations/slackbridge .
docker push dr.api.no/operations/slackbridge
```
