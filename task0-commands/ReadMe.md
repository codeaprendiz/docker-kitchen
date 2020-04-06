## COMMANDS CONTROL

- [here](#place-2)
- [image](#image)
- [images](#images)

## Title

### Place 1

Hello, this is some text to fill in this, , is a link to the second place.



Place one has the fun times of linking here, but I can also link back [here](#place-1).

### Place 2
## image
- rm [id-of-the-image]


To remove the image with specific ID
```bash
$ sudo docker images | grep ubuntu
Password:
ubuntu                               latest                     4e5021d210f6        2 weeks ago         64.2MB
 
$ sudo docker image rm 4e5021d210f6
Untagged: ubuntu:latest
Untagged: ubuntu@sha256:bec5a2727be7fff3d308193cfde3491f8fba1a2ba392b7546b43a051853a341d
Deleted: sha256:4e5021d210f65ebe915670c7089120120bc0a303b90208592851708c1b8c04bd
Deleted: sha256:1d9112746e9d86157c23e426ce87cc2d7bced0ba2ec8ddbdfbcc3093e0769472
Deleted: sha256:efcf4a93c18b5d01aa8e10a2e3b7e2b2eef0378336456d8653e2d123d6232c1e
Deleted: sha256:1e1aa31289fdca521c403edd6b37317bf0a349a941c7f19b6d9d311f59347502
Deleted: sha256:c8be1b8f4d60d99c281fc2db75e0f56df42a83ad2f0b091621ce19357e19d853
```

## images
To show all the images present
```bash
$ sudo docker images               
Password:
REPOSITORY                           TAG                        IMAGE ID            CREATED             SIZE
ubuntu                               latest                     4e5021d210f6        2 weeks ago         64.2MB
busybox                              latest                     83aa35aa1c79        3 weeks ago         1.22MB
```
