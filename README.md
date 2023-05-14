# OMB Font Theme only Fork
This is an extremely gutted version of the original [Oh My Bash](https://github.com/ohmybash/oh-my-bash) containing nothing but necessary code for the rendering of the default *font* prompt theme. No extra aliases (in OMB even if you opt out of aliases/plugins/completions you still get some random aliases added), no update checking, no module bloat. Only the looks.

## Usage
- Clone the repo to `~/.my-omb-fancy-prompt`.
- Source the `setup-prompt.inc.sh` in your bashrc.
```bash
echo "source ~/.my-omb-fancy-prompt/setup-prompt.inc.sh" >> ~/.bashrc
```
- Reload shell & profit.

## Original License

Oh My Bash is derived from [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh).
Oh My Bash is released under the [MIT license](LICENSE.md).
