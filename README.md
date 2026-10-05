<!-- tyhp-readme:start -->
# tyhpdef/illuminate-cache

Tyhp type definitions for `illuminate/cache` `13.32.0`.

```bash
composer require --dev tyhpdef/illuminate-cache:13.32.0
```

This is a metapackage. Composer also installs `tyhpdef/illuminate-cache-impl` (type files).
Require **this** name, not `tyhpdef/illuminate-cache-impl`.

See https://tyhplang.com.

## Maintain `illuminate/cache`? Ship the types yourself

If you are a Packagist maintainer of `illuminate/cache`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/illuminate-cache-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `illuminate/cache` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/illuminate-cache": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `illuminate/cache` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `illuminate/cache` with a real constraint,
   `"replace": { "tyhpdef/illuminate-cache": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `illuminate/cache` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/illuminate-cache` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
