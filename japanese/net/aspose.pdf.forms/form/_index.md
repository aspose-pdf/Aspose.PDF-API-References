---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Form クラス。フォームオブジェクトを表すクラス
type: docs
weight: 5070
url: /ja/net/aspose.pdf.forms/form/
---
## フォーム クラス

フォームオブジェクトを表すクラス。

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | 設定されている場合、任意のフィールドが変更されるとすべてのフォームフィールドが再計算されます。デフォルト値は true です。計算フィールドが多数あるフォームを記入する際のパフォーマンスを向上させるために false に設定します。 |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | 設定されている場合、欠落しているフォームフィールドはアノテーションに存在する場合に自動的に作成されます。 |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | フィールド計算の順序を設定できます。 |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | このフォームのフィールドの数を取得します。 |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | フォームのデフォルトの外観を取得または設定します（フォームのフィールドのデフォルトフォント、テキストサイズ、色を説明するオブジェクト）。 |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | このフォームに配置されたデフォルトリソースを取得します。 |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | このプロパティが true の場合、必須の Xfa exclGroup 要素コンテナのために追加の赤い境界矩形が描画されます。このプロパティは、標準への変換中に exclGroup の類似物が欠如しているために導入されました。デフォルトでは false です。 |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | 階層フォームの最下層にあるすべてのフィールドのリストを取得します。 |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | このプロパティが true の場合、XFA フォームを標準フォームに変換する際に NeedsRendering キーの値が無視されます。デフォルトでは false です。 |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | オブジェクトがスレッドセーフである場合は true を返します。 |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | フィールド名によってフォームのフィールドを取得します。フィールドが見つからない場合は例外をスローします。（2 つのインデクサ） |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | このプロパティが true の場合、動的ドキュメントを標準に変換した後、"Perms" 辞書が PDF ドキュメントから削除されます。"Perms" 辞書には、Adobe Acrobat リーダーで必須フィールドの選択を表示するのを妨げるルールが含まれる場合があります。デフォルトでは false です。 |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | 設定されている場合、ドキュメントには、ファイルが以前の内容を変更する方法で保存（書き込み）された場合に無効になる可能性のある署名が含まれます。 |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | 設定されている場合、ドキュメントには少なくとも 1 つの署名フィールドが含まれています。 |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | 同期オブジェクトを返します。 |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | フォームのタイプを取得します。可能な値は: Standard, Static, Dynamic です。 |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | フォームの XFA データを取得します（存在する場合）。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | フォームにフィールドを追加します。 |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | フォームにフィールドを追加します。 |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | フォームに新しいフィールドを追加します。このフィールドが他のフォームまたはこのフォームに既に配置されている場合、フィールドのコピーが作成されます。 |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | 指定されたページの指定された位置にフィールドの追加の外観を追加します。 |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | フォームの XFA を指定された値に設定します。 |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | フォームに配置されたフィールドを配列にコピーします。 |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | フォームからフィールドを削除します。 |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | 名前によってフォームからフィールドを削除します。 |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | PDF フォームフィールドを JSON 形式にエクスポートし、結果を提供されたストリームに書き込みます。 |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | PDF フォームフィールドを JSON 形式にエクスポートし、結果を指定されたファイルに書き込みます。 |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | すべてのフォームフィールドを削除し、その値をページに直接配置します。 |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | フォームフィールドの列挙を取得します。 |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | 指定された矩形内のフィールドを返します。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | フォームに指定されたフィールドが既に存在するかどうかを確認します。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | 指定された名前のフィールドがフォームに既に追加されているかどうかを判断します。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | 指定された名前のフィールドがフォームに既に追加されているかどうかを判断し、フィールドの子階層を調べることができます。 |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | ストリームで提供された JSON 形式から PDF フォームフィールドをインポートします。 |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | 指定されたファイルから提供された JSON 形式から PDF フォームフィールドをインポートします。 |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | フォームフィールドのアノテーションを独立させます。 |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | 指定されたインデックスのフィールドの外観を削除します。子の外観が 1 つだけ残っている場合、このメソッドはそれをフィールドに埋め込みます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | フォームには署名情報を含むことができ、署名済みまたは未署名である可能性があります。そして、フォームの表示は、フォームが署名されているかどうかに依存する必要があります。このプロパティは、フォームのコンバータに、結果のフォームが署名されたものとしてレンダリングされるべきか、未署名としてレンダリングされるべきかを指示します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | フォームのフラッティング手順の設定を説明するクラス。 |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | フォームには署名情報を含むことができ、署名済みまたは未署名である可能性があります。時には、ビューアでのフォームの表示は、フォームが署名されているかどうかに依存する必要があります。この列挙型は、署名に関するフォームタイプの変換中に可能なレンダリングモードを列挙します。 |

### 参照

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)