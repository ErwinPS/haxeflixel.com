```
title: "Flixel Tools"
```


//todo




To make HaxeFlixel development easier a set of command line tools has been developed with [Haxe](http://haxe.org) and [Neko](http://nekovm.org). With it you can easily create our demo projects, templates and more. Just like HaxeFlixel it is an opensource tool and additions/improvements from the community are welcome at the [Flixel Tools Github repository](https://github.com/HaxeFlixel/flixel-tools).

###Installation:

- You need to make sure you have git installed, [git](http://git-scm.com/download/).

- Please make sure you are also running the latest version of haxelib you can make sure with the command:
```haxelib selfupdate```

####Run the following set of commands to install the tools:

To clone this repo to your haxelib directory:

```
haxelib git flixel-tools https://github.com/HaxeFlixel/flixel-tools.git
```

To set the tools up initially / to be able to use the `flixel` alias in your console:

```
haxelib run flixel-tools setup
```

To clone the [flixel-demos](https://github.com/HaxeFlixel/flixel-demos) repo (for demo creation):

```
flixel download
```

###Commands

Create a new demo (in the current directory):

```
flixel create <name_or_number>
```

If no name or number is given it will list all demos and prompt you for a choice, by number or name.

To create a new default game template use the following, with -n option being the name you want:

```
flixel template -n <name>
```
- Currently the templates created are only compatible with the latest dev branch of flixel. For flixel 2.x use the command: ```haxelib run flixel new -name <name>```