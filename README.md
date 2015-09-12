# 3d-browser-game-walkthrough

### after clone

    docker run -it --rm -v `pwd`:/data totocastaldi/js-development-stack npm install
    docker run -it --rm -v `pwd`:/data totocastaldi/js-development-stack bower install

### run

    docker run -it --rm -v `pwd`:/data -p 9000:9000 -p 35729:35729 totocastaldi/js-development-stack grunt

http://localhost:9000


