# the official website of the MIT women's ultimate team: sMITe!

## dev
to run locally, go to the root directory of this repository and run `python -m SimpleHTTPServer` (Python 2) or `python -m http.server` (Python 3). navigate to `localhost:8000` in a browser to view the site. 

to update the film room:
- install the bundler and jekyll gems with `gem install bundler jekyll`; refer to http://jekyllrb.com/docs/installation/ for prerequisites
- add posts to the `film-room-jekyll/_posts` folder
- run `bundle exec jekyll build` in the `film-room-jekyll` directory; this will generate to the `film-room` directory, and changes can be seen at `localhost:8000/film-room`

## deployment
ssh into the women's ultimate scripts box and run `git pull` in the `web_scripts` directory. the site will redeploy automatically. 
