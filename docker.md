## Docker Knowledge Issues and Trouble Shooting

`$ docker-compose up`

When having folloving error message

```
ERROR: Couldn't connect to Docker daemon at http+docker://localunixsocket - is it running?

If it's at a non-standard location, specify the URL with the DOCKER_HOST environment variable.
```
add user to docker group

`$ sudo usermode -aG docker ${USER}` 
