---
title: "クラス Form"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Forms.Form クラス。フォームオブジェクトを表すクラスです。"
type: docs
weight: 5190
url: /ja/net/aspose.pdf.forms/form/
---
## Form class

クラスはフォームオブジェクトを表します。

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | 設定されている場合、任意のフィールドが変更されるとすべてのフォームフィールドが再計算されます。デフォルト値は true です。計算フィールドが多数あるフォームの入力時にパフォーマンスを向上させるため、false に設定します。 |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | 設定されている場合、注釈に存在する欠落したフォームフィールドは自動的に作成されます。 |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | フィールド計算の順序を設定できるようにします。 |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | このフォーム上のフィールド数を取得します。 |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | フォームのデフォルト外観を取得または設定します（フォーム上のフィールドのデフォルトフォント、テキストサイズ、色を記述するオブジェクト）。 |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | このフォームに配置されたデフォルトリソースを取得します。 |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | このプロパティが true の場合、必須の Xfa exclGroup 要素コンテナに対して追加の赤い境界矩形が描画されます。このプロパティは、フォームの Xfa 表現を標準に変換する際に exclGroup の類似物が存在しないために導入されました。デフォルトは false です。 |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | 階層フォームの最下位レベルにあるすべてのフィールドのリストを取得します。 |
| [HasXfa](../../aspose.pdf.forms/form/hasxfa/) { get; } | Documentに XFA フォームが含まれているかどうかを示す値を取得します。このプロパティは、XFA フォームが存在し、[`NeedsRendering`](./needsrendering/) が false の場合に XFA フォームを削除するために [`IgnoreNeedsRendering`](./ignoreneedsrendering/) を使用すべきかどうかを判断するために導入されました。 |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | このプロパティが true の場合、XFA フォームを標準フォームに変換する際に NeedsRendering キーの値が無視されます。デフォルトは false です。 |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | オブジェクトがスレッドセーフである場合は true を返します。 |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | フィールド名でフォームのフィールドを取得します。フィールドが見つからない場合は例外をスローします。（インデクサーが 2 つ） |
| [NeedsRendering](../../aspose.pdf.forms/form/needsrendering/) { get; } | Documentが動的 XFA フォームの削除を必要とするかどうかを示す値を取得します。このプロパティは、XFA フォームが存在し、[`NeedsRendering`](./needsrendering/) が false の場合に XFA フォームを削除するために [`IgnoreNeedsRendering`](./ignoreneedsrendering/) を使用すべきかどうかを判断するために導入されました。 |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | このプロパティが true の場合、動的Documentを標準に変換した後、pdf Documentから "Perms" 辞書が削除されます。"Perms" 辞書には、Adobe Acrobat Reader で必須フィールドの選択表示を妨げるルールが含まれることがあります。デフォルトは false です。 |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | 設定されている場合、ファイルがインクリメンタル更新ではなく、以前の内容を変更する形で保存（書き込み）されると無効になる可能性のある署名がDocumentに含まれます。 |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | 設定されている場合、Documentに少なくとも 1 つの署名フィールドが含まれます。 |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | 同期オブジェクトを返します。 |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | フォームのタイプを取得します。可能な値は: Standard、Static、Dynamic です。 |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | フォームの XFA データを取得します（存在する場合）。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | フォームにフィールドを追加します。 |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | フォームにフィールドを追加します。 |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | フォームに新しいフィールドを追加します。このフィールドが他のフォームまたはこのフォームにすでに配置されている場合、フィールドのコピーが作成されます。 |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | 指定された場所のDocumentの指定ページにフィールドの追加外観を追加します。 |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | フォームの XFA を指定された値に設定します。 |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | フォームに配置されたフィールドを配列にコピーします。 |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | フォームからフィールドを削除します。 |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | 名前でフォームからフィールドを削除します。 |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | PDF フォームフィールドを JSON 形式でエクスポートし、結果を提供されたストリームに書き込みます。 |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | PDF フォーム フィールドを JSON 形式でエクスポートし、結果を指定されたファイルに書き込みます。 |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | すべてのフォーム フィールドを削除し、その値をページ上に直接配置します。 |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | フォーム フィールドの列挙を取得します。 |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | 指定された矩形内のフィールドを返します。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | フォームに指定されたフィールドがすでに存在するか確認します。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | 指定された名前のフィールドがすでにフォームに追加されているかどうかを判断します。 |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | 指定された名前のフィールドがすでにフォームに追加されているかどうかを判断し、フィールドの子階層も参照できるようにします。 |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | ストリームで提供された JSON 形式から PDF フォーム フィールドをインポートします。 |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | 指定されたファイルで提供された JSON 形式から PDF フォーム フィールドをインポートします。 |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | フォーム フィールドの注釈を独立させます。 |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | 指定されたインデックスのフィールドの外観を削除します。子の外観が 1 つだけ残っている場合、メソッドはそれをフィールドに埋め込みます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | フォームには署名情報が含まれる場合があり、署名済みまたは未署名のいずれかです。また、フォームの表示は署名の有無に依存することがあります。このプロパティは、フォームのコンバータ（例：XFA フォームを標準フォームに変換する際）に、結果のフォームを署名済みとしてレンダリングすべきか、未署名としてレンダリングすべきかを指示します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | フォーム平坦化手順の設定を記述するクラスです。 |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | フォームには署名情報が含まれ、署名済みまたは未署名になることがあります。ビューアでのフォーム表示は署名の有無に依存することがあります。この列挙体は、署名に関してフォームタイプの変換中に利用できるレンダリング モードを列挙します。 |

### 関連項目

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


