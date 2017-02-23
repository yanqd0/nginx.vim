# nginx.vim

A plugin for nginx copied from [nginx/contrib/vim].

## Introduction

The code is originally release by [Evan Miller](http://www.vim.org/account/profile.php?user_id=12345)
as a vim plugin [nginx.vim](http://www.vim.org/scripts/script.php?script_id=1886)
at [vim.org] in 2005.
The last version is 0.3.3 there, updated in the January of 2013.

In the December of 2013, [Evan Miller](mailto:emmiller@gmail.com) submit the code into the [nginx] project.
Since then, there are 5 other commits.

This repository is created in 2017,
which makes it convenient to install with vim plugin managers, like Vundle or Pathogen.

The source code of nginx is stored with [Mercurial] in <http://hg.nginx.org/nginx/> .
But there is an official read-only mirror [nginx/nginx] in GitHub, where this repository copied from.

[nginx/contrib/vim]:https://github.com/nginx/nginx/tree/master/contrib/vim
[vim.org]:http://www.vim.org/
[nginx]:http://nginx.org/
[Mercurial]:https://www.mercurial-scm.org/
[nginx/nginx]:https://github.com/nginx/nginx

## Usage

If you use [Vundle.vim], add this to an approperiate place of your vimrc.

```vim
Plugin 'yanqd0/nginx.vim'
```

After that, install it with `:PluginInstall` in Vim.

[Vundle.vim]: https://github.com/VundleVim/Vundle.vim

## Other ways

In fact, there are other ways to use it.

```vim
Plugin 'nginx.vim'
```

It refers to the plugin mirror [vim-scripts/nginx.vim],
which is out of date since 2013.

This repository will be updated irregularly.
If you want to update with [nginx/nginx],
notify [me](mailto:yanqd0@outlook.com) or fork it.

Besides, you can use [Vundle.vim] like this.

```vim
Plugin 'nginx/nginx', {'rtp': 'contrib/vim'}
```

Yes, that means you don't mind to update an entire nginx project in your `~/.vim`.

[vim-scripts/nginx.vim]:https://github.com/vim-scripts/nginx.vim

## Change log since 0.3.3

The change log below is from [nginx/nginx].

| Title                                                              | Author                                   | Date       |
| -----                                                              | -----                                    | ----       |
| Contrib: vim syntax, listen option and SSL/Mail protocol keywords. | [othree](mailto:othree@gmail.com)        | 2017-02-22 |
| Contrib: added 'commentstring' for vim-commentary support.         | [Armin Grodon](mailto:me@armingrodon.de) | 2016-12-13 |
| Fixed spelling.                                                    | [Josh Soref](mailto:timeless@gmail.com)  | 2016-04-07 |
| Removed the prototype mysql module.                                | [Ruslan Ermilov](mailto:ru@nginx.com)    | 2016-03-31 |
| Contrib: add more directives to vim syntax.                        | [Peter Wu](peter@lekensteyn.nl)          | 2014-10-22 |
| Contrib: add vim scripts to contrib/ directory.                    | [Evan Miller](mailto:emmiller@gmail.com) | 2013-12-04 |
