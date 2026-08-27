---
title: "Stamp"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "スタンプを表すクラスです。"
type: docs
weight: 410
url: /ja/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

スタンプを表すクラスです。

Stamp 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| Stamp() | Stamp クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| stamp_id | スタンプの識別子を取得または設定します。 |
| quality | 画像スタンプの品質をパーセンテージで取得または設定します。 有効な値は 0..100%。 |
| opacity | スタンプの不透明度を取得または設定します。 |
| page_number | ページ番号を取得または設定します。 |
| pages | スタンプの影響を受けるページ番号の配列を取得または設定します。 <br/>            Pages が null の場合、ドキュメントのすべてのページが対象となります。 |
| rotation | スタンプの回転角度（度）を取得または設定します。 |
| is_background | 背景ステータスを取得または設定します。true の場合、スタンプはページの背景として配置されます。<br/>            デフォルトは false に設定されています。 |
| blending_space | BlendingColorSpace 値を取得または設定します。この値はページ上で透過およびブレンド操作を行うために使用されるカラースペースを定義します。<br/>             |
## メソッド
| 名前 | 説明 |
| :- | :- |
| bind_pdf(pdf_file, page_number) | スタンプとして使用される PDF ファイルとページ番号を設定します。 |
| bind_pdf(pdf_stream, page_number) | スタンプとして使用される PDF ファイルとページ番号を設定します。 |
| bind_image(image_file) | 画像をスタンプとして設定します。 |
| bind_image(image) | スタンプとして使用される画像を設定します。 |
| bind_logo(formatted_text) | テキストをスタンプとして設定します。 |
| bind_text_state(text_state) | スタンプテキストのテキスト状態を設定します。 |
| set_origin(origin_x, origin_y) | スタンプが配置されるページ上の位置を設定します。 |
| set_image_size(width, height) | 画像スタンプのサイズを設定します。画像は指定された値に従ってスケーリングされます。 |

### 関連項目

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

