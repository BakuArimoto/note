# Markdownファイルをローカルで編集し、リアルタイムで表示を確認する

### 目次

- Vimプラグインのインストールのための準備(vimrcの設定)

- Vimプラグインのインストール
- 実際に使用してみる


### Vimプラグインのインストールのための準備(vimrcの設定)
[ここを参考にvimrcの設定](https://howpon.com/20480)


### Vimプラグインのインストール
[ここを参考にプラグインのインストール](https://howpon.com/22203)

call plug#begin('~/.vim/plugged')
と
call plug#end()は
それぞれ
下記のようにcall vundle#begin()とcall vundle#end()に書き換える必要があります。


>call vundle#begin()

>Plug 'godlygeek/tabular'

>Plug 'plasticboy/vim-markdown'

>Plug 'previm/previm'

>let g:vim_markdown_folding_disabled = 1

>let g:previm_enable_realtime = 1

>let g:previm_open_cmd = 'open -a Google\ Chrome'

>call vundle#end()


### 実際に使用してみる
Vimエディタをのコマンドモードで下記を実行します。
:PluginInstall

