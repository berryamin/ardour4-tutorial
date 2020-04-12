# ardour4-tutorial
Fully updated version of the Ardour FLOSS manual

# to build the manual

#
git clone https://github.com/berryamin/ardour4-tutorial
cd ardour4-tutorial
git checkout berryamin

# npm
npm install grunt
npm install
grunt  (takes ages due to image minification using optipng )


# Octopress
sudo gem install bundler
bundler install

# Start doc server using Jekyll
jekyll serve
