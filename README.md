# GitHub Docker test

Proof of concept repository to let a user add a dockerfile which is built and distributed through github actions. The intention is that a user can eventually build a singularity container which is made available on a scientific compute cluster.
For now the image is built and available in the artifacts, but these are automatically deleted when the action is finished. You can inspect and adjust the `.github/workflows/docker-image.yml` to make your action specific for your use-case.

Just MR your dockerfile into the `Dockerfiles/` folder and it the file will be built using docker.
