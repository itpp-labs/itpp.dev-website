[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)


Source of the https://itpp.dev website

# How to contribute

## Initialization

* Fork this repo
* Clone to your machine

      git clone --recursive <URL>

* [Install](https://gohugo.io/getting-started/installing) hugo:

      cd /tmp
      wget https://github.com/gohugoio/hugo/releases/download/v0.57.2/hugo_0.57.2_Linux-64bit.deb
      sudo dpkg -i hugo*.deb

## Make updates

### To preview updates

      cd hugo
      hugo server -D

### To update content

* make updates
* preview updates
* send pull request to this repo

### To update theme

* check folder ``hugo/themes/``
* make updates
* preview updates
* make git commit
* send pull request to theme repo
* update theme version

       cd hugo/themes/THEME
       git checkout COMMIT_REFEREN CE
       cd ..
       git commit -a -m "theme updated"

* send pull request to this repo
