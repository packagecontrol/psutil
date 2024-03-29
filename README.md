# *psutil* module for Package Control

[![Github Action](https://github.com/packagecontrol/psutil/workflows/test/badge.svg)](https://github.com/packagecontrol/psutil)


This is the *[psutil][]* module
bundled for usage with [Package Control][],
a package manager
for the [Sublime Text][] text editor.


this repo | pypi
---- | ----
![latest tag](https://img.shields.io/github/tag/packagecontrol/psutil.svg) | [![pypi](https://img.shields.io/pypi/v/psutil.svg)][pypi]

## How to use *psutil* as a dependency

In order to tell Package Control
that you are using the *psutil* module
in your ST package,
create a `dependencies.json` file
in your package root
with the following contents:

```js
{
   "*": {
      "*": [
         "psutil"
      ]
   }
}
```

If the file exists already,
add `"psutil"` to the every dependency list.

Then run the **Package Control: Satisfy Dependencies** command
to make Package Control
install the module for you locally
(if you don't have it already).

After all this
you can use `import psutil`
in any of your Python plugins.

See also:
[Documentation on Dependencies](https://packagecontrol.io/docs/dependencies)


## Contributions


The files were built by github [workflows][].


## License

The contents of the root folder
in this repository
are released
under the *public domain*.
The contents of all the subfolders
fall under *their own bundled licenses*.



[psutil]: https://pypi.org/project/psutil/
[Package Control]: https://packagecontrol.io/
[Sublime Text]: https://sublimetext.com/
[pypi]: https://pypi.python.org/pypi/psutil
[workflows]: https://github.com/packagecontrol/psutil/tree/master/.github/workflows

