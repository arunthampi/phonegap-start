# PhoneGap Build Starter Application

> A Hello World application to get started with PhoneGap Build.

## Usage

### Run Application

    /www/index.html

### Run Tests

    /www/spec.html

### Hack on Nitrous.IO

Get Set Up with the Phonegap Starter App on
[Nitrous.IO](https://www.nitrous.io) in a matter of seconds.

[![Hack phonegap/phonegap-start on
Nitrous.IO](https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-l-v1-3cc067e71372f6045e1949af9d96095b.png)](https://www.nitrous.io/hack_button?source=embed&runtime=nodejs&repo=phonegap%2Fphonegap-start&file_to_open=README.nitrous.md)

### PhoneGap/Build

Create a new app with the following repository:

    https://github.com/phonegap/phonegap-start.git

## Updating the Application

The application is based on the [Apache Cordova Hello World][cordova-app] app.

### 1. Update the Source

    cp cordova-app-hello-world/www www/

__Do not replace `www/config.xml`.__

__Do not replace `www/img/logo.png`.__

### 2. Update index.html

Replace `<h1>Apache Cordova</h1>` with `<h1>PhoneGap</h1>`.

### 3. Update PhoneGap Version

    <preference name="phonegap-version" value="x.x.x" />

### 4. Commit

    $ git commit -am "Version x.x.x"

### 5. Tag

    $ git tag x.x.x

[cordova-app]: http://github.com/apache/cordova-app-hello-world

