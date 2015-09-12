# 3d-browser-game-walkthrough

### after clone

    docker run -it --rm -v `pwd`:/data totocastaldi/grunt-bower-beefy npm install
    docker run -it --rm -v `pwd`:/data totocastaldi/grunt-bower-beefy bower install

### run

    docker run -it --rm -v `pwd`:/data -p 9000:9000 -p 35729:35729 totocastaldi/grunt-bower-beefy grunt

http://localhost:9000


