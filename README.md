## What is this?
I'm developing a website for use by Cascade Orienteering Club in conjunction with hosting the Orienteering USA 2020 Junior Nationals event. Current thinking is to just serve a jekyll site directly from github pages because that seems quick and easy.

## Theme
Starting by using a theme I found [here](https://github.com/chrisrhymes/bulma-clean-theme/) with some [docs](http://www.csrhymes.com/bulma-clean-theme/development/2019/02/09/getting-started-with-bulma-clean-theme/)

## To Do List
* Landing Page
* List of Pages / Functions
* Nav
* Layouts
* Content content content
* Editabilty by non-tech folks
* Confirm the COC subdomain can point here

## Dev Environment
Using WSL for this project. 
Navigate to the folder in WSL and run `bundle update` to make sure everything's in place
For normal development, run `bundle exec jekyll serve` and view the site at `localhost:4000/jn2020/`.

To generate files for deployment: `JEKYLL_ENV=production bundle exec jekyll build`
