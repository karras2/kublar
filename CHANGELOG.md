# 26.08.2021
- Fixed a bug that sliced up names
- To fix it for yourself if you're olding a older version of the template, search up
- `z.name = get.next();`
- and replace the thing around it with this, i hope you understand
```
if (type & 0x04) { // has a nameplate
  z.name = get.next();
  z.score = get.next();
}
```