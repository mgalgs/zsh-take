zsh plugin that adds a `take` command to your zsh to make creating
directories (or download/cloning remote assets) and changing into them a
single step.

It may seem small, but micro-optimizations to your workflow add up! And
after you've gotten used to `take`, using the `mkdir; cd` pattern will feel
archaic and inefficient.

## Examples

### Create directory and change into it

    take my-cool-new-dir

Is equivalent to:

    mkdir my-cool-new-dir
    cd my-cool-new-dir

### Clone repo and cd into it

    take https://github.com/mgalgs/zsh-take.git

Is equivalent to:

    git clone https://github.com/mgalgs/zsh-take.git
    cd zsh-take

## Installation

Add this repo with your plugin manager (which should find the
zsh-take.plugin.zsh file and source it automatically), or just download the
source and source it yourself.
