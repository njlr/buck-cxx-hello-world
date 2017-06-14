# buck-cxx-hello-world

This is a "Hello World" example of a C++ project built using [Buck](https://buckbuild.com/).

Before you get started, you will need a C++ compiler and Buck installed on your system. Further documentation can be found [on the Buck website](https://buckbuild.com/setup/getting_started.html).

To build the project:

```bash=
buck build :hello-world
```

The binary will be placed at `buck-out/gen/hello-world`.

To run the binary via Buck:

```bash=
buck run :hello-world
```

There are many examples of C/C++ `BUCK` files in [the Buckaroo cookbook](https://github.com/LoopPerfect/buckaroo-recipes).
