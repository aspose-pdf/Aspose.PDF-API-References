---
title: "クラス ChoiceField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Forms.ChoiceField クラス。選択フィールドの基底クラスを表します"
type: docs
weight: 5110
url: /ja/net/aspose.pdf.forms/choicefield/
---
## ChoiceField class

選択フィールドの基底クラスを表します。

```csharp
public abstract class ChoiceField : Field
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ChoiceField](choicefield/#constructor)(Document) | 選択フィールドを作成します（Generator 用） |
| [ChoiceField](choicefield/#constructor_1)(Document, Rectangle) | ChoiceField のコンストラクタです。 |
| [ChoiceField](choicefield/#constructor_2)(Page, Rectangle) | ChoiceField のコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | 注釈のアクションを取得します。（2 つのプロパティ） |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | フィールドの代替名を取得または設定します（実際のフィールド名の代わりにユーザーインターフェイスでフィールドが識別される場所で使用される代替フィールド名）。代替名は Adobe Acrobat でフィールドのツールチップとして使用されます。 |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | ページ上のこの注釈のインデックスを取得または設定します。 |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | 注釈のタイプを取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 注釈の境界特性を取得または設定します。[`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | 選択変更時にコミットするかどうかのフラグを取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | このフィールドのサブフィールド数を取得します。（例：ラジオボタンフィールドの項目数） |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | フィールドのデフォルト外観を取得または設定します。 |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | フィールドのエクスポート可能フラグを取得または設定します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | 注釈のハイライトモード。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します（PDF ジェネレータ用）。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列に配置されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | このフィールドが非終端フィールド（つまりフィールドのグループ）であるかどうかを示すブール値を取得または設定します。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインかどうかを取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されるように強制する bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。（pdf 生成用） |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Generator のサポート用プロパティです。フィールドがヘッダーまたはフッターに追加されるときに使用されます。true の場合、このフィールドは一度だけ作成され、その外観は Document のすべてのページで表示されます。false の場合、各 Document ページごとに個別のフィールドが作成されます。 |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | 辞書が同期されている場合は true を返します。 |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | このフィールドに含まれるサブフィールドをサブフィールド名で取得します。（インデクサー 2 つ） |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Document からインタラクティブなフォームフィールドデータをエクスポートする際に使用されるフィールドのマッピング名を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側余白を取得または設定します（pdf 生成用） |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Annotation が最近変更された日時を取得または設定します。 |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | 複数選択フラグを取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Page 上の Annotation 名を取得または設定します。 |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Annotation がアクティブ化されたときに実行されるアクションです。 |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | 選択肢オプションのコレクションを取得します。 |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | このフィールドを含む Page のインデックスを取得します。 |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Annotation の親を取得します。 |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | フィールドの部分名を取得または設定します。 |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | フィールドの読み取り専用ステータスを取得または設定します。 |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | フィールドの矩形を取得または設定します。 |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | フィールドの必須ステータスを取得または設定します。 |
| virtual [Selected](../../aspose.pdf.forms/choicefield/selected/) { get; set; } | 選択されたオプションのインデックスを取得または設定します。このプロパティにより選択を変更できます。 |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems/) { get; set; } | 選択された項目の配列を取得または設定します。マルチセレクトリストの場合、配列には複数の項目が含まれます。シングルセレクトリストの場合、単一の項目が含まれます。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Annotation の外観辞書を取得します。 |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | 同期オブジェクトです。 |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | フィールドのタブ順序を取得または設定します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Annotation のテキスト配置を取得または設定します。 |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | フィールドの値を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 注釈の幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す整数値を取得または設定します。ZIndex が大きいグラフは ZIndex が小さいグラフの上に配置されます。ZIndex は負の値にすることもできます。負の ZIndex を持つグラフはページ内のテキストの背後に配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | ビジターを受け入れます。 |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/#addoption)(string) | 指定された名前で新しいオプションを追加します。 |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/#addoption_1)(string, string) | 指定されたエクスポート値と名前で新しいオプションを追加します。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 行列変換に従ってパラメータと外観を更新します。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッドです。常に null を返します。 |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | このフィールドのサブフィールドを、指定されたインデックスから配列にコピーします。 |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | 名前でオプションを削除します。 |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | フィールドに対して指定された JavaScript アクションを実行します。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | 指定された PDF フォームフィールドを JSON 形式でエクスポートし、結果を提供されたストリームに書き込みます。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | 指定された PDF フォームフィールドを JSON 形式でエクスポートし、結果を指定されたファイルに書き込みます。 |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | 指定されたフィールドの内容を JSON ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | このフィールドを削除し、その値をページに直接配置します。 |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | 既存の状態名に従って「checked」状態の名前を返します。 |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | 含まれるフィールドの列挙子を返します。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮した注釈の矩形を返します。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | フィールドの完全名が完全一致することに基づき、JSON ストリームから指定されたフィールドにデータをインポートします。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | JSON ストリームから指定されたフィールドにデータをインポートします。マッチングには 'fieldFullNameInJSON' 変数で指定された完全名を使用します。 |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | フォーム上のすべての計算フィールドを再計算します。 |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | フィールドの位置を設定します。 |

### 関連項目

* class [Field](../field/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


