# test coverage for  [sharp (v0.17.3)](https://github.com/lovell/sharp)  [![npm package](https://img.shields.io/npm/v/npmtest-sharp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sharp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sharp.svg)](https://travis-ci.org/npmtest/node-npmtest-sharp)
#### High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images

[![NPM](https://nodei.co/npm/sharp.png?downloads=true)](https://www.npmjs.com/package/sharp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sharp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sharp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sharp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sharp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sharp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sharp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sharp/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sharp/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-sharp/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-sharp/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-sharp%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sharp/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sharp/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-sharp%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sharp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sharp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sharp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lovell Fuller",
        "email": "npm@lovell.info"
    },
    "bugs": {
        "url": "https://github.com/lovell/sharp/issues"
    },
    "cc": {
        "linelength": "120",
        "filter": [
            "build/include",
            "runtime/indentation_namespace"
        ]
    },
    "config": {
        "libvips": "8.4.2"
    },
    "contributors": [
        {
            "name": "Pierre Inglebert",
            "email": "pierre.inglebert@gmail.com"
        },
        {
            "name": "Jonathan Ong",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "Chanon Sajjamanochai",
            "email": "chanon.s@gmail.com"
        },
        {
            "name": "Juliano Julio",
            "email": "julianojulio@gmail.com"
        },
        {
            "name": "Daniel Gasienica",
            "email": "daniel@gasienica.ch"
        },
        {
            "name": "Julian Walker",
            "email": "julian@fiftythree.com"
        },
        {
            "name": "Amit Pitaru",
            "email": "pitaru.amit@gmail.com"
        },
        {
            "name": "Brandon Aaron",
            "email": "hello.brandon@aaron.sh"
        },
        {
            "name": "Andreas Lind",
            "email": "andreas@one.com"
        },
        {
            "name": "Maurus Cuelenaere",
            "email": "mcuelenaere@gmail.com"
        },
        {
            "name": "Linus Unnebäck",
            "email": "linus@folkdatorn.se"
        },
        {
            "name": "Victor Mateevitsi",
            "email": "mvictoras@gmail.com"
        },
        {
            "name": "Alaric Holloway",
            "email": "alaric.holloway@gmail.com"
        },
        {
            "name": "Bernhard K. Weisshuhn",
            "email": "bkw@codingforce.com"
        },
        {
            "name": "Chris Riley",
            "email": "criley@primedia.com"
        },
        {
            "name": "David Carley",
            "email": "dacarley@gmail.com"
        },
        {
            "name": "John Tobin",
            "email": "john@limelightmobileinc.com"
        },
        {
            "name": "Kenton Gray",
            "email": "kentongray@gmail.com"
        },
        {
            "name": "Felix Bünemann",
            "email": "Felix.Buenemann@gmail.com"
        },
        {
            "name": "Samy Al Zahrani",
            "email": "samyalzahrany@gmail.com"
        },
        {
            "name": "Chintan Thakkar",
            "email": "lemnisk8@gmail.com"
        },
        {
            "name": "F. Orlando Galashan",
            "email": "frulo@gmx.de"
        },
        {
            "name": "Kleis Auke Wolthuizen",
            "email": "info@kleisauke.nl"
        },
        {
            "name": "Matt Hirsch",
            "email": "mhirsch@media.mit.edu"
        },
        {
            "name": "Matthias Thoemmes",
            "email": "thoemmes@gmail.com"
        },
        {
            "name": "Patrick Paskaris",
            "email": "patrick@paskaris.gr"
        },
        {
            "name": "Jérémy Lal",
            "email": "kapouer@melix.org"
        },
        {
            "name": "Rahul Nanwani",
            "email": "r.nanwani@gmail.com"
        },
        {
            "name": "Alice Monday",
            "email": "alice0meta@gmail.com"
        },
        {
            "name": "Kristo Jorgenson",
            "email": "kristo.jorgenson@gmail.com"
        }
    ],
    "dependencies": {
        "caw": "^2.0.0",
        "color": "^1.0.3",
        "got": "^6.7.1",
        "nan": "^2.5.1",
        "semver": "^5.3.0",
        "tar": "^2.2.1"
    },
    "description": "High performance Node.js image processing, the fastest module to resize JPEG, PNG, WebP and TIFF images",
    "devDependencies": {
        "async": "^2.2.0",
        "bufferutil": "^3.0.0",
        "cc": "^1.0.0",
        "cross-env": "^4.0.0",
        "documentation": "^4.0.0-beta.18",
        "exif-reader": "^1.0.2",
        "icc": "^1.0.0",
        "mocha": "^3.2.0",
        "nyc": "^10.2.0",
        "rimraf": "^2.5.4",
        "semistandard": "^10.0.0",
        "unzip": "^0.1.11"
    },
    "directories": {},
    "dist": {
        "shasum": "484cd2a70c900370948dcc43e165f78306bff48a",
        "tarball": "https://registry.npmjs.org/sharp/-/sharp-0.17.3.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "fcf853712cb0ac96bb6af1a886469d290485912c",
    "gypfile": true,
    "homepage": "https://github.com/lovell/sharp",
    "keywords": [
        "jpeg",
        "png",
        "webp",
        "tiff",
        "gif",
        "svg",
        "dzi",
        "image",
        "resize",
        "thumbnail",
        "crop",
        "libvips",
        "vips"
    ],
    "license": "Apache-2.0",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "lovell",
            "email": "npm@lovell.info"
        }
    ],
    "name": "sharp",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/lovell/sharp.git"
    },
    "scripts": {
        "clean": "rm -rf node_modules/ build/ vendor/ coverage/ test/fixtures/output.*",
        "docs": "for m in constructor input resize composite operation colour channel output utility; do documentation build --shallow --format=md lib/$m.js >docs/api-$m.md; done",
        "install": "node-gyp rebuild",
        "test": "semistandard && cc && cross-env VIPS_WARNING=0 nyc --reporter=lcov --branches=99 mocha --slow=5000 --timeout=60000 ./test/unit/*.js",
        "test-leak": "./test/leak/leak.sh",
        "test-packaging": "./packaging/test-linux-x64.sh"
    },
    "semistandard": {
        "env": [
            "mocha"
        ]
    },
    "version": "0.17.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
