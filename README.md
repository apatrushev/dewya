# dewya
Docker Env Wrapper (Yet Another)

This is wrapper for docker client. It provides the ability to select
the one of your dockers from preconfigured list placed in ~/.dewya configuration file.

Example config:
```
tcp://127.0.0.1:2375
ssh://some-host:2375
tcp://some-other-host:2375
```

It's really helpful if you have a bunch (not too big, actually) of
docker servers somewhere.

Current implementation making a lot of assumptions about environment
which is based on MacOS X with homebrew-installed docker clients.

Wrapper needs only python (tested with 2.7.10 and 3.5.0), config
file and homebrew-installed docker clients.
