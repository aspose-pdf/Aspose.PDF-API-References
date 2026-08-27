---
title: "Form"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "フォームオブジェクトを表すクラスです。"
type: docs
weight: 110
url: /ja/python-net/aspose.pdf.forms/form/
---

## Form class

フォームオブジェクトを表すクラスです。

Form 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_synchronized | オブジェクトがスレッドセーフの場合は true を返します。 |
| sync_root | 同期オブジェクトを返します。 |
| auto_recalculate | 設定されている場合、任意のフィールドが変更されるとすべてのフォームフィールドが再計算されます。デフォルト値は true です。計算フィールドが多数あるフォームに入力する際のパフォーマンス向上のため、false に設定します。 |
| auto_restore_form | 設定されている場合、アノテーションに存在する欠落したフォームフィールドが自動的に作成されます。 |
| default_resources | このフォームに配置されたデフォルトリソースを取得します。 |
| default_appearance | フォームのデフォルト外観を取得または設定します（フォーム上のフィールドのデフォルトフォント、テキストサイズ、カラーを記述するオブジェクト）。 |
| xfa | フォームの XFA データを取得します（存在する場合）。 |
| ignore_needs_rendering | このプロパティが true の場合、変換中に NeedsRendering キーの値は無視されます。<br/>            XFA フォームから標準フォームへの変換時です。デフォルトは false です。 |
| remove_permission | このプロパティが true の場合、変換後に PDF ドキュメントから "Perms" 辞書が削除されます。<br/>            動的ドキュメントを標準に変換します。"Perms" 辞書には、Adobe Acrobat Reader で必須フィールドの選択表示を妨げるルールが含まれることがあります。<br/>            デフォルトは false です。 |
| emulate_requierd_groups | このプロパティが true の場合、必須の Xfa exclGroup 要素コンテナに対して追加の赤い境界矩形が描画されます。<br/>            このプロパティは、フォームの Xfa 表現を標準に変換する際に exclGroup の類似物が存在しないことに対応するために導入されました。<br/>            デフォルトは false です。 |
| type | フォームのタイプを取得します。可能な値は: Standard、Static、Dynamicです。 |
| フィールド | 階層フォームの最下層にあるすべてのフィールドのリストを取得します。 |
| signatures_exist | 設定されている場合、ドキュメントには少なくとも1つの署名フィールドが含まれます。 |
| signatures_append_only | 設定されている場合、ファイルが以前の内容を変更する形で保存（書き込み）されると無効になる可能性のある署名がドキュメントに含まれます。<br/>            増分更新とは対照的です。 |
| sign_dependent_elements_rendering_mode_when_converted | フォームは署名情報を含むことができ、署名済みまたは未署名である可能性があります。<br/>              フォームの表示は、フォームが署名されているかどうかに依存する必要がある場合があります。<br/>              このプロパティは、フォームのコンバータ（例：XFA フォームを Standard フォームに変換する際）に、結果のフォームを署名済みとしてレンダリングすべきか、未署名としてレンダリングすべきかを指示します。 |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | フィールドインデックスでフォームのフィールドを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| delete(field) | フォームからフィールドを削除します。 |
| delete(field_name) | 名前でフォームからフィールドを削除します。 |
| add(field, page_number) | フォームにフィールドを追加します。 |
| add(field) | フォームにフィールドを追加します。 |
| add(field, partial_name, page_number) | フォームに新しいフィールドを追加します。既に他のフォームまたはこのフォームに配置されている場合、フィールドのコピーが作成されます。 |
| has_field(field) | フォームが指定されたフィールドをすでに持っているか確認します。 |
| has_field(field_name) | 指定された名前のフィールドがすでにフォームに追加されているかどうかを判断します。 |
| copy_to(array, index) | フォームに配置されたフィールドを配列にコピーします。 |
| flatten() | すべてのフォームフィールドを削除し、その値をページ上に直接配置します。 |
| add_field_appearance(field, page_number, rect) | フィールドの外観を、文書の指定されたページの指定された位置に追加します。 |
| get_fields_in_rect(rect) | 指定された矩形内のフィールドを返します。 |

### 関連項目

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

