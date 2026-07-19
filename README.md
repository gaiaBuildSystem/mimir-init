
<p align="center">
    <img
        src="https://github.com/gaiaBuildSystem/gaia/raw/main/assets/img/mimirLogo310.png"
        height="212"
    />
</p>

# Mimir Init

This repo is an example of how to use Mimir to create a new Gaia build system project. It also contains an example on how to use Mimir to trigger build using a GitHub Action.

To initialize a new Gaia project, you can use the following command:

```
wget -qO init https://raw.githubusercontent.com/gaiaBuildSystem/mimir-init/refs/heads/main/init && bash init
```

This will check if the environment has the required dependencies installed:

- git
- Docker

This will create e `workdir` directory where you ran the command, then will clone the Gaia core repository into it, and will initialize the sandbox container. From inside the sandbox container you can run the Mimir to continue:

```
./gaia/mimir
```
