matreix:
include:
- language: c
sudo: false # only for faster builds
compiler:
- clang
- gcc
script:
- gcc -o test tg.c
- ./test
