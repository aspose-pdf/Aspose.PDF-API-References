---
title: "AutoFiller"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "データベースやその他のデータソースからデータを受け取り、テンプレート PDF の設計されたフィールドに埋め込み、最終的に新しい PDF ファイルまたはストリームを生成するクラスを表します。<br/>             入力モードは2種類あり、ストリームとして入力するか PDF ファイルとして入力します。<br/>             出力モードは4種類あり、1つの結合ストリーム、1つの結合ファイル、複数の小さなストリーム、複数の小さなファイルです。<br/>             System.Data.DataTable に含まれるリテラルデータを受け取ることができます。"
type: docs
weight: 20
url: /ja/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

データベースやその他のデータソースからデータを受け取り、テンプレート PDF の設計されたフィールドに埋め込み、最終的に新しい PDF ファイルまたはストリームを生成するクラスを表します。<br/>             入力モードは2種類あり、ストリームとして入力するか PDF ファイルとして入力します。<br/>             出力モードは4種類あり、1つの結合ストリーム、1つの結合ファイル、複数の小さなストリーム、複数の小さなファイルです。<br/>             System.Data.DataTable に含まれるリテラルデータを受け取ることができます。

AutoFiller 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| AutoFiller() | AutoFiller クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| output_stream | OutputStream を取得または設定します。4 つの出力モードのうちの一つです。その典型的な使用例は Response.OutputStream です。<br/>            オンラインデモをご参照ください。 |
| output_streams | 複数の Output Streams を取得または設定します。4 つの出力モードのうちの一つです。 |
| input_stream | 入力テンプレートストリームを取得または設定します。2 つの入力モードのうちの一つです。 |
| input_file_name | 入力テンプレートファイルを取得または設定します。2つの入力モードのうちの1つです。 |
| output_file_name | 1つの大きな結合出力ファイルを取得または設定します。4つの出力モードのうちの1つです。 |
| generating_path | 多数の小さな PDF ファイルが生成される場合の小さな PDF ファイルの生成パスを取得または設定します。別のプロパティ [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName と連携します。<br/>            4つの出力モードのうちの1つです。 |
| basic_file_name | 多数の小さなファイルが生成される場合の基本ファイル名を取得または設定します。生成されたファイルは "BasicFileName0","BasicFileName1",... のようになります。<br/>            別のプロパティ [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath と連携します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| save() | すべての PDF を保存します。 |
| save(dest_file) | すべての PDF を保存します。 |
| save(dest_stream) | すべての PDF を保存します。 |
| bind_pdf(src_file) | Pdf ファイルをバインドします。 |
| bind_pdf(src_stream) | Pdf ファイルをバインドします。 |
| bind_pdf(src_doc) | Pdf ドキュメントをバインドします。 |
| close() | オブジェクトと出力ストリームを閉じます。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

