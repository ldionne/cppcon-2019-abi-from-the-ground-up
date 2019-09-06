## The C++ ABI for dummies

This repository contains my [reveal.js][]-based presentation on the C++ ABI
for [CppCon 2019][].

## Usage
Go to https://ldionne.com/abi-for-dummies or open `index.html` with your browser.
A PDF version of the slides is in `slides.pdf`.

## Running a local server
```sh
cd reveal
npm install # you can make sure that Python < 3 is used with `--python=python2.XYZ`
grunt serve --root=..
```

Then visit http://localhost:8000.

<!-- Links -->
[CppCon 2019]: https://cppcon.org
[reveal.js]: https://github.com/hakimel/reveal.js
