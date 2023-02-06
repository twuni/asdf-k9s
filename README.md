# asdf-k9s

[k9s][k9s] plugin for the [asdf universal version manager][asdf].

## Installing

```sh
asdf plugin-add k9s https://github.com/twuni/asdf-k9s.git
```

Then, manage k9s versions just as you would any other asdf plugin.

For example:

```sh
# Install the latest version of k9s
asdf install k9s latest

# Set your default k9s version to the current latest version
asdf global k9s latest
```

[asdf]: https://github.com/asdf-vm/asdf
[k9s]: https://k9scli.io/
