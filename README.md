# gitea-docker
Gitea docker-compose

### Installation
- Clone this repo `git clone https://github.com/uniibu/gitea-docker.git`
- Open the cloned repo `cd gitea-docker`
- Edit the pg.env with your own database password `nano pg.env`
- You can also customize some settings by editing the gitea.env `nano gitea.env`
- Build and Start the container `docker-compose up`
- To simply start an already built container `docker-compose start`
- If you decide to edit the pg.env again you must rung `docker-compose build` to rebuild the container