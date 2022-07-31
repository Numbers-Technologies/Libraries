# Add a new library to this repository

- Create new library with prefix `lib` 
- Add documentation for lib to this repository `docs/libraryname/README.md`.
- You should check this library very well.

#### Compile library
```bash
gcc -shared -o libraryname.so -fPIC library.c
```

Output file must be like as `libraryname.so`.
