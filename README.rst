=================================
 TeXstudio UI 日本語訳用ファイル
=================================

.. contents:: 目次
   :local:

概要
====

TeXstudio UI 日本語訳用ファイルは、
TeXstudioのユーザーインターフェースを日本語化するためのファイルです。

.. note::

    **基本的にはTeXstudioに同梱されている日本語化ファイルを利用してください。**
    同梱されているファイルに不満がある場合などにこのファイルを利用することをおすすめします。

利用法
======

#. ファイルtexstudio_ja.qmを、TeXstudioのシステムディレクトリの
   texstudio_*.qmが存在するディレクトリに移動

#. TeXstudioの設定で言語を日本語に変更

翻訳ファイルの更新方法
======================

基本的に `TransifexのTeXstudioプロジェクト`_ から翻訳を更新するようにしてください。
こちらの方法以外で更新した場合、公式の翻訳には反映されませんので注意してください。

.. _TransifexのTeXstudioプロジェクト: https://www.transifex.com/texstudio/texstudio/

翻訳ファイルを独自に更新したい場合は、次の作業を行なってください
（内容は `TeXstudio Wikiのtranslation`_ に書かれていることとほぼ同じ）。

.. _TeXstudio Wikiのtranslation: http://sourceforge.net/apps/mediawiki/texstudio/index.php?title=Translate

#. Qt開発環境に付属するLinguistとlreleaseコマンドを使用可能な状態にする

#. Linguistでtexstudio_ja.tsを開いて翻訳を行う

#. lreleaseコマンドでtexstudio_ja.tsをtexstudio_ja.qmへ変換する

その他
======

* なにかある場合はIssueもしくはmilestoneへ上げること
