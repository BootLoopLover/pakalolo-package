```
echo >> feeds.conf.default
echo 'src-git pakalolopackage https://github.com/BootLoopLover/pakalolo-package.git' >> feeds.conf.default
```

```
./scripts/feeds update -a
./scripts/feeds install -a
```


