## Usage

This project includes a script `docker_build.sh` that you can use to build a
Docker image for your Flyte project.

```
# help
./docker_build.sh -h

# build an image with defaults
./docker_build.sh

# build an image with custom values
./docker_build.sh -p my_project -r <REGISTRY> -v <VERSION>
```


## Run
```
cd ProtDiff_flyte / workflows
pyflyte run --remote example.py wf --hyperparameters '{"name": "jay"'
```
