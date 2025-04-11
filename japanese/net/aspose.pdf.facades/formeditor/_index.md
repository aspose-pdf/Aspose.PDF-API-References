---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormEditor クラス。フォームの編集、フィールドの追加/削除などのクラス
type: docs
weight: 4330
url: /ja/net/aspose.pdf.facades/formeditor/
---
## FormEditor クラス

フォームの編集のためのクラス（フィールドの追加/削除など）

```csharp
public sealed class FormEditor : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | FormEditor のコンストラクタ。 |
| [FormEditor](formeditor/#constructor_1)(Document) | *document* に基づいて新しい `FormEditor` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | PDF ファイル形式を設定します。結果ファイルは指定されたファイル形式で保存されます。このプロパティが指定されていない場合、ファイルは変換なしでデフォルトの PDF 形式で保存されます。 |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | エクスポート値を持つコンボボックスのオプションを設定します。 |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | フィールドの視覚属性を設定します。 |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | 新しく作成されたリストボックスまたはコンボボックスに追加されるアイテムを設定します。 |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | ラジオボタンアイテムのサイズを取得または設定します（新しいラジオボタンフィールドが追加されたとき）。 |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | 隣接する2つのラジオボタン間のギャップをピクセル単位で記録するメンバー、デフォルトは50です。 |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | ラジオボタンが水平または垂直に配置されているかどうかを示すフラグ、デフォルト値はtrueです。 |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | 提出ボタンの提出フラグを設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | 指定されたタイプのフィールドをフォームに追加します。 |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | 指定されたタイプのフィールドをフォームに追加します。 |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | PushButton フィールドのための JavaScript を追加します。古いイベントが存在する場合、新しいイベントはその後に追加されます。 |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | リストボックスに新しいアイテムを追加します。 |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | 既存のリストボックスフィールドにエクスポート値を持つ新しいアイテムを追加します。これは AcroForm コンボボックスフィールドのみに適用されます。 |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | フォームに送信ボタンを追加します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | ファサードを閉じます。 |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | 既存のフィールドを指定されたページ番号の同じ位置にコピーします。新しいドキュメントが生成され、ソースドキュメントに含まれるすべての内容が含まれますが、新しくコピーされたフィールドは含まれません。 |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | 既存のフィールドをページ番号と座標によって指定された新しい位置にコピーします。新しいドキュメントが生成され、ソースドキュメントに含まれるすべての内容が含まれますが、新しくコピーされたフィールドは含まれません。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | 1つの PDF ドキュメントから別のドキュメントに既存のフィールドを元のページ番号と座標でコピーします。注意：AcroForm フィールドのみに適用されます（ラジオボックスを除く）。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | 1つの PDF ドキュメントから別のドキュメントに指定されたページ番号と元の座標で既存のフィールドをコピーします。注意：AcroForm フィールドのみに適用されます（ラジオボックスを除く）。 |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | 1つの PDF ドキュメントから別のドキュメントに指定されたページ番号と座標で既存のフィールドをコピーします。注意：AcroForm フィールドのみに適用されます（ラジオボックスを除く）。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | PDF ドキュメント内のすべてのフィールドの視覚属性を変更します。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | 指定されたフィールドタイプのすべてのフィールドの視覚属性を変更します。 |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | 指定されたフィールドの視覚属性を変更します。 |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | リストフィールドからアイテムを削除します。 |
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
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | テキストフィールドの整列スタイルを設定します。 |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | テキストフィールドの垂直整列スタイルを設定します。 |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | フィールドフラグを設定します。 |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | フィールドの属性を設定します。 |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | 通常の単一行テキストフィールドのコンボ数を設定します（フィールドは自動的にコンボ数パラメータの値に応じて等間隔の位置、またはコンボに分割されます）。 |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | テキストフィールドの最大文字数を設定します。 |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | PushButton フィールドのための JavaScript を設定します。古い JavaScript が存在する場合、新しいものに置き換えられます。 |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | 提出ボタンの提出フラグを設定します。 |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | ボタンの URL を設定します。 |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | 単一行テキストフィールドを複数行のものに変更します。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)