# lfs-test

Produced by something like:
```
ls > foo.txt
ls > bar.txt
git lfs install
head -c 1M /dev/urandom > cat.bin
head -c 1M /dev/urandom > dog.bin
git lfs track '*.bin'
git commit -m "Add files"
```
