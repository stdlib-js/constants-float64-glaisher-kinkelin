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

# Glaisher-Kinkelin Constant

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> [Glaisher-Kinkelin][glaisher-constant] constant.

<section class="intro">

[Glaisher-Kinkelin][glaisher-constant] constant is defined as

<!-- <equation class="equation" label="eq:glaisher_kinkelin_constant" align="center" raw="A = \lim_{n\to\infty} \frac{K(n + 1)}{n^{n^2/2 + n/2 + 1/12}e^{-n^2/4}}" alt="Glaisher-Kinkelin constant"> -->

<div class="equation" align="center" data-raw-text="A = \lim_{n\to\infty} \frac{K(n + 1)}{n^{n^2/2 + n/2 + 1/12}e^{-n^2/4}}" data-equation="eq:glaisher_kinkelin_constant">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@5d87cc7cb2c58aeb732872f89562d2c89571cc8a/lib/node_modules/@stdlib/constants/float64/glaisher-kinkelin/docs/img/equation_glaisher_kinkelin_constant.svg" alt="Glaisher-Kinkelin constant">
    <br>
</div>

<!-- </equation> -->

where

<!-- <equation class="equation" label="eq:k_function" align="center" raw="K(n) = \prod_{k=1}^{n-1} k^k" alt="K-function"> -->

<div class="equation" align="center" data-raw-text="K(n) = \prod_{k=1}^{n-1} k^k" data-equation="eq:k_function">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@5d87cc7cb2c58aeb732872f89562d2c89571cc8a/lib/node_modules/@stdlib/constants/float64/glaisher-kinkelin/docs/img/equation_k_function.svg" alt="K-function">
    <br>
</div>

<!-- </equation> -->

is the [K-function][k-function].

</section>

<!-- /.intro -->



<section class="usage">

## Usage

```javascript
import A from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-glaisher-kinkelin@deno/mod.js';
```

#### A

The [Glaisher-Kinkelin][glaisher-constant] constant.

```javascript
var bool = ( A === 1.2824271291006226 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better example -->

<!-- eslint no-undef: "error" -->

```javascript
import A from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-glaisher-kinkelin@deno/mod.js';

console.log( 'Glaisher\'s constant: %d', A );
// => 'Glaisher\'s constant: 1.2824271291006226'
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

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

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

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-float64-glaisher-kinkelin.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-float64-glaisher-kinkelin

[test-image]: https://github.com/stdlib-js/constants-float64-glaisher-kinkelin/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/constants-float64-glaisher-kinkelin/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-float64-glaisher-kinkelin/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-float64-glaisher-kinkelin?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-float64-glaisher-kinkelin.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-float64-glaisher-kinkelin/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-float64-glaisher-kinkelin/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-float64-glaisher-kinkelin/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-float64-glaisher-kinkelin/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-float64-glaisher-kinkelin/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-float64-glaisher-kinkelin/main/LICENSE

[glaisher-constant]: https://en.wikipedia.org/wiki/Glaisher%E2%80%93Kinkelin_constant

[k-function]: https://en.wikipedia.org/wiki/K-function

</section>

<!-- /.links -->
