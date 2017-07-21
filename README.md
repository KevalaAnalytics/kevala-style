# kevala-style
Use to style your Kevala application!

## Use
jsDelivr is a free service that saves us from C&Ping our style files every time.
To use this service you only need to know what version you need. You can find different versions available on the [Releases](https://github.com/KevalaAnalytics/kevala-style/releases) and [Tags](https://github.com/KevalaAnalytics/kevala-style/tags) pages. For more information,
[read the docs](https://github.com/jsdelivr/jsdelivr#usage)!

Add the following to your web application to use this style:
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/KevalaAnalytics/kevala-style@<VERSION>/kevala.css" type="text/css">
```

If the size of the file matters you can add `.min` before `.css`.
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/KevalaAnalytics/kevala-style@<VERSION>/kevala.min.css" type="text/css">
```

## Reference
[Use this online reference](https://kevalaanalytics.github.io/kevala-style/index.html), to view the available styling classes.

Located here:
```
https://kevalaanalytics.github.io/kevala-style/index.html
```

## Contribute

### Dependencies
* First, install Ruby 2 (This is needed to install Sass so < 2 may work)
* Then, install Sass `gem install sass`

### Develop
To develop, run the following command to generate the `kevala.css` file from the
base directory.
```
sass --watch sass/:.
```
This command is watching for any changes in the `sass` directory and outputting
the 'compiled' style to the base directory.
