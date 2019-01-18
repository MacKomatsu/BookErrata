# 正誤表

編集者がいないため、初版か新規内容の改訂を含む版には単純な文章の誤りが含まれています。

特に文が切れているものは意味がないと考えてもらって結構です。

## OpenCL入門

## C++プログラミング

## C/C++プログラマーが予備知識として学ぶアセンブリ言語・コンピューターアーキテクチャ

## Linux で C/C++ の足固め: メモリー/ファイル/mmap (kernel 4.18.16)、malloc (glibc2.7)、アロケーター（C++11/14/17）「初版」

* fopen / fread / fwrite / fclose 関数

> 読み込みみの為に開きます。

「読み込みの為に開きます。」の間違い。

>その他は

文が切れている箇所は削除（または無視）でお願いします。

* Linux のファイルシステム => file (カーネル)

> kmalloc() / vmalloc() / alloc_pages() 等の関数で確保したメモリー領域

削除（または無視）でお願いします。

「kmalloc() / vmalloc() / alloc_pages() 等の関数により確保したカーネルのメモリー領域を（ vma 引数で指定された ）ユーザーアプリケーションのメモリー領域にマッピングさせます」に脳内返還してもらって良いのですが、kmalloc() 等の関数とカーネルからユーザーアプリケーションへのマッピングはデバイスドライバの知識が不可欠のためです。

筆者がデバイスドライバを含めるか悩んでいた痕跡ではありますが、本の流れからは不要と判断すべきところを、迷ったまま本文に残ってしまいました。

時間の都合により初版ではデバイスドライバの説明は入れませんでしたが、簡単なデバイスドライバのハローワールドプログラムでも書いておけば、中途半端に文章が終わることは無かったので、次の版では大幅に加筆修正する予定です。



