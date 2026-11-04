# publish-probe-app

A fixture for the 3-Torus platform's synthetic user journey (publish leg).
It holds only `.3torus/app.yaml`, which points at the public
[podinfo](https://github.com/stefanprodan/podinfo) image (pinned to a
version tag, which the platform resolves to a digest at submit).

The journey publishes this repo for a synthetic tenant's team, waits for the
test run, deploys it from the marketplace and tears it down. Do not add
secrets or real code here.
