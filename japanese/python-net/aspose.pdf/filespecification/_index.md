---
title: "FileSpecification"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "埋め込みファイルを表すクラス。"
type: docs
weight: 360
url: /ja/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

埋め込みファイルを表すクラス。

FileSpecification 型は次のメンバーを公開します:
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| FileSpecification(file) | FileSpecification クラスの新しいインスタンスを初期化します |
| FileSpecification(stream, name) | FileSpecification クラスの新しいインスタンスを初期化します |
| FileSpecification(file, description) | FileSpecification クラスの新しいインスタンスを初期化します |
| FileSpecification(stream, name, description) | FileSpecification クラスの新しいインスタンスを初期化します |
| FileSpecification(file_name, annot) | FileSpecification クラスの新しいインスタンスを初期化します |
| FileSpecification() | 新しい空のファイル仕様を作成します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| エンコーディング | エンコーディング形式を取得または設定します。<br/>            可能な値: Zip - ファイルは ZIP で圧縮されます, <br/>            None - ファイルは圧縮されません。 |
| include_contents | true の場合、ファイルの内容はファイル仕様に含まれます。 |
| encrypted_payload | 暗号化されたペイロードを取得します。 |
| description | ファイル仕様に関連付けられたテキストを取得または設定します。 |
| af_relationship | 関連付けられたファイルリレーションシップ。 |
| stream_contents | ファイルの内容をストリームとして取得します。 <br/>            内容はメモリにロードされないため、メモリ使用量を削減できます。<br/>            ただし、このストリームは位置指定や Length プロパティをサポートしていません。この機能が必要な場合は、代わりに Contents プロパティを使用してください。 |
| contents | 内容ファイルを取得または設定します。 <br/>            このプロパティはメモリにロードされたデータを返すため、大量のデータでメモリ不足例外が発生する可能性があります。<br/>            メモリ使用量を削減するには、StreamContents を使用してください。 |
| params | ファイルパラメータを取得します。 |
| mime_type | 埋め込みファイルのサブタイプを取得します |
| name | ファイル仕様名を取得または設定します。 |
| unicode_name | ファイル仕様の Unicode 名を取得または設定します。 |
| file_system | ファイルシステムの名前を取得または設定します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| get_value(key) | アプリケーション固有のパラメータを取得します。 |
| set_value(key, value) | アプリケーション固有のパラメータを設定します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

