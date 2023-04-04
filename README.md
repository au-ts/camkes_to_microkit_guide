This repository holds the guide for transitioning from CAmkES to the seL4 Core Platform. Written by Jade Zhou.

Any feedback is appreciated.

### Producing a PDF

To build a PDF version of the guide you can use Pandoc:
```sh
pandoc guide.md -f gfm -o guide.pdf
```

If you don't have Pandoc installed you can install it using apt:
```sh
sudo apt install pandoc
```

Or if you are on macOS with Homebrew:
```sh
brew install pandoc
```

If these methods do not work for you, the [Pandoc instructions](https://pandoc.org/installing.html) might help.
