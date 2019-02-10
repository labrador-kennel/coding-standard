# Labrador Coding Standard

A ruleset for PHP_CodeSniffer that defines the coding standard incorporated by Labrador packages.

## Installion

There is only 1 supported method for installing Labrador packages; [Composer]

```
compose require-dev cspray/labrador-coding-standard
```

> Please note that we are installing this as a dev dependency; it is not recommended 
to use this library in a production environment.

## Usage

After installing simply run either of the 2 provided binary commands: `labrador-cs` and `labrador-cbf` 
respectively.

```
vendor/bin/labrador-cs src/ test/
vendor/bin/labrador-cbf src/ test/
```

[Composer]: https://getcomposer.org
