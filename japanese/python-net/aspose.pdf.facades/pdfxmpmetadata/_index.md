---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "XMPメタデータを操作するクラスです。"
type: docs
weight: 380
url: /ja/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

XMPメタデータを操作するクラスです。

PdfXmpMetadata 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| PdfXmpMetadata() | PdfXmpMetadata のコンストラクタ。 |
| PdfXmpMetadata(document) | PdfXmpMetadata クラスの新しいインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| document | ドキュメントファサードを取得します。 |
| keys | 辞書からキーを取得します。 |
| values | 辞書内の値のコレクションを取得します。 |
| is_fixed_size | コレクションが固定サイズの場合は true を返します。 |
| is_synchronized | コレクションが同期されている場合は true を返します。 |
| sync_root | コレクションの同期オブジェクトを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(src_file) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_stream) | PDF ドキュメントを編集用にバインドします。 |
| bind_pdf(src_doc) | PDF ドキュメントを編集用にバインドします。 |
| save(dest_file) | 指定されたファイルに PDF ドキュメントを保存します。 |
| save(dest_stream) | 指定されたストリームに PDF ドキュメントを保存します。 |
| add(key, value) | XMP メタデータに値を追加します。 |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | メタデータに拡張フィールドを追加します。 |
| add(key, value) | 辞書オブジェクトに新しい要素を追加します。 |
| add(key, value) | メタデータに拡張フィールドを追加します。 |
| remove(key) | 指定されたキーの要素を削除します。 |
| remove(key) | 辞書からキーを削除します。 |
| contains(key) | 辞書が指定されたキーを含むかどうかを確認します。 |
| contains(property) | 辞書が指定されたプロパティを含むかどうかを確認します。 |
| get_xmp_metadata() | 入力 PDF の XmpMetadata を XML 形式で取得します。 |
| get_xmp_metadata(name) | メタ名に従って、入力 PDF の XmpMetadata の一部を取得します。 |
| close() | 現在のファサードに関連付けられたリソースを解放します。 |
| register_namespace_uri(prefix, namespace_uri) | 名前空間 URI を登録します。 |
| get_namespace_uri_by_prefix(prefix) | プレフィックスで名前空間 URI を取得します。 |
| get_prefix_by_namespace_uri(namespace_uri) | 名前空間 URI からプレフィックスを取得します。 |
| contains_key(key) | この辞書が指定されたキーを含むかどうかを判断します。 |
| try_get_value(key, value) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

