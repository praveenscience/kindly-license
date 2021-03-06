# The KINDLY License [![Donate now][donate-now]][paypal-donations]
A human readable license designed for open-source projects.

## Why yet another open-source license?
I'm not a supporter of closed source software. I do not use closed source software
and I do not promote it. This license contains simple and human readable terms.
It lets the author to decide if he/she allows using their work in closed source
projects or not. :four_leaf_clover:

## The license content

```
The KINDLY License
Copyright (c) <year> <author>

You have the permission to use this software, read its source code, modify and
redistribute it under the following terms:

 - if you want to use this software or include parts of its code in a
   closed-source or commercial project you should kindly ask the
   author (via a private message or email) and get a positive answer
 - this license should be included in the modified versions of this software
 - in case of redistributing modified copies, you are encouraged to clearly
   indicate that the copies are based on this work
 - if you think that your redistributed copy is awesome, you are encouraged to
   show the author of this software what you did and how you helped the others

You are free to install and use this software on as many machines as you want,
free of charge, making sure you met the terms above.

You are encouraged to kindly support the software and its author by:

 - sharing his/her work
 - reporting issues/bugs and asking for feature requests
 - donating money or any other things that can help the author
 - contribute on the software code by fixing bugs and adding features
```

## Usage
### Online
You can use the online version to get a copy of the license:

```
http://ionicabizau.github.io/kindly-license/?author=Your%20Name&year=2014
```

[Here is an example](http://ionicabizau.github.io/kindly-license/?author=Ionic%C4%83%20Biz%C4%83u&year=2014).

### Command line
You can use this as command line tool and generate KINDLY licenses providing
the copyright data.

```sh
$ npm install -g kindly-license
$ kindly-license --help
```

### Using as library
If you want to use it programmatically, that's possible too. See [this document](/DOCUMENTATION.md).

```js
// Dependencies
var KindlyLicense = require("kindly-license");

// Output a copy of the license
console.log(KindlyLicense(new Date().getFullYear(), "Your Name"));
```


## How to contribute
Have an idea? Found a bug? See [how to contribute](/CONTRIBUTING.md).

### Editing the license content
If you found a way to improve the license content, there are two places where
you have to change it:

 - in the `LICENSE.kindly` file
 - in `README.md` (*The license content*)

After modifying `LICENSE.kindly` you can run `npm run install` to update the
other files.

## License
See the [LICENSE](./LICENSE) file.

[donate-now]: http://i.imgur.com/jioicaN.png
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MG98D7NPFZ3MG
