<h1 align="center">ScribbleIT</h1>

<p align="center">
  <a href="https://github.com/scribble-rs/scribble.rs/actions">
    <img src="https://github.com/scribble-rs/scribble.rs/workflows/Run%20scribble-rs%20tests/badge.svg">
  </a>
  <a href="https://codecov.io/gh/scribble-rs/scribble.rs">
    <img src="https://codecov.io/gh/scribble-rs/scribble.rs/branch/master/graph/badge.svg">
  </a>
  <a href="https://discord.gg/3sntyCv">
    <img src="https://img.shields.io/discord/693433417395732531.svg?logo=discord">
  </a>
  <a href="https://liberapay.com/biosmarcel/donate">
    <img src="https://img.shields.io/liberapay/receives/biosmarcel.svg?logo=liberapay">
  </a>
  <a href="https://heroku.com/deploy?template=https://github.com/scribble-rs/scribble.rs/tree/master">
    <img src="https://www.herokucdn.com/deploy/button.png">
  </a>
</p>

ScribbleIT is a clone of the web-based drawing game skribbl.io. My main
problems with skribbl.io were the ads and the fact that a disconnect would
cause you to lose your points. On top of that, the automatic word choice was
quite annoying and caused some frustration.

The site will not display any ads or share any data with third parties.

## Play now

Feel free to play on this instance

* https://scribblers-official.herokuapp.com/
  > Might not respond right-away, just wait some seconds / minutes, as it
  > shuts down automatically when unused.

### Hosting your own instance for free

By using Heroku, you can deploy a temporary container that runs scribbleIT.
The container will not have any cost and automatically suspend as soon as it
stops receiving traffic for a while.

Simply create an account at https://id.heroku.com/login and then click this link:

https://heroku.com/deploy?template=https://github.com/Manometer16/Scribble/tree/master

## Building / Running

Run the following to build the application:

```shell
git clone https://github.com/Manometer16/Scribble.git
cd Scribble
```

For -nix systems:
```shell
# run `make` to see all available commands
make build
```

For Windows:
```shell
go run github.com/gobuffalo/packr/v2/packr2
go build -o scribblers .
```

This will produce a portable binary called `scribblers`. The binary doesn't
have any dependencies and should run on every system as long as it has the
same architecture and OS family as the system it was compiled on.

The default port will be `8080`. The parameter `portHTTP` allows changing the
port though.

It should run on any system that go supports as a compilation target.

This application uses go modules, therefore you need to make sure that you
have go version `1.13` or higher.

## Docker

Alternatively there's a docker container:

```shell
docker pull biosmarcel/Scribble
```

### Changing default port

The default port is `8080`. To override it, run:
```shell
docker run -p <port-number>:<port-number> biosmarcel/Scribble --portHTTP=<port-number>
```

## Discord

While you can find a link to a discord server at the top, for personally
reasons you won't find me on that server anymore, however, you can still reach
me via E-Mail or even the issue section.

## Contributing

There are many ways you can contribute:

* Update / Add documentation in the wiki of the GitHub repository
* Extend this README
* Create feature requests and bug reports
* Solve issues by creating Pull Requests
* Tell your friends about the project

## Donating

If you can't or don't want to contribute in any of the ways listed above, you can always donate something to me.

* PayPal: https://www.paypal.com/donate/?hosted_button_id=RZ7N8D95TXFEN
* Liberapay: https://liberapay.com/biosmarcel/donate
* Etherum: 0x49939106563a9de8a777Cf5394149423b1dFd970
* XLM/Lumen: GDNCEW46OTDMXMSNVM4K7GNPIXNYT5BOZXVZ7M4QSRB6OB3BRM2VYDB5

## Credits

These resources are by people unrelated to the project, whilst not every of these
resources requires attribution as per license, we'll do it either way ;)

If you happen to find a mistake here, please make a PR. If you are one of the
authors and feel like we've wronged you, please reach out.

* Favicon - [Fredy Sujono](https://www.iconfinder.com/freud)
* Rubber Icon - Made by [Pixel Buddha](https://www.flaticon.com/authors/pixel-buddha) from [flaticon.com](https://flaticon.com)
* Fill Bucket Icon - Made by [inipagistudio](https://www.flaticon.com/authors/inipagistudio) from [flaticon.com](https://flaticon.com)
* Kicking Icon - [Kicking Icon #309402](https://icon-library.net/icon/kicking-icon-4.html)
* Sound / No sound Icon - Made by Viktor Erikson (If this is you or you know who this is, send me a link to that persons Homepage)
* Profile Icon - Made by [kumakamu](https://www.iconfinder.com/kumakamu)
