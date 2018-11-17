# BeautifyRust

A binding for Sublime Text to the [Rustfmt](https://github.com/rust-lang-nursery/rustfmt).


### Requirements

1. Clone and build the [rustfmt](https://github.com/rust-lang-nursery/rustfmt)
2. Clone from this repo [https://github.com/pspace/BeautifyRust](https://github.com/pspace/BeautifyRust) into `~/.config/sublime-text-3/Packages/BeautifyRust/` (or whatever is neede on your platform)
3. If an error is encountered while processing the file or can not find `rustfmt` in path, following message `Beautify rust: can not find rustfmt in path.` is displayed. Open menu in your `Preferences -> Package settings -> BeautifyRust -> Settings - User`, and edit the settings file using below as a template:

```
{
  "run_on_save": false,
  "show_errors": true,
  "rustfmt": "/Users/user/.cargo/bin/rustfmt"

  // Optionally, you may specify an array of arguments to pass to rustfmt
  // For example, if you have a system wide rustfmt configuration file
  // "args": [
  //     "--config-path=/Users/user/.rust/"
  // ]
}
```

Contact
=======

https://github.com/pspace/BeautifyRust
