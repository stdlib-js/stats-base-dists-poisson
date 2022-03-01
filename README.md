<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Poisson

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Poisson distribution.

<section class="installation">

## Installation

```bash
npm install @stdlib/stats-base-dists-poisson
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].

</section>

<section class="usage">

## Usage

```javascript
var poisson = require( '@stdlib/stats-base-dists-poisson' );
```

#### poisson

Poisson distribution.

```javascript
var dist = poisson;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pmf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, lambda )`][@stdlib/stats/base/dists/poisson/cdf]</span><span class="delimiter">: </span><span class="description">Poisson distribution cumulative distribution function.</span>
-   <span class="signature">[`logpmf( x, lambda )`][@stdlib/stats/base/dists/poisson/logpmf]</span><span class="delimiter">: </span><span class="description">evaluate the natural logarithm of the probability mass function (PMF) for a Poisson distribution.</span>
-   <span class="signature">[`mgf( t, lambda )`][@stdlib/stats/base/dists/poisson/mgf]</span><span class="delimiter">: </span><span class="description">Poisson distribution moment-generating function (MGF).</span>
-   <span class="signature">[`pmf( x, lambda )`][@stdlib/stats/base/dists/poisson/pmf]</span><span class="delimiter">: </span><span class="description">Poisson distribution probability mass function (PMF).</span>
-   <span class="signature">[`quantile( p, lambda )`][@stdlib/stats/base/dists/poisson/quantile]</span><span class="delimiter">: </span><span class="description">Poisson distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`kurtosis( lambda )`][@stdlib/stats/base/dists/poisson/kurtosis]</span><span class="delimiter">: </span><span class="description">Poisson distribution excess kurtosis.</span>
-   <span class="signature">[`mean( lambda )`][@stdlib/stats/base/dists/poisson/mean]</span><span class="delimiter">: </span><span class="description">Poisson distribution expected value.</span>
-   <span class="signature">[`median( lambda )`][@stdlib/stats/base/dists/poisson/median]</span><span class="delimiter">: </span><span class="description">Poisson distribution median.</span>
-   <span class="signature">[`mode( lambda )`][@stdlib/stats/base/dists/poisson/mode]</span><span class="delimiter">: </span><span class="description">Poisson distribution mode.</span>
-   <span class="signature">[`skewness( lambda )`][@stdlib/stats/base/dists/poisson/skewness]</span><span class="delimiter">: </span><span class="description">Poisson distribution skewness.</span>
-   <span class="signature">[`stdev( lambda )`][@stdlib/stats/base/dists/poisson/stdev]</span><span class="delimiter">: </span><span class="description">Poisson distribution standard deviation.</span>
-   <span class="signature">[`variance( lambda )`][@stdlib/stats/base/dists/poisson/variance]</span><span class="delimiter">: </span><span class="description">Poisson distribution variance.</span>

</div>

<!-- </toc> -->

The namespace contains a constructor function for creating a [Poisson][poisson-distribution] distribution object.

<!-- <toc pattern="*ctor*"> -->

<div class="namespace-toc">

-   <span class="signature">[`Poisson( [lambda] )`][@stdlib/stats/base/dists/poisson/ctor]</span><span class="delimiter">: </span><span class="description">Poisson distribution constructor.</span>

</div>

<!-- </toc> -->

```javascript
var Poisson = require( '@stdlib/stats-base-dists-poisson' ).Poisson;

var dist = new Poisson( 2.0 );

var y = dist.pmf( 3.0 );
// returns ~0.18

y = dist.pmf( 2.3 );
// returns 0.0
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils-keys' );
var poisson = require( '@stdlib/stats-base-dists-poisson' );

console.log( objectKeys( poisson ) );
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-poisson.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-poisson

[test-image]: https://github.com/stdlib-js/stats-base-dists-poisson/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/stats-base-dists-poisson/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-poisson/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-poisson?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-poisson.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-poisson/main

-->

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/stats-base-dists-poisson/tree/deno
[umd-url]: https://github.com/stdlib-js/stats-base-dists-poisson/tree/umd
[esm-url]: https://github.com/stdlib-js/stats-base-dists-poisson/tree/esm

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-poisson/main/LICENSE

[poisson-distribution]: https://en.wikipedia.org/wiki/Poisson_distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/poisson/ctor]: https://github.com/stdlib-js/stats-base-dists-poisson-ctor

[@stdlib/stats/base/dists/poisson/kurtosis]: https://github.com/stdlib-js/stats-base-dists-poisson-kurtosis

[@stdlib/stats/base/dists/poisson/mean]: https://github.com/stdlib-js/stats-base-dists-poisson-mean

[@stdlib/stats/base/dists/poisson/median]: https://github.com/stdlib-js/stats-base-dists-poisson-median

[@stdlib/stats/base/dists/poisson/mode]: https://github.com/stdlib-js/stats-base-dists-poisson-mode

[@stdlib/stats/base/dists/poisson/skewness]: https://github.com/stdlib-js/stats-base-dists-poisson-skewness

[@stdlib/stats/base/dists/poisson/stdev]: https://github.com/stdlib-js/stats-base-dists-poisson-stdev

[@stdlib/stats/base/dists/poisson/variance]: https://github.com/stdlib-js/stats-base-dists-poisson-variance

[@stdlib/stats/base/dists/poisson/cdf]: https://github.com/stdlib-js/stats-base-dists-poisson-cdf

[@stdlib/stats/base/dists/poisson/logpmf]: https://github.com/stdlib-js/stats-base-dists-poisson-logpmf

[@stdlib/stats/base/dists/poisson/mgf]: https://github.com/stdlib-js/stats-base-dists-poisson-mgf

[@stdlib/stats/base/dists/poisson/pmf]: https://github.com/stdlib-js/stats-base-dists-poisson-pmf

[@stdlib/stats/base/dists/poisson/quantile]: https://github.com/stdlib-js/stats-base-dists-poisson-quantile

<!-- </toc-links> -->

</section>

<!-- /.links -->
