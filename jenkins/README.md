# jenkins setup

1. Create custom docker image using jenkinsci/blueocean image.

```sh
docker build -t paulyeo21/sneakersworld-jenkins:1.0.0 .
```

2. Upload custom docker image to docker hub.

```sh
docker login
```

```sh
docker push paulyeo21/sneakersworld-jenkins:1.0.0
```

3. Ssh into remote machine and install jenkins as outlined in setup script.

```sh
scp setup ec2-user@ipaddress:/home/ec2-user/
```

```sh
ssh ec2-user@ipaddress
```

```sh
sh setup
```
