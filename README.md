Google APIs Client Library for PHP adapted to Symfony2
=====================================

Description
I'm just trying to use this libraries under php5.3 and symfony2, this repo is beta and ealry development.

Installing

**Using the vendors script**

Add the following lines in your `deps` file:

```
[Sf2GoogleApi]
    git=git://github.com/zeopix/Sf2GoogleApi.git
    target=Sf2GoogleApi
```

Now, run the vendors script to download the bundle:

``` bash
$ php bin/vendors install
```

**Using submodules**

If you prefer instead to use git submodules, the run the following:

``` bash
$ git submodule add git://github.com/zeopix/Sf2GoogleApi.git vendor/Sf2GoogleApi
$ git submodule update --init
```