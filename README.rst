=================================
 TeXstudio UI 日本語訳用ファイル
=================================

.. contents:: 目次
   :local:

概要
====

TeXstudio UI 日本語訳用ファイルは、
TeXstudioのユーザーインターフェースを日本語化するためのファイルです。

利用法
======

#. ファイルtexstudio_ja.qmを、TeXstudioのシステムディレクトリの
   texstudio_*.qmが存在するディレクトリに移動

#. TeXstudioの設定で言語を日本語に変更

翻訳ファイルの更新方法
======================

翻訳ファイルを独自に更新したい場合は、次の作業を行なってください
（内容は `TeXstudio Wikiのtranslation`_ に書かれていることとほぼ同じ）。

.. _TeXstudio Wikiのtranslation: http://sourceforge.net/apps/mediawiki/texstudio/index.php?title=Translate

#. Qt開発環境に付属するLinguistとlreleaseコマンドを使用可能な状態にする

#. Linguistでtexstudio_ja.tsを開いて翻訳を行う

#. lreleaseコマンドでtexstudio_ja.tsをtexstudio_ja.qmへ変換する

Todo
====

* Issueもしくはmilestoneへ上げること
