# Teto

A minimalist package manager written in `sh`.

## Features
- Install packages from `pkgs/build/`
- Modular design: package operations are separated into `modules/`

## Usage
teto -S <pkg>    # install a package

teto -R <pkg>    # remove a package

teto -U <pkg>    # update a package

## Requirements
Linux

POSIX-compatible shell

sed

C99 compiler

make

automake

autoconf

libtool

curl

## How to install
cd /

sudo git clone https://github.com/Vexirio/teto

ln -s /teto/teto /bin/teto
