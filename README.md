# Purifier for Kohana

Overloads [Security::xss_clean](http://kohanaframework.org/guide/api/Security#xss_clean) to provide secure XSS filtering using [HTMLPurifier](http://htmlpurifier.org/).

# Installation

## Using Git

Using Git, you can simply add this repository as a submodule to your existing Git project:

    git submodule add git://github.com/shadowhand/purifier.git modules/purifier
    git submodule update --init

If you want to use a specific version, you can check out a tag:

    cd modules/purifier
    git checkout 0.1.0
    cd -
    git add modules/purifier

Always remember to commit changes you make to submodules!

    git commit -m 'Added Purifier module'

## FTP or Plain Files

For an untracked repository, you can [download](http://github.com/shadowhand/purifier/archives/master) the repository and install it to `MODPATH/purifier`.

To download a specific version, select the tag on Github before clicking the download link.

# Usage

Use [Security::xss_clean](http://kohanaframework.org/guide/api/Security#xss_clean) as you normally would.
