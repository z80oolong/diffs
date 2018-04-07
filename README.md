# diffs -- tmux, mutt 等の各種ソフトウェアの差分ファイル群

## 概要

本リポジトリは、端末多重化ソフトウェアである [tmux][TMUX] と軽量メールソフトである [mutt][MUTT] 等の各種ソフトウェアについて各種修正を行う為の差分ファイルを集めたリポジトリです。

これらの差分ファイルは、当方の [GithubGist][GIST] において投稿していた差分ファイルを [Github][GITH] のリポジトリにおいて再掲するものです。

## その他詳細について

以下に掲げる、本リポジトリにおける各差分ファイルの詳細に関しては、下記の [GithubGist][GIST] の投稿記事を御覧下さい。

- ```tmux/tmux-*-fix.diff``` … [tmux 2.3 以降において East Asian Ambiguous Character を全角文字の幅で表示する][GST1]
- ```mutt/mutt-*-fix.diff``` … [mutt 1.9.0 以降において East Asian Ambiguous Character を全角文字の幅で表示する ][GST2]
- ```dropbear/dropbear-*.diff``` … [Debian noroot 環境において dropbear の動作に不具合が生じる問題を修正するための差分ファイル ][GST3]
- ```libandroid-shmem/libandroid-shmem-termux-0.2_1-fix.diff``` … [Termux に移植された libandroid-shmem.so を Debian noroot 環境に再移植するための差分ファイル][GST4]

<!-- 外部リンク一覧 -->


[TMUX]:https://tmux.github.io/
[MUTT]:https://www.mutt.org/
[GITH]:https://github.com/z80oolong/
[GIST]:https://gist.github.com/z80oolong/
[GST1]:https://gist.github.com/z80oolong/e65baf0d590f62fab8f4f7c358cbcc34
[GST2]:https://gist.github.com/z80oolong/606a36ba7d1b456e60b30db17fdc8c54
[GST3]:https://gist.github.com/z80oolong/3e353bd8f0b44f415880d047b4dad4af
[GST4]:https://gist.github.com/z80oolong/247dbbb0a7d83a1dea98de2939327432
