# HelloPascal

First Pascal program, kept here so I have somewhere to put the rest of the
Pascal exercises later.

```pascal
program HelloWorld;

begin
  writeln('Hello, World!');
end.
```

## Compile and run

You need Free Pascal:

- Debian/Ubuntu: `sudo apt install fp-compiler`
- Arch: `sudo pacman -S fpc`
- macOS: `brew install fpc`
- Windows: https://www.freepascal.org/download.var

Then:

    fpc HelloWorld.pas
    ./HelloWorld

On Windows it is `HelloWorld.exe`.
