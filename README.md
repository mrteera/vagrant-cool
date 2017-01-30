# Vagrant Box for Cool

Set up the development environment for [Cool: The Classroom Object-Oriented Language](http://theory.stanford.edu/~aiken/software/cool/cool.html) using [Vagrant](https://www.vagrantup.com/).

## Usage

This is a fairly simple project to get up and running.

1. Clone the project
2. Run `vagrant up`
3. Open `cool` folders and start hacking
4. Connect to the virtual machine and test using `vagrant ssh`

## Test
1. After `vagrant ssh` `cd /home/vagrant/cool/examples`
2. `coolc hello_world.cl`
3. `spim hello_world.s`

The result should be similar to this:

```
SPIM Version 6.5 of January 4, 2003
Copyright 1990-2003 by James R. Larus (larus@cs.wisc.edu).
All Rights Reserved.
See the file README for a full copyright notice.
Loaded: /usr/class/cs143/cool/lib/trap.handler
Hello, World.
COOL program successfully executed
Stats -- #instructions : 152
         #reads : 27  #writes 22  #branches 28  #other 75
```

## Reference

- [Stanford Compilers Course on Coursera](https://www.coursera.org/course/compilers)

## License

vagrant-cool is available under the MIT license. See the LICENSE file for more info.
