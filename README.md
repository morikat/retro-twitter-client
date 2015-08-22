# retro-twitter-client
A retro twitter client.

![](/images/preview.png)

## Development
### npm run setup
Set up your development environment for this project.

```
$ npm run setup

> retro-twitter-client@0.0.1 setup /Users/r7kamura/src/github.com/r7kamura/retro-twitter-client
> npm install
```

### npm run package
Package and distribute the app in OS executables for Mac and Win.

```
$ npm run package

> retro-twitter-client@0.0.1 package /Users/r7kamura/src/github.com/r7kamura/retro-twitter-client
> electron-packager . retro-twitter-client --arch=x64 --out=packages/v0.0.1 --platform=darwin,win32 --version=0.31.0

Packaging app for platform darwin x64 using electron v0.31.0
Packaging app for platform win32 x64 using electron v0.31.0
Wrote new apps to:
packages/v0.0.1/retro-twitter-client-darwin-x64
packages/v0.0.1/retro-twitter-client-win32-x64
```

### npm run start
Launch the application.

```
$ npm run start

> retro-twitter-client@0.0.1 start /Users/r7kamura/src/github.com/r7kamura/retro-twitter-client
> electron .

[61547:0822/231648:WARNING:dns_config_service_posix.cc(143)] dns_config has unhandled options!
[61551:0822/231648:INFO:renderer_main.cc(200)] Renderer process started
```

## npm run release
Release a new version of the app.

```
$ npm run release
```
