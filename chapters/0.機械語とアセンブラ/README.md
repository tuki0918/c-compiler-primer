

[機械語とアセンブラ / Cとそれに対応するアセンブラ / 簡単な例](https://www.sigbus.info/compilerbook#%E7%B0%A1%E5%8D%98%E3%81%AA%E4%BE%8B)

```
docker run --rm -it -v $PWD:/work -w /work compilerbook
```

example

```
$ cc -o test1 test1.c
$ ./test1
$ echo $?
42
```

example

```
$ cc -o test2 test2.s
$ ./test2
$ echo $?
42
```
