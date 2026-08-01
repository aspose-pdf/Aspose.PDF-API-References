---
title: "クラス FormEditor"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.FormEditor クラス。フォームのフィールドの追加/削除などを編集するためのクラス。"
type: docs
weight: 4450
url: /ja/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

フォームの編集（フィールドの追加/削除など）を行うクラスです。

```csharp
public sealed class FormEditor : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | FormEditor のコンストラクタ。 |
| [FormEditor](formeditor/#constructor_1)(Document) | *document* を基に新しい `FormEditor` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | PDF ファイル形式を設定します。結果ファイルは指定された形式で保存されます。このプロパティが指定されていない場合、ファイルは変換なしでデフォルトの PDF 形式で保存されます。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業対象の document ファサードを取得します。 |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | エクスポート値を持つコンボボックスのオプションを設定します。 |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | フィールドの視覚属性を設定します。 |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | 新しく作成されたリストボックスまたはコンボボックスに追加される項目を設定します。 |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | 新しいラジオボタンフィールドが追加される際のラジオボタン項目サイズを取得または設定します。 |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | 隣接するラジオボタン間のギャップをピクセル単位で記録するメンバーで、デフォルトは 50 です。 |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | ラジオボタンが水平に配置されているか垂直に配置されているかを示すフラグで、デフォルト値は true です。 |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | 送信ボタンの送信フラグを設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | 指定されたタイプのフィールドをフォームに追加します。 |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | 指定されたタイプのフィールドをフォームに追加します。 |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | PushButton フィールドの JavaScript を追加します。古いイベントが存在する場合、新しいイベントはその後に追加されます。 |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | リストボックスに新しい項目を追加します。 |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | 既存のリストボックスフィールドにエクスポート値を持つ新しい項目を追加します（AcroForm コンボボックスフィールドにのみ適用）。 |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | フォームに送信ボタンを追加します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | ファサードを閉じます。 |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | 既存のフィールドを指定されたページ番号の同じ位置にコピーします。新しいドキュメントが生成され、元のドキュメントのすべての内容が含まれますが、新しくコピーされたフィールドは除外されます。 |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | 既存のフィールドをページ番号と座標の両方で指定された新しい位置にコピーします。新しいドキュメントが生成され、元のドキュメントのすべての内容が含まれますが、新しくコピーされたフィールドは除外されます。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | 既存のフィールドを、元のページ番号と座標を保持したまま、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールド（ラジオボックスを除く）のみ対象です。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | 既存のフィールドを、指定されたページ番号と元の座標で、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールド（ラジオボックスを除く）のみ対象です。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | 既存のフィールドを、指定されたページ番号と座標で、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールド（ラジオボックスを除く）のみ対象です。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | 指定されたフィールドタイプを持つすべてのフィールドの視覚属性を変更します。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | 指定されたフィールドの視覚属性を変更します。 |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | リストフィールドから項目を削除します。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | フィールドフラグを取得します。 |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | フィールドの新しい位置を設定します。 |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | フォームからフィールドを削除します。 |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | フィールドの送信アクションを削除します。 |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | フィールドの名前を変更します。 |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | すべての視覚属性を空の値にリセットします。 |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | 内部ファサードのすべての視覚属性を空の値にリセットします。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF ドキュメントを指定されたファイルに保存します。 |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | テキストフィールドの配置スタイルを設定します。 |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | テキストフィールドの垂直配置スタイルを設定します。 |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | フィールドフラグを設定します |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | フィールドの属性を設定します。 |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | 通常の単一行テキストフィールドのコンブ数を設定します（フィールドは combNumber パラメータの値に応じて、同じ間隔の位置（コンブ）に自動的に分割されます）。 |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | テキストフィールドの最大文字数を設定します。 |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | PushButton フィールドの JavaScript を設定します。既存の JavaScript がある場合は新しいものに置き換えられます。 |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | 送信ボタンの submit フラグを設定します。 |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | ボタンの URL を設定します。 |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | 単一行テキストフィールドを複数行テキストフィールドに変更します。 |

### 関連項目

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


