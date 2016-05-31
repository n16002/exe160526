## vim comannd(1)

### vim normal mode comannd list

1. h - move cursor left
1. j - カーソルを下に移動 - move cursor down
1. k - カーソルを上に移動 - move cursor up
1. l - カーソルを右に移動 - move cursor right
1. :q! - 保存せず終了 - quit and throw away unsaved changes
1. :wq - 保存して終了 - write (save) and quit
1. x - 一文字削除 - delete (cut) character
1. i - カーソルがある位置にテキストを入力 - insert before the cursor
1. I - 行の先頭にテキストを入力 - insert at the beginning of the line
1. a - カーソルがある位置の後ろにテキストを入力 - insert (append) after the cursor
1. A - 行の最後にテキストを入力 - insert (append) at the end of the line
1. d - 一行削除 - delete marked text
1. w - 一単語分進む - jump forwards to the start of a word
1. e - 前方の単語の終わりに移動 - jump forwards to the end of a word
1. u - 直前の操作を取りやめる - undo 
1. Ctrl + r - 取り消したものを再度取り消す - redo
1. p - カーソルの下にペースト - put (paste) the clipboard after cursor
1. r - 一文字置き換える - replace a single character
1. c - カーソル位置から行末まで削除して、インサートモードに入る
1. Ctrl + g - ファイル内での位置とファイルの情報を表示
1. gg - テキストを整形する - go to the first line of the document
1. G - ファイルの最後の行に移動 - go to the last line of the document
1. / - 文字列 を検索する（順方向）
1. % - 対応する括弧に移動
1. :s/old/new/g - replace all old with new throughout file

### vim insert/append mode command list

1. esc - コマンドモードに戻る
