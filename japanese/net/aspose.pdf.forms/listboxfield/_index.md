---
title: Class ListBoxField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ListBoxField クラス。クラスは ListBox フィールドを表します。
type: docs
weight: 5130
url: /ja/net/aspose.pdf.forms/listboxfield/
---
## ListBoxField クラス

クラスは ListBox フィールドを表します。

```csharp
public sealed class ListBoxField : ChoiceField
```

## Constructors

| Name | Description |
| --- | --- |
| [ListBoxField](listboxfield/#constructor)() | ジェネレーターで使用する ListBoxField のコンストラクター。 |
| [ListBoxField](listboxfield/#constructor_1)(Document, Rectangle) | ListBox フィールドのコンストラクター。 |
| [ListBoxField](listboxfield/#constructor_2)(Page, Rectangle) | 新しい ListBox フィールドを作成します。 |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | アノテーションアクションを取得します。 (2 プロパティ) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在のアノテーション外観状態を取得または設定します。 |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | フィールドの別名を取得または設定します (フィールドがユーザーインターフェイスで識別される際に実際のフィールド名の代わりとして使用される別のフィールド名です)。別名は Adobe Acrobat のフィールドツールチップとして使用されます。 |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | このアノテーションのページ上のインデックスを取得または設定します。 |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | アノテーションの種類を取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | アノテーションの外観ディクショナリを取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | アノテーションの境界線特性を取得または設定します。 [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | アノテーションの特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | アノテーションの色を取得または設定します。 |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | 選択変更時のコミットフラグを取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | アノテーションテキストを取得または設定します。 |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | このフィールド内のサブフィールド数を取得します。（例：ラジオボタンフィールド内の項目数） |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | フィールドのデフォルト外観を取得または設定します。 |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | フィールドのエクスポート可能フラグを取得または設定します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | アノテーションのフラグ。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | アノテーションの完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | アノテーションの高さを取得または設定します。 |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | アノテーションのハイライトモード。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDFジェネレーター用）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次のコラムに配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | このフィールドが末端でない、すなわちフィールドグループであることを示す boolean 値を取得または設定します。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（PDF生成用） |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | ジェネレーターサポート用のプロパティです。フィールドがヘッダーまたはフッターに追加されるときに使用されます。true の場合、このフィールドは一度だけ作成され、その外観はドキュメントのすべてのページで表示されます。false の場合、各ドキュメントページごとに個別のフィールドが作成されます。 |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | ディクショナリが同期されている場合、true を返します。 |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | このフィールドに含まれるサブフィールドをサブフィールド名で取得します。（2 つのインデクサ） |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | ドキュメントからインタラクティブフォームフィールドデータをエクスポートする際に使用される、フィールドのマッピング名を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側の余白を取得または設定します（PDF生成用） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 最近アノテーションが変更された日時を取得または設定します。 |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | 複数選択フラグを取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | ページ上のアノテーション名を取得または設定します。 |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | アノテーションがアクティベートされたときに実行されるアクション。 |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | 選択オプションのコレクションを取得します。 |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | このフィールドを含むページのインデックスを取得します。 |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | アノテーションの親を取得します。 |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | フィールドの部分的な名前を取得または設定します。 |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | フィールドの読み取り専用ステータスを取得または設定します。 |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | フィールドの矩形を取得または設定します。 |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | フィールドの必須ステータスを取得または設定します。 |
| override [Selected](../../aspose.pdf.forms/listboxfield/selected/) { set; } | 選択された項目のインデックスを取得または設定します。項目は 1 から番号付けされます。 |
| override [SelectedItems](../../aspose.pdf.forms/listboxfield/selecteditems/) { set; } | 複数選択リストの選択された項目の配列を取得または設定します。単一選択リストの場合は、1 つの項目のみの配列を返します。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | アノテーションの外観ディクショナリを取得します。 |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | 同期オブジェクト。 |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | フィールドのタブ順序を取得または設定します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | アノテーションのテキスト整列を取得または設定します。 |
| [TopIndex](../../aspose.pdf.forms/listboxfield/topindex/) { get; set; } | リストの上部に表示される要素のインデックスを取得または設定します。 |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | フィールドの値を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直方向の配置を取得または設定します。 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | アノテーションの幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z オーダーを示す int 値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値になることもあります。負の ZIndex のグラフはページ上のテキストの背後に配置されます。 |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | ビジターを受け入れます。 |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string) | 指定された名前の新しいオプションを追加します。 |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | 指定されたエクスポート値と名前を持つ新しいオプションを追加します。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | マトリックス変換に従ってパラメーターと外観を更新します。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッドです。常に null を返します。 |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | 指定されたインデックスから開始して、このフィールドのサブフィールドを配列にコピーします。 |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | オプションをその名前で削除します。 |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | フィールドに対して指定された JavaScript アクションを実行します。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | 指定された PDF フォームフィールドを JSON 形式にエクスポートし、結果を提供されたストリームに書き込みます。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | 指定された PDF フォームフィールドを JSON 形式にエクスポートし、結果を指定されたファイルに書き込みます。 |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | 指定されたフィールドの内容を JSON ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | このフィールドを削除し、その値をページ上に直接配置します。 |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | 既存の状態名に基づいて「チェック済み」状態の名前を返します。 |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | 含まれるフィールドの列挙子を返します。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮してアノテーションの矩形を返します。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | フィールドの完全修飾名と正確に一致するものに基づいて、JSON ストリームから指定されたフィールドにデータをインポートします。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | マッチングに 'fieldFullNameInJSON' 変数に指定された完全名を使用して、JSON ストリームから指定されたフィールドにデータをインポートします。 |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | フォーム上のすべての計算済みフィールドを再計算します。 |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | フィールドの位置を設定します。 |

### See Also

* クラス [ChoiceField](../choicefield/)
* 名前空間 [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../)