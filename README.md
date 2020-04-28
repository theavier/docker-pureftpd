# docker-pureftpd

Instrucktions for building your own image of pureftpd repository and deploying with docker-compose. Works nicely for raspberry

1. Download source
Git clone https://github.com/stilliard/docker-pure-ftpd.git
2. build image from repository, name it pureftpd
docker build --tag pureftpd:1.0 .
3. Download this docker-compose.yml
git clone https://github.com/theavier/docker-pureftpd.git 
4. run docker-compose, edit to change password etc
docker-compose up -d
5. access on port 21, listing not available.
