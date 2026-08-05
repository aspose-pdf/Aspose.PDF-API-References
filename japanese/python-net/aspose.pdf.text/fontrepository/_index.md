---
title: "FontRepository"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "フォント検索を実行します。システムにインストールされたフォントと標準PDFフォントを検索します。<br/>             カスタムフォントを開く機能も提供します。"
type: docs
weight: 130
url: /ja/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

フォント検索を実行します。システムにインストールされたフォントと標準PDFフォントを検索します。<br/>             カスタムフォントを開く機能も提供します。

FontRepository 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| FontRepository() | FontRepository クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| substitutions | フォント置換戦略コレクションを取得します。 |
| sources | フォントソースコレクションを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| find_font(font_name) | 指定されたフォント名のフォントを検索して返します。 |
| find_font(font_name, ignore_case) | 大文字小文字の区別を無視または考慮して、指定されたフォント名のフォントを検索して返します。 |
| find_font(font_family_name, stl) | 指定されたフォント名とフォントスタイルのフォントを検索して返します。 |
| find_font(font_family_name, stl, ignore_case) | 指定されたフォント名とフォントスタイルのフォントを検索して返します <br/>             大文字小文字の区別を無視または考慮します。 |
| open_font(font_stream, font_type) | 指定されたフォントストリームでフォントを開きます。 |
| open_font(font_file_path) | 指定されたフォントファイルパスでフォントを開きます。 |
| open_font(font_file_path, metrics_file_path) | 指定されたフォントファイルパスでフォントを開きます。 |
| load_fonts() | システムにインストールされたフォントと標準の Pdf フォントをロードします。このメソッドはフォントのロードプロセスを高速化するために設計されました。<br/>            デフォルトでは、フォントは任意のフォントへの最初のリクエスト時にロードされます。このメソッドを使用すると、システムと標準の Pdf フォントが<br/>            任意の Pdf ドキュメントが開かれる直前にロードされます。 |
| reload_fonts() | プロパティ [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) で指定されたすべてのフォントを再ロードします |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

