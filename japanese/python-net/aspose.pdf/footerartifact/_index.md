---
title: "FooterArtifact"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "フッターアーティファクトを記述します。これはページのフッターを設定するために使用できます。"
type: docs
weight: 400
url: /ja/python-net/aspose.pdf/footerartifact/
---

## FooterArtifact class

フッターアーティファクトを記述します。これはページのフッターを設定するために使用できます。

FooterArtifact 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| FooterArtifact() | Footer Artifact のインスタンスを作成します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| custom_type | アーティファクトタイプの名前を取得します。非標準のアーティファクトタイプの場合に使用できます。 |
| custom_subtype | アーティファクトサブタイプの名前を取得します。標準でないサブタイプの場合に使用できます。 |
| type | アーティファクトタイプを取得します。 |
| subtype | アーティファクトのサブタイプを取得します。アーティファクトに標準外のサブタイプがある場合、サブタイプの名前は CustomSubtype を介して取得できます。 |
| contents | アーティファクトの内部オペレーターのコレクションを取得します。 |
| form | アーティファクトの XForm を取得します（XForm が使用されている場合）。 |
| rectangle | アーティファクトの矩形を取得します。 |
| position | アーティファクトの位置を取得または設定します。<br/>            このプロパティが指定されている場合、余白と配置は無視されます。 |
| right_margin | アーティファクトの右余白。 <br/>            Position プロパティで位置が明示的に指定されている場合、この値は無視されます。 |
| left_margin | アーティファクトの左余白。 <br/>            Position プロパティで位置が明示的に指定されている場合、この値は無視されます。 |
| top_margin | アーティファクトの上余白。 <br/>            Position プロパティで位置が明示的に指定されている場合、この値は無視されます。 |
| bottom_margin | アーティファクトの下余白。 <br/>            Position プロパティで位置が明示的に指定されている場合、この値は無視されます。 |
| artifact_horizontal_alignment | アーティファクトの水平配置。 <br/>            Position プロパティで位置が明示的に指定されている場合、この値は無視されます。 |
| artifact_vertical_alignment | アーティファクトの垂直配置。 <br/>            Position プロパティで位置が明示的に指定されている場合、この値は無視されます。 |
| rotation | アーティファクトの回転角度を取得または設定します。 |
| text | アーティファクトのテキストを取得します。 |
| image | アーティファクトの画像を取得します（存在する場合）。 |
| opacity | アーティファクトの不透明度を取得または設定します。可能な値は 0..1 の範囲です。 |
| lines | 複数行テキストアーティファクトの行数。 |
| text_state | アーティファクトテキストのテキスト状態。 |
| is_background | true の場合、アーティファクトはページコンテンツの背後に配置されます。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| set_image(image_stream) | アーティファクトの画像を設定します。 |
| set_image(image_name) | アーティファクトの画像を設定します。 |
| set_text(formatted_text) | アーティファクトのテキストを設定します。 |
| set_text_and_state(text, text_state) | アーティファクトのテキストとテキストプロパティを設定します。 |
| set_lines_and_state(text, text_state) | アーティファクトのテキストとテキストプロパティを設定します。複数行を指定できます。 |
| set_pdf_page(page) | アーティファクトとして文書ページに配置される PDF ページを設定します。 |
| get_value(name) | アーティファクトのカスタム値を取得します。 |
| set_value(name, value) | アーティファクトのカスタム値を設定します。 |
| remove_value(name) | アーティファクトからカスタム値を削除します。 |
| begin_updates() | 遅延更新を開始します。同じアーティファクトに対して複数の変更を行い、パフォーマンスを向上させたい場合にこの機能を使用します。 <br/>            アーティファクトのプロパティが変更されるたびに、通常はアーティファクトの演算子が変更されます。これにより、アーティファクトが変更されるたびにページ内容が変更されます。<br/>            この影響を回避するには、すべてのアーティファクト更新を StartUpdates/SaveUpdates 呼び出しの間に配置してください。<br/>            これにより、ページ内容を一度だけ変更できます。 |
| save_updates() | BeginUpdates() 呼び出し後に行われた、アーティファクト内のすべての更新を保存します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

