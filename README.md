# oauth2orize-audience

[OAuth2orize](https://github.com/jaredhanson/oauth2orize) extension providing
support for audience indicators.

## Install

    $ npm install oauth2orize-audience

## Usage

#### Parse Request Extensions

In order to parse the additional parameters used to indicate an audience,
register support for this extension with a `Server` instance:

```js
server.grant(require('oauth2orize-audience').extensions());
```

## License

[The MIT License](http://opensource.org/licenses/MIT)

Copyright (c) 2016-2017 Jared Hanson <[http://jaredhanson.net/](http://jaredhanson.net/)>

<a target='_blank' rel='nofollow' href='https://app.codesponsor.io/link/vK9dyjRnnWsMzzJTQ57fRJpH/jaredhanson/oauth2orize-audience'>  <img alt='Sponsor' width='888' height='68' src='https://app.codesponsor.io/embed/vK9dyjRnnWsMzzJTQ57fRJpH/jaredhanson/oauth2orize-audience.svg' /></a>
