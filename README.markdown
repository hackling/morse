**Must be executed within a git repository.**

## Installation

You must have a file called `.semaphore.token` in your home direction.
It will contain only one line, and it will be your semaphore API key.

Place morse inside your `~/bin` directory

Alternatively, you can manage this script with [fresh](http://github.com/freshshell):

```
$ fresh https://github.com/hackling/morse/blob/master/bin/morse
```

## Usage

Navigate to your branch and run

```
$ morse
```

To have morse run the failed test, use

```
$ morse --run
```
