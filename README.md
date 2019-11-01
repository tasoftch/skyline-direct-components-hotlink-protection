# Skyline Component Hotlink Protection
This package extends the direct component delivery system with hotlink protection.

#### Installation
```bin
$ composer require skyline/direct-components-hotlink-protection
```

The package only contains a plugin that will stop component delivery, if the HTTP referer and the current host don't match.