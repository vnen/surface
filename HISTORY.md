0.7.8 / 2015-02-9
==================
- [ADD] add Access-Control headers for crossing domain automatically.

0.7.7 / 2015-02-03
==================
- [ENHANCE] new code structure (use koa-ovenware for auto loading).
- [ADD] prefix could be a RegExp.
- [FIX] default format setting will really available by default (when there's no Accept head).
- [FIX] some bugs.

0.7.6 / 2014-12-10
==================
- [FIX] custom HTTP code

0.7.5 / 2014-10-16
==================
- [FIX] del route - `DELETE`
- [FIX] about https://github.com/koajs/koa/pull/353

0.7.4 / 2014-10-02
==================

- [REMOVE] No longer support `ctx.body = ''` => 204 No Content
  - use `ctx.body = null` instead
- [REMOVE] API - this.statusMessage
  - use `ctx.res.statusCode` and `ctx.res.statusMessage` (node native API) instead

0.7.3 / 2014-09-25
==================

- [ADD] default prefixPattern = new RegExp(prefix), if prefix is string.

0.7.2 / 2014-09-25
==================

- [ADD] API - this.statusMessage

0.7.1 / 2014-09-24
==================

- [ADD] prefix for all routes
- [FIX] #1