# CLAide Changelog

## Master

###### Enhancements

* Use the Argument class to describe arguments.
  [Olivier Halligon][AliSoftware]
  [#33](https://github.com/CocoaPods/CLAide/issues/33)

* Support for argument alternatives and repeatable arguments (ellipsis)
  [Olivier Halligon][AliSoftware]
  [#33](https://github.com/CocoaPods/CLAide/issues/33)

## 0.6.1

###### Bug Fixes

* Respect the ANSI flag for the help banner.
  [Fabio Pelosin][irrationalfab]
  [#34](https://github.com/CocoaPods/CLAide/issues/34)

* Underline the colon of the titles of the help banner.
  [Fabio Pelosin][irrationalfab]

## 0.6.0

###### Enhancements

* Use an array to describe arguments.  
  [Fabio Pelosin][irrationalfab]
  [#26](https://github.com/CocoaPods/CLAide/issues/26)

* Improved layout and contents of help banner
  [Fabio Pelosin][irrationalfab]
  [#25](https://github.com/CocoaPods/CLAide/pull/25)

* Colorize option, arguments, and example commands in the help banner.  
  [Fabio Pelosin][irrationalfab]
  [#12](https://github.com/CocoaPods/CLAide/issues/12)

* Add support for ANSI escape sequences.  
  [Fabio Pelosin][irrationalfab]
  [#17](https://github.com/CocoaPods/CLAide/issues/17)
  [#20](https://github.com/CocoaPods/CLAide/pull/20)
  [#24](https://github.com/CocoaPods/CLAide/pull/24)

* Add support for completion script
  [Fabio Pelosin][irrationalfab]
  [#19](https://github.com/CocoaPods/CLAide/pull/19)

* Add support for version logic via the introduction of the `version` class
  attribute to the `CLAide::Commmand` class. If a value for the attribute is
  specified the `--version` flag is added. The `--version --verbose` flags
  include the version of the plugins in the output.  
  [Fabio Pelosin][irrationalfab]
  [#13](https://github.com/CocoaPods/CLAide/issues/13)
  [#14](https://github.com/CocoaPods/CLAide/issues/14)

## 0.5.0

###### Enhancements

* Add a `ignore_in_command_lookup` option to commands, which makes it possible
  to have anonymous command classes that are or only meant to provide common
  functionality, but are otherwise completely ignored during parsing, command
  lookup, and help banner printing.  
  [Eloy Durán](https://github.com/alloy)

* Deprecate the `color` option in favor of `ansi`. This is more abstract and
  can be used for commands that only prettify output by using, for instance,
  the bold ANSI code. This applies to the `CLAide` APIs as well.  
  [Eloy Durán](https://github.com/alloy)

* Add more hooks that allow the user to customize how to prettify output.  
  [Eloy Durán](https://github.com/alloy)

* Word wrap option descriptions to terminal width.  
  [Eloy Durán](https://github.com/alloy)
  [#6](https://github.com/CocoaPods/CLAide/issues/6)


## 0.4.0

###### Enhancements

* Added support for plugins.  
  [Les Hill](https://github.com/leshill)
  [#1](https://github.com/CocoaPods/CLAide/pull/1)

[irrationalfab]: https://github.com/irrationalfab

