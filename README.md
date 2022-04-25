## @ngageoint/geopackage-xyz-server-js &mdash; Turn your GeoPackage into an XYZ tile server

This utility demonstrates how to run an XYZ Tile Server using Node/Express and GeoPackage JS.

### Usage

#### Run server locally

```sh
export GeoPackageDir='directory containing GeoPackage files'
node index.js
```

#### Browser request
```browser
http://localhost:4234/:geoPackageFileName/:tableName/{z}/{x}/{y}.png
```


#### GeoPackage JS Library ####

The [GeoPackage Libraries](http://ngageoint.github.io/GeoPackage/) were developed at the [National Geospatial-Intelligence Agency (NGA)](http://www.nga.mil/) in collaboration with [BIT Systems](http://www.bit-sys.com/). The government has "unlimited rights" and is releasing this software to increase the impact of government investments by providing developers with the opportunity to take things in new directions. The software use, modification, and distribution rights are stipulated within the [MIT license](http://choosealicense.com/licenses/mit/).

### Pull Requests ###
If you'd like to contribute to this project, please make a pull request. We'll review the pull request and discuss the changes. All pull request contributions to this project will be released under the MIT license.

Software source code previously released under an open source license and then modified by NGA staff is considered a "joint work" (see 17 USC § 101); it is partially copyrighted, partially public domain, and as a whole is protected by the copyrights of the non-government authors and must be released according to the terms of the original open source license.


### Changelog


##### 4.1.0
- Update to GeoPackage JS 4.1.0.
