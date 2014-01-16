bash_builtin_skeleton
=====================

"hello world" skeleton for bash custom builtin-commands in C/C++

### Test output

    $ ./test 

    testing builtin 'hello'
    (..1000 calls..)

    real	0m0.022s
    user	0m0.016s
    sys	0m0.004s



    testing standalone 'hello'
    (..1000 calls..)

    real	0m1.525s
    user	0m0.092s
    sys	0m0.244s

### What is it

Bash builtins enable you to extend bash with fast C/C++ commands, instead of relying on external programs only (=slow).
By doing so, you can use bash as a scripting engine, similar to how C/C++ applications use lua for flexible scripting.

### Applications 

Well you name it, games, utilities (heavy crunching), etc.

### Requirements

* You need the bash-builtin header files (on debianish distros: `apt-get install bash-builtins`)

