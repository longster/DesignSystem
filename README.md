# About Design System
Creating a minimalistic design system that encompases all of the principles, best practices, theory, resources, and tools to build a foundation user experience that can apply wide range of project.

## Getting Started
This framework uses Jekyll + Gulp + Browser-sync + Bootstrap 4 + Font-Awesome

## Requirements
### https://jekyllrb.com/docs/installation/
- Ruby (refer to jekyll documentation)
- RubyGems (refer to jekyll documentation)
- NodeJS (sudo apt-get install nodejs)
- NPM (sudo apt-get install npm)
- Gulp (sudo npm install gulp -g)

## Jekyll Bootstrap 4.1 Installation
1. Clone or download this respository.
2. Run 'npm install' via cmd line to get all of the node dependancies, this will also install Gulp for compiling scss and js.
3. Run "gulp" via the cmd line to compile uncompressed sass and js as well as build the website in _site. It will also start Browsersync to watch for changes.
4. Copy _site contents to your live server.

### Credit
Original creator for this awesome build process goes to https://github.com/soulroll/jekyll-bootstrap-4

### File Structure
```
DesignSystem/
├── _data/
├── _includes/
├── _layouts/
├── _pages/
├── _posts/
├── _site/
├── assets/
	├── _js/
		├── src
            ├──app.js
	├── _scss/
		├── text1.txt
	├── css/
		├── main.css
	├── fonts/
        ├──FontAwesome
            ├── fontawesome-webfont.eot
            ├── fontawesome-webfont.svg
            ├── fontawesome-webfont.ttf
            ├── fontawesome-webfont.woff
            ├── fontawesome-webfont.woff2
            ├── FontAwesome.otf
    ├── img/
	├── js/
		├── app.bundle.js
_config.yml
.gitignore
Gemfile
Gemfile.lock
Gulpfile.js
index.html
404.html
package-lock.json
package.json
README.md
```

### Usage
