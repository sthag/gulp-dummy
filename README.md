# gulp-dummy
A gulp setup for static HTML development

## Prerequisites

$ npm config set proxy http://192.168.181.1:3128  
$ npm config set https-proxy http://192.168.181.1:3128  
$ npm config set strict-ssl false
$ npm config set registry "http://registry.npmjs.org/"

$ npm install -g gulp-cli

## Installation

```
$ cd projectfolder

$ npm init

$ npm install -D gulp jshint

$ npm install -D gulp-jshint gulp-ruby-sass gulp-rename del gulp-concat pump gulp-sourcemaps gulp-autoprefixer gulp-cssnano gulp-uglify gulp-cached gulp-remember gulp-changed gulp-notify browser-sync

cat > .jshintrc <<EOL
{
  "undef": true,
  "unused": true,
  "globals": {

  }
}
EOL

```
