---
title: Class SignatureField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.SignatureField クラス。署名フォームフィールドを表します
type: docs
weight: 5290
url: /ja/net/aspose.pdf.forms/signaturefield/
---
## SignatureField クラス

署名フォームフィールドを表します。

```csharp
public sealed class SignatureField : Field
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SignatureField](signaturefield/#constructor)(Document, Rectangle) | `SignatureField` クラスの新しいインスタンスを初期化します。 |
| [SignatureField](signaturefield/#constructor_1)(Page, Rectangle) | `SignatureField` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | 注釈アクションを取得します。 (2 プロパティ) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 現在の注釈の外観状態を取得または設定します。 |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | フィールドの代替名を取得または設定します (ユーザーインターフェイスでフィールドを識別する際に実際のフィールド名の代わりに使用される代替フィールド名)。代替名は Adobe Acrobat のフィールドツールチップとして使用されます。 |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | ページ上のこの注釈のインデックスを取得または設定します。 |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | 注釈の種類を取得します。 |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 注釈の外観辞書を取得します。 |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 注釈の境界線の特性を取得または設定します。 [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 注釈の特性を取得します。 |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 注釈の色を取得または設定します。 |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 注釈のテキストを取得または設定します。 |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | このフィールド内のサブフィールドの数を取得します。 (例えば、ラジオボタンフィールド内のアイテム数)。 |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | フィールドのデフォルトの外観を取得または設定します。 |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | フィールドのエクスポータブルフラグを取得または設定します。 |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 注釈のフラグ。 |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 注釈の完全修飾名を取得します。 |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 注釈の高さを取得または設定します。 |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | 注釈のハイライトモード。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | フラグメントハイパーリンクを取得または設定します (PDF ジェネレーター用)。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | この段落が次の列にあるかどうかを示す bool 値を取得または設定します。デフォルトは false です。(PDF 生成用) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | このフィールドが非終端フィールド、すなわちフィールドのグループであるかどうかを示すブール値を取得または設定します。 |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 段落がインラインであるかどうかを取得または設定します。デフォルトは false です。(PDF 生成用) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | この段落が新しいページで生成されることを強制する bool 値を取得または設定します。デフォルトは false です。(PDF 生成用) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 現在の段落が次の段落と同じページに残るかどうかを示す bool 値を取得または設定します。デフォルトは false です。(PDF 生成用) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | ジェネレーターサポート用のプロパティ。フィールドがヘッダーまたはフッターに追加されるときに使用されます。true の場合、このフィールドは一度作成され、その外観はドキュメントのすべてのページに表示されます。false の場合、各ドキュメントページに対して別々のフィールドが作成されます。 |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | 辞書が同期されている場合は true を返します。 |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | サブフィールドの名前によってこのフィールドに含まれるサブフィールドを取得します。 (2 インデクサ) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | ドキュメントからインタラクティブフォームフィールドデータをエクスポートする際に使用されるフィールドのマッピング名を取得または設定します。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 段落の外側の余白を取得または設定します (PDF 生成用) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 注釈が最近変更された日時を取得または設定します。 |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | ページ上の注釈名を取得または設定します。 |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | 注釈がアクティブ化されたときに実行されるアクション。 |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | このフィールドを含むページのインデックスを取得します。 |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | 注釈の親を取得します。 |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | フィールドの部分名を取得または設定します。 |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | フィールドの読み取り専用状態を取得または設定します。 |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | フィールドの矩形を取得または設定します。 |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | フィールドの必須状態を取得または設定します。 |
| [Signature](../../aspose.pdf.forms/signaturefield/signature/) { get; } | 署名オブジェクトを取得します。このオブジェクトには公開鍵暗号基準に関する署名データが含まれています。クラス [`PKCS1`](../pkcs1/)、[`PKCS7`](../pkcs7/) および [`PKCS7Detached`](../pkcs7detached/) は、すべてのサポートされている署名オブジェクトのタイプを表します。 |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 注釈の外観辞書を取得します。 |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | 同期オブジェクト。 |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | フィールドのタブ順序を取得または設定します。 |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 注釈のテキストの配置を取得または設定します。 |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | フィールドの値を取得または設定します。 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 段落の垂直配置を取得または設定します。 |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 注釈の幅を取得または設定します。 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | グラフの Z 順序を示す int 値を取得または設定します。ZIndex が大きいグラフは、ZIndex が小さいグラフの上に配置されます。ZIndex は負の値を取ることができます。負の ZIndex を持つグラフは、ページ内のテキストの後ろに配置されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | ビジターを受け入れます。 |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | マトリックス変換に従ってパラメータと外観を更新します。 |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | このインスタンスをクローンします。仮想メソッド。常に null を返します。 |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | 指定されたインデックスから配列にこのフィールドのサブフィールドをコピーします。 |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | フィールドの指定された JavaScript アクションを実行します。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | 指定された PDF フォームフィールドを JSON 形式にエクスポートし、結果を提供されたストリームに書き込みます。 |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | 指定された PDF フォームフィールドを JSON 形式にエクスポートし、結果を指定されたファイルに書き込みます。 |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | 指定されたフィールドの内容を JSON ストリームにエクスポートします。ボタンフィールドの値はエクスポートされません。 |
| [ExtractCertificate](../../aspose.pdf.forms/signaturefield/extractcertificate/)() | DER 形式の単一 X.509 証明書をストリームとして抽出します。 |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage)() | 署名の画像を JPEG エンコードされたストリームとして抽出します。 |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage_1)(ImageFormat) | 署名の画像をエンコードされたストリームとして抽出します。 |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | このフィールドを削除し、その値をページに直接配置します。 |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | 既存の状態名に従って「チェック済み」状態の名前を返します。 |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | 含まれるフィールドの列挙子を返します。 |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | ページの回転を考慮して注釈の矩形を返します。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | フィールドの完全な名前の正確な一致に基づいて、JSON ストリームから指定されたフィールドにデータをインポートします。 |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | 'fieldFullNameInJSON' 変数で指定された完全な名前を使用して、JSON ストリームから指定されたフィールドにデータをインポートします。 |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | フォーム上のすべての計算フィールドを再計算します。 |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | フィールドの位置を設定します。 |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign)(Signature) | この署名フィールドを使用してドキュメントに署名します。 |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign_1)(Signature, Stream, string) | この署名フィールドを使用してドキュメントに署名します。 |

### 参照

* クラス [Field](../field/)
* 名前空間 [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../)