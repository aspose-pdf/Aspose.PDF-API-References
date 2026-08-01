---
title: "クラス Page"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Page クラス。PDF ドキュメントのページを表すクラスです。"
type: docs
weight: 8190
url: /ja/net/aspose.pdf/page/
---
## Page class

PDF document の page を表すクラスです。

```csharp
public sealed class Page : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | ページプロパティのコレクションを取得します。 |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | ページアノテーションのコレクションを取得します。[`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | ページのアートボックスを取得または設定します。 |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | ページ上のアーティファクトのコレクションを取得します。 |
| [Background](../../aspose.pdf/page/background/) { get; set; } | ページの背景色を取得または設定します。 |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | 取得または設定するページの背景画像（ジェネレータ専用で、Document を読み込む際には設定されません）。 |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | ページのブリードボックスを取得または設定します。 |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | ページの色タイプを、SetColor 演算子、画像、およびフォームから取得した情報に基づいて設定します。 |
| [Contents](../../aspose.pdf/page/contents/) { get; } | ページのコンテンツストリーム内の演算子コレクションを取得します。 [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | ページのクロップボックスを取得または設定します。 |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | ページの表示時間を取得または設定します。これはプレゼンテーション中にページが表示される秒数です。期間が定義されていない場合は -1 を返します。 |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | このページのタブ順にある Field オブジェクトの一覧を取得します。 |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | ページのフッターを取得または設定します。 |
| [Group](../../aspose.pdf/page/group/) { get; set; } | 透過イメージングモデルで使用するための、ページのページグループの属性を指定するグループ属性クラスを取得または設定します。 |
| [Header](../../aspose.pdf/page/header/) { get; set; } | ページのヘッダーを取得または設定します。 |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | ページの最後の段落の後に段落を追加する機能を取得または設定します。 |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | レイヤーコレクションを取得または設定します。 |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | ページのメディアボックスを取得または設定します。 |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | ノートのラインスタイルを取得または設定します。（生成時のみ使用され、ドキュメント読み取り時には設定されません） |
| [Number](../../aspose.pdf/page/number/) { get; } | ページ番号を取得します。 |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | ページ情報を取得または設定します。（生成時のみ使用され、ドキュメント読み取り時には設定されません） |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | 段落を取得します。 |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | ページの矩形を取得または設定します。取得時: 指定されていればページのクロップボックスが返され、そうでなければページのメディアボックスが返されます。設定時: 常にページのメディアボックスが設定されます。このプロパティはページの回転を考慮しないことに注意してください。回転を考慮したページ矩形を取得するには ActualRect を使用してください。 |
| [Resources](../../aspose.pdf/page/resources/) { get; } | ページのリソースを取得します。Resources オブジェクトには画像、フォーム、フォントのコレクションが含まれます。 [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | ページの回転を取得または設定します。 |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | ページの変換行列を取得します。 |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | ページのタブ順を取得または設定します。可能な値: Row、Column。デフォルト、Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | 目次情報を取得または設定します。 |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | ページのトリムボックスを取得または設定します。 |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | UserUnit の値を取得または設定します。デフォルトのユーザースペース単位のサイズを 1/72 インチの倍数で示す正の数です。デフォルト値は 1 です。このエントリをページからクリアするには、0 または負の値を設定してください。 |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | ページの透かしを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) ビジターオブジェクトを受け入れ、Annotation の操作機能を提供します。 |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | [`ImagePlacementAbsorber`](../imageplacementabsorber/) ビジターオブジェクトを受け入れ、画像配置オブジェクトの操作機能を提供します。 |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) ビジターオブジェクトを受け入れ、テキストオブジェクトの操作機能を提供します。 |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) ビジターオブジェクトを受け入れ、テキストオブジェクトの操作機能を提供します。 |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | ページにグラフィックを追加します。[`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/) メソッドで要素を1つずつ追加するよりも高速に動作します。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | 画像をページに追加し、指定された矩形の中央に配置して、画像の比率を保持します。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | 画像をページに追加し、指定された矩形の中央に配置して、画像の比率を保持します。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | 検索可能な画像をページに追加し、指定された矩形の中央に配置して、画像の比率を保持します。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | ページに画像を追加し、画像の矩形位置に応じて配置します。 |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | ページにスタンプを配置します。スタンプはページ番号、画像、またはシンプルなテキスト（例: ロゴ）にできます。 |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | 現在のページをビットマップに変換し、バイト配列を返します。 |
| [AsXml](../../aspose.pdf/page/asxml/)() | 現在のページを UTF-8 エンコードの XML に変換します。 |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | bbox 値を計算します。これは、目に見える余白がない内容を含む矩形です。 |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | DSR、OMR、OCR 画像ストリーム用に Page を PNG に変換します。 |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | ページからグラフィックを削除します。[`Remove`](../../aspose.pdf.vector/graphicelement/remove/) メソッドで要素を一つずつ削除するより高速です。 |
| [Dispose](../../aspose.pdf/page/dispose/)() | メモリを解放します |
| [Flatten](../../aspose.pdf/page/flatten/)() | ページ上にあるすべてのフィールドを削除し、その代わりにフィールドの値を配置します。 |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | キャッシュされたデータをクリアします |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | ページコンテンツに対する内部操作に関する通知を返します。（現在、テキスト追加シナリオにおける段落イベントに関する通知のみがサポートされています。） |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | ページの CropBox（または CropBox が null の場合は MediaBox）に基づく矩形を返します。 |
| [GetResources](../../aspose.pdf/page/getresources/)() | ページに関連付けられたリソースを取得します。 |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | ページにベクターグラフィックが存在するかどうかを検出します。 |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | ページが空白かどうかのフラグを取得します。 |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | ページをグレースケールに変換します。 |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | ページ上のすべてのレイヤーを、指定された新しいレイヤー名の単一レイヤーに統合します。 |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | ページ上のすべてのレイヤーを、指定された新しいレイヤー名とオプションのコンテンツグループ ID の単一レイヤーに統合します。 |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | ページのサイズを変更します。 |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | ページを指定されたページデバイスで処理に送ります。 |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | ページを指定されたページデバイスで処理に送ります。 |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | ページのサイズを設定します。 |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | ページにベクターグラフィックが存在する場合、保存を試みます。保存形式は SVG です。 |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | 整数値を対応する回転列挙体メンバーに変換します。 |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | 回転列挙体メンバーを整数値に変換します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | ヘッダーとフッターをカスタマイズするためのイベントです。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | ヘッダーとフッターをカスタマイズする手順。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


