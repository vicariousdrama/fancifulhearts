# fancifulhearts

doing setup

```
cd ~
mkdir ~/gems
sudo apt-get install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
sudo gem install jekyll bundler
sudo gem install jekyll-sitemap
sudo gem install jekyll-seo-tag
sudo gem install jekyll-paginate
sudo gem install jekyll-feed
cd ~/fancifulhearts
bundle exec jekyll serve
```