# vxcc definition language
DSL for definining vxcc IR operations and patterns

Currently has to be cloned and built in the root of the [lambda mountain compiler](https://github.com/andrew-johnson-4/lambda-mountain).

Building:
```
lm --c -o vxdef.c vxdef/index-index.lsts
cc vxdef.c -o vxdef.exe
```

Depends on https://github.com/andrew-johnson-4/lambda-mountain/pull/1250 to merged

Currently broken and WIP

For examples see test.vxdef and ops.vxdef
