Init Dotfiles
=============

Get Running in 5 Minutes
------------------------

```bash
    curl -fsSLO https://raw.githubusercontent.com/cdxcode/init-dotfiles/master/bootstrap

    chmod +x ./bootstrap

    ./bootstrap
```

Usage
--------------------

- `test` - Test mode. Nothing will actually be done. Best if you are wary
    about the whole thing. Default: No.

- `verbose-config` - The Dotbot configuration will have every option
    explicitly set. Default: No.

- `dump-config` - The configuration will be sent to `stdout`, perfect for
    redirecting into a file. Default: No.

- `preview` - Commands will be printed to the console before being executed.
    There won't be newlines between them, but you can see what they are. Default:
    Yes.

- `colors` - Colorize output. Default: No.

Every command line option can have `no-` prepended to turn off the option.

For example:

```bash
    ./init_dotfiles.sh verbose-config no-preview
```

Will enable the `verbose-config` option and disable the `preview` option.

[cdxcode]: https://github.com/cdxcode/cdxcode
