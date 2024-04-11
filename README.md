# Bcomms liveness Buildpack

A buildpack whose intent is to inject the bcomms liveness binary.

### Usage

```bash
pack build bcomms-liveness --builder cnbs/sample-builder:jammy --buildpack .
```

THEN

```
docker run bcomms-liveness echo hello
```
