[![Build status on Travis CI][travis-master-badge]][travis-link]
[![Newest release on crates.io][crate-version-badge]][crate-link]
[![Number of downloads on crates.io][crate-download-badge]][crate-link]
[![Project license][crate-license-badge]](LICENSE)

[Documentation][docs]

[crate-link]: https://crates.io/crates/ffsend-api
[crate-download-badge]: https://img.shields.io/crates/d/ffsend-api.svg
[crate-version-badge]: https://img.shields.io/crates/v/ffsend-api.svg
[crate-license-badge]: https://img.shields.io/crates/l/ffsend-api.svg
[travis-master-badge]: https://travis-ci.org/timvisee/ffsend-api.svg?branch=master
[travis-link]: https://travis-ci.org/timvisee/ffsend-api
[docs]: https://docs.rs/ffsend-api

# ffsend-api [WIP]
> A fully featured [Firefox Send][send] API client written in Rust.

This repository is still being worked on,
and this documentation is not finished yet.

Here is a demo of the API implementation as used in [ffsend][ffsend]:  
[![ffsend-api implementation demo from ffsend][ffsend-usage-demo-svg]][ffsend-usage-demo-asciinema]
_Implementation demo from [ffsend][ffsend] not visible here?
View it on [asciinema][ffsend-usage-demo-asciinema]._

Please note that the provided API interface may change drastically each version
until a stable `1.0` version is released. Therefore, if you're using any alpha
version of this crate in your own project, it's recommended to select a fixed
version number to prevent future build failures due to a newly released but
incompatible version. 

Please see the client project here: [ffsend][ffsend]

## License
This project is released under the MIT license.
Check out the [LICENSE](LICENSE) file for more information.

[ffsend]: https://github.com/timvisee/ffsend
[ffsend-usage-demo-asciinema]: https://asciinema.org/a/182225
[ffsend-usage-demo-svg]: https://cdn.rawgit.com/timvisee/ffsend/6e8ef55b/res/demo.svg
[send]: https://send.firefox.com/
