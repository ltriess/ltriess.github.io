Take a look at my [webpage](https://larissa.triess.eu)

Getting Started
```
sudo apt-get install ruby-full build-essential zlib1g-dev

echo '# Install Ruby Gems to ~/gems' >> ~/.zshrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.zshrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc

gem install jekyll
gem install bundler -v 2.1.4

bundle install
```
To build the site and serve locally
```
bundle exec jekyll serve

```
