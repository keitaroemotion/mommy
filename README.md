mommy
============================

The script which monitors your daily Git activity and convert it into
the human readable report 

usage
-------

First, edit the config file

```
$ vi config
~
~ author=Abe Shinzo
~ workdir=~/Develop
~
```

*author* is your author name you use in Git Team Development.
*workdir* is the default repository on which your working git repository located. (if there are no workdir in config file, it automatically looks for the home dir)

Then, install the execution file and config file.

```
$ ./installer
```

Finally,

```
$ mommy
```

then you get the expected result.

For the help:

```
$ mommy -h
```

If you want colored output,

```
$ mommy -c
```

If directory should be looked for recursively, 

```
$ mommy -r
```

## about the author

My name is *Kei Sugano*. Please contact me via tobasojyo@gmail.com for any questions.

