# Hash-The-File

```
$ python main.py --help
Usage: python main.py [--<method>] filenames
Available hash methods
    --md5
    --sha1
    --sha224
    --sha256
    --sha384
    --sha512
    --blake2b
    --blake2s
    --sha3_224
    --sha3_256
    --sha3_384
    --sha3_512
    --shake_128
    --shake_256
```

```
$ python main.py --md5 test.txt
bbd29f982c1c23021d55f6aa8854cac6  test.txt
$ python main.py --sha256 test.txt
cdf2262e50bc5c8a22240a732eb94ec3ce5474469aed89301fb248ab21bc9eee  test.txt
```
