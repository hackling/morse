## Installation

Create a file called `.semaphore.token` in your home directory that
contains your Semaphore API key.

Place morse inside your `~/bin` directory

Alternatively, you can manage this script with [fresh](http://github.com/freshshell):

```
$ fresh https://github.com/hackling/morse/blob/master/bin/morse
```

## Usage

Navigate to your project directory and run

```
$ morse
```

To have morse run the failed test, use

```
$ morse --run
```

**Must be executed within a git repository.**
