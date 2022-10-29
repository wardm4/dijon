<p align="center">
  <img height="200" src="https://imgur.com/a/rhzDO5U.png">
</p>

### About

`dijon` is a fork of `dijo`.

`dijo` is a curses-based habit tracker. It is curses-based, it runs in
your terminal. Check out the original `dijo` to see all the base features. All features of `dijo` still exist in `dijon`.

When I found `dijo`, it was borderline perfect for what I wanted.

But I wanted just a handful of extra features.

### Features new to dijon

As of now, these are all planned. None have been implemented.

 - Track everything, not just habits: sleep, weight, caffeine intake, etc.
 - Weekly habits.

 Look, dijo "let you track weekly habits" but in a strange way. 

 Say I wanted to go to the gym 4 times a week.

Dijo let you increment each time, so you'd get a 1 on Monday a 1 on Wednesday, etc. But there was nothing internal to tell you if you achieved that goal. Dijon fixes that.

### Install via cargo

```shell
# dijon requires rustc >= v1.42
$ rustup update
$ git clone https://github.com/wardm4/dijon.git
$ cd dijon
$ cargo install dijon
```
If you aren't familiar with `cargo` or Rust, read the [complete
installation](https://github.com/NerdyPepper/dijo/wiki/Install)
guide.

#### Others

Sorry, I have not packaged dijon for any other package managers like snap yet.

### Usage

`dijo` has a [detailed
wiki](https://github.com/NerdyPepper/dijo/wiki/), here are
some good places to start out:

 - [Getting started](https://github.com/NerdyPepper/dijo/wiki/Getting-Started)
 - [Automatically tracking habits](https://github.com/NerdyPepper/dijo/wiki/Auto-Habits)
 - [Command reference](https://github.com/NerdyPepper/dijo/wiki/Commands)

### Gallery

Day mode, shows days of the current month:

![day.png](https://u.peppe.rs/qI.png)

Week mode, shows weekly summary for the weeks of the month:

![weekly.png](https://u.peppe.rs/HZ.png)

[![Awesome Humane Tech](https://raw.githubusercontent.com/humanetech-community/awesome-humane-tech/main/humane-tech-badge.svg?sanitize=true)](https://github.com/humanetech-community/awesome-humane-tech)
