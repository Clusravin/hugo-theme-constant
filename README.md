# Hugo Theme: Constant

A minimal theme for Hugo. 

![Constant](https://github.com/Clusravin/hugo-theme-constant/blob/master/images/screenshot.png?raw=true)

## Live demo

Demo site hosted on [Github Pages](https://clusravin.github.io/hugo-theme-constant/).

## Installation

Create a theme folder and add the [repo](https://github.com/Clusravin/hugo-theme-constant/).

```sh
$ mkdir themes
$ cd themes
$ git submodule add https://github.com/Clusravin/hugo-theme-constant.git hugo-theme-constant
```
    
See the [Hugo documentation](https://gohugo.io/themes/installing/) for more information.

## Configuration

Set theme parameter in your config file.

```
theme = "hugo-theme-constant"
```

## Example Site

Run Hugo server to set up the example site.

```
make hugo-server
```

### Start page

The default start page template is located at ```themes/hugo-theme-constant/layouts/index.html```. To change the page content, you to need to copy this file to 
your website top-level ```layouts``` folder (```layouts/index.html```).

## License

Copyright © 2024 [Fan Zirui](https://github.com/Clusravin/)

The theme is released under the MIT License. Check the [original theme license](https://github.com/mrmierzejewski/hugo-theme-console/blob/master/LICENSE) for additional licensing information.
