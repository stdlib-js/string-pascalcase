<!--

@license Apache-2.0

Copyright (c) 2021 The Stdlib Authors.

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

# pascalcase

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Convert a string to Pascal case.

<!-- Package usage documentation. -->



<section class="usage">

## Usage

```javascript
import pascalcase from 'https://cdn.jsdelivr.net/gh/stdlib-js/string-pascalcase@esm/index.mjs';
```

#### pascalcase( str )

Converts a string to Pascal case.

```javascript
var out = pascalcase( 'foo bar' );
// returns 'FooBar'

out = pascalcase( 'IS_MOBILE' );
// returns 'IsMobile'

out = pascalcase( 'Hello World!' );
// returns 'HelloWorld'

out = pascalcase( '--foo-bar--' );
// returns 'FooBar'

out = pascalcase( 'fooBar' );
// returns 'FooBar'
```

</section>

<!-- /.usage -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import pascalcase from 'https://cdn.jsdelivr.net/gh/stdlib-js/string-pascalcase@esm/index.mjs';

var str = 'Hello World!';
var out = pascalcase( str );
// returns 'HelloWorld'

str = 'HELLO WORLD!';
out = pascalcase( str );
// returns 'HelloWorld'

str = 'To be, or not to be: that is the question.';
out = pascalcase( str );
// returns 'ToBeOrNotToBeThatIsTheQuestion'

</script>
</body>
</html>
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

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/string-pascalcase.svg
[npm-url]: https://npmjs.org/package/@stdlib/string-pascalcase

[test-image]: https://github.com/stdlib-js/string-pascalcase/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/string-pascalcase/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/string-pascalcase/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/string-pascalcase?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/string-pascalcase.svg
[dependencies-url]: https://david-dm.org/stdlib-js/string-pascalcase/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[cli-section]: https://github.com/stdlib-js/string-pascalcase#cli
[cli-url]: https://github.com/stdlib-js/string-pascalcase/tree/cli
[@stdlib/string-pascalcase]: https://github.com/stdlib-js/string-pascalcase/tree/main

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/string-pascalcase/tree/deno
[umd-url]: https://github.com/stdlib-js/string-pascalcase/tree/umd
[esm-url]: https://github.com/stdlib-js/string-pascalcase/tree/esm
[branches-url]: https://github.com/stdlib-js/string-pascalcase/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/string-pascalcase/main/LICENSE

[standard-streams]: https://en.wikipedia.org/wiki/Standard_streams

[mdn-regexp]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions

<!-- <related-links> -->

<!-- </related-links> -->

</section>

<!-- /.links -->
