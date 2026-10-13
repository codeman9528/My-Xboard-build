# My-Xboard-build

Public build & install repo for my private Xboard fork. The admin frontend is built from the private repo My-Xboard-admin during the image build. Image: `ghcr.io/codeman9528/my-xboard`.

Install:

    git clone --depth 1 https://github.com/codeman9528/My-Xboard-build && cd My-Xboard-build
    docker compose up -d

Update: `docker compose pull && docker compose up -d`
