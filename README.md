# Godfiles
## Feel like the Lord almighty when you $ bash

Godfiles are a collection of bash profile scripts that include a number of aliases and functions to make using your shell that more biblical. It allows such sin-thwarting syntax as:

```bash
$ thou must smite ~/test_file
$ thou shall flee to ~/Sites/godfiles
$ thou will describe ~/some_folder
```

## Installation

Install just for this shell session by including the file:

    $ source .godfiles

Or install permanently:

    $ cp .godfiles ~/ && echo 'source .godfiles' >> ~/.profile
  
## Full reference

Godfiles contains a bunch of different commands to do a large number of things. In order to make it read like biblical English, there are a variety of joining words that do nothing. These are:

    $ thou thee to you moses you me shall shalt
    
Combining these allows us to create sentences. More usefully, we can use some **stronger** verbs to enforce the command, through the use of `sudo`:

    $ thou must smite file
    $ thou will smite file
    
Finally, there are a bunch of commands aliased / patched to do certain tasks.

* `smite` = `rm -fr`
* `flee to` = `cd`
* `describe` = `ls -al`
* `create` = `touch`

Enjoy!

## Contributions

Please contribute as much as you can! It'd be great to have a really comprehensive group of functions. Pull request away, friends. Bonus points for a patch/topic branch, because it makes life that much easier.

Thanks to everyone who's contributed so far:

* [Nick Jackson](https://github.com/jacksonj04)

## Disclaimer

I am a Christian. This is not meant to offend or blaspheme, it's merely a bit of light-hearted fun.

## License

Godfiles is [licensed under the MIT license](http://www.opensource.org/licenses/MIT), which means you can do absolutely anything you want with it, assuming you keep the copyright notices intact. Frankly though, I'm not bothered.