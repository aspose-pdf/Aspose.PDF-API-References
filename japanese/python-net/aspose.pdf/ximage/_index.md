---
title: "XImage"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "画像 X-Object を表すクラスです。"
type: docs
weight: 1680
url: /ja/python-net/aspose.pdf/ximage/
---

## XImage class

画像 X-Object を表すクラスです。

XImage 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| contains_transparency | 画像に透明性が含まれている場合は true を返し、そうでない場合は false を返します。 |
| grayscaled | 画像のグレースケール版を取得します。 |
| filter_type | 画像フィルターの種類を取得します。 |
| width | 画像の幅を取得します。 |
| height | 画像の高さを取得します。 |
| name | 画像名を取得または設定します。ページ内容で参照されている画像の名前を変更すると、ドキュメントが正しくなくなる可能性があります。その場合は XImage.Rename メソッドを使用してください。 |
| メタデータ | 画像のメタデータ。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| save(stream) | 画像データを JPEG 画像としてストリームに保存します。 |
| save(stream, format) | 画像を要求された形式でストリームに保存します。 |
| save(stream, resolution) | 指定された解像度で JPEG 画像として画像データをストリームに保存します。 |
| save(stream, format, resolution) | 要求された形式と指定された解像度で画像をストリームに保存します。 |
| rename(name) | 画像の名前を変更し、画像へのすべての参照を新しい名前に置き換えます |
| get_color_type() | 画像のカラータイプを返します。 |
| detect_color_type(bmp) | 画像のカラータイプを返します。 |
| is_the_same_object(image) | 両方の画像が同じオブジェクトを参照している場合に true を返します。 |
| get_name_in_collection() | ints コレクション内の画像の名前を返します。 |
| to_stream() | 元の画像ストリームを返します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

