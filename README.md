
# starpeace-website-content

[![Build Status](https://travis-ci.org/ronappleton/starpeace-website-content.svg)](https://travis-ci.org/ronappleton/starpeace-website-content)

Documentation website for [STARPEACE](https://docs.starpeace.io), including game client instructions, rules and overview of gameplay, and game history and lore.

## Security Vulnerabilities

If you discover a security vulnerability within this website, please send an e-mail to security@starpeace.io or open a [GitHub issue](https://github.com/ronappleton/starpeace-website-content/issues). All security vulnerabilities will be promptly addressed.

## Development

Local development can be accomplished in a few commands. The following build-time dependencies must be installed:

* [Node.js](https://nodejs.org/en/) javascript runtime and [npm](https://www.npmjs.com/get-npm) package manager
* [Grunt](https://gruntjs.com/) task manager

Retrieve copy of repository and navigate to root:

```
$ git clone https://github.com/ronappleton/starpeace-website-content.git
$ cd starpeace-website-content
```

Install starpeace-website-content dependencies:

```
$ npm install
```

Build repository with npm command defined in package.json:

```
$ npm run generate
```

Local development with nuxt and interactive build can be started with a single command:

```
$ npm run dev
```

## Build and Deployment

After building repository, website is compiled into static resources within the ```/dist/``` folder. These resources should be served as static assets from web application and can be cached if desired.

## License

Repository is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
