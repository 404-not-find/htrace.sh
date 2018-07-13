<h1 align="left">htrace.sh</h1>

<p align="left">
  <a href="https://travis-ci.org/trimstray/htrace.sh">
    <img src="https://travis-ci.org/trimstray/htrace.sh.svg?branch=master"
        alt="Travis-CI">
  </a>
</p>

<h5 align="left">Simple shell script to debugging http/https traffic tracing.</h5>

<br>

<p align="center">
    <img src="https://github.com/trimstray/htrace.sh/blob/master/doc/img/htrace.sh_preview.png"
        alt="Master">
</p>

<br>

<div align="center">
  <sub>Created by
  <a href="https://twitter.com/trimstray">trimstray</a> and
  <a href="https://github.com/trimstray/htrace.sh/graphs/contributors">
    contributors
  </a>
</div>

<br>

## Description

It is useful for:

- redirects analysis, eg. to eliminate redirect loops
- check properly web server/reverse proxy domain configuration

## How To Use

It's simple:

```bash
# Clone this repository
git clone https://github.com/trimstray/htrace.sh

# Go into the repository
cd htrace.sh

# Install
./setup.sh install

# Run the app
htrace.sh --domain https://google.com
```

> * symlink to `bin/htrace.sh` is placed in `/usr/local/bin`
> * man page is placed in `/usr/local/man/man8`

## Parameters

Provides the following options:

```bash
  Usage:
    htrace.sh <option|long-option>

  Examples:
    htrace.sh --domain https://google.com

  Options:
        --help                        show this message
        --domain <domain_name>        set domain name
```

## Contributing

See **[this](CONTRIBUTING.md)**.

## License

GPLv3 : <http://www.gnu.org/licenses/>

**Free software, Yeah!**
