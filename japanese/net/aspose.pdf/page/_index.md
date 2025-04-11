---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Page クラス。PDF ドキュメントのページを表すクラス
type: docs
weight: 8050
url: /ja/net/aspose.pdf/page/
---
## Page クラス

PDF ドキュメントのページを表すクラス。

```csharp
public sealed class Page : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | ページプロパティのコレクションを取得します。 |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | ページ注釈のコレクションを取得します。 [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | ページのアートボックスを取得または設定します。 |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | ページ上のアーティファクトのコレクションを取得します。 |
| [Background](../../aspose.pdf/page/background/) { get; set; } | ページの背景色を取得または設定します。 |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | ページの背景画像を取得または設定します（生成者のみ、ドキュメントを読み取るときは設定されません）。 |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | ページのブリードボックスを取得または設定します。 |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | SetColor、画像、フォームから取得した情報に基づいてページの色タイプを設定します。 |
| [Contents](../../aspose.pdf/page/contents/) { get; } | ページのコンテンツストリーム内のオペレーターのコレクションを取得します。 [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | ページのクロップボックスを取得または設定します。 |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | ページの表示時間を取得または設定します。これはプレゼンテーション中にページが表示される時間（秒）です。期間が定義されていない場合は -1 を返します。 |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | このページのタブ順序の Field オブジェクトのリストを取得します。 |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | ページのフッターを取得または設定します。 |
| [Group](../../aspose.pdf/page/group/) { get; set; } | 透明なイメージングモデルで使用するためのページグループの属性を指定するグループ属性クラスを取得または設定します。 |
| [Header](../../aspose.pdf/page/header/) { get; set; } | ページのヘッダーを取得または設定します。 |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | ページの最後の段落の後に段落を追加するかどうかを取得または設定します。 |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | レイヤーコレクションを取得または設定します。 |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | ページのメディアボックスを取得または設定します。 |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | ノートのためのラインスタイルを取得または設定します。（生成者のみ、ドキュメントを読み取るときは設定されません） |
| [Number](../../aspose.pdf/page/number/) { get; } | ページの番号を取得します。 |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | ページ情報を取得または設定します（生成者のみ、ドキュメントを読み取るときは設定されません）。 |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | 段落を取得します。 |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | ページの矩形を取得または設定します。取得時：指定されている場合はページのクロップボックスが返され、それ以外の場合はページのメディアボックスが返されます。設定時：ページのメディアボックスは常に設定されます。このプロパティはページの回転を考慮しないことに注意してください。回転を考慮したページの矩形を取得するには、ActualRect を使用してください。 |
| [Resources](../../aspose.pdf/page/resources/) { get; } | ページリソースを取得します。リソースオブジェクトには、画像、フォーム、フォントのコレクションが含まれています。 [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | ページの回転を取得または設定します。 |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | ページの変換行列を取得します。 |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | ページのタブ順序を取得または設定します。可能な値：Row、Column。デフォルト、Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | 目次情報を取得または設定します。 |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | ページのトリムボックスを取得または設定します。 |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | UserUnit 値を取得または設定します。デフォルトのユーザースペース単位のサイズを 1 / 72 インチの倍数で示す正の数です。デフォルト値は 1 です。このエントリをページでクリアするには、ゼロまたは負の値を設定してください。 |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | ページのウォーターマークを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | 注釈と連携する機能を提供する [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) ビジターオブジェクトを受け入れます。 |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | 画像配置オブジェクトと連携する機能を提供する [`ImagePlacementAbsorber`](../imageplacementabsorber/) ビジターオブジェクトを受け入れます。 |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | テキストオブジェクトと連携する機能を提供する [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) ビジターオブジェクトを受け入れます。 |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | テキストオブジェクトと連携する機能を提供する [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) ビジターオブジェクトを受け入れます。 |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | ページにグラフィックスを追加します。 [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/) メソッドで要素を1つずつ追加するよりも高速です。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保存します。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | ページに画像を追加し、指定された矩形の中央に配置して画像の比率を保存します。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | 検索可能な画像をページに追加し、指定された矩形の中央に配置して画像の比率を保存します。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | ページに画像を追加し、画像の矩形位置に基づいて配置します。 |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | ページにスタンプを追加します。スタンプはページ番号、画像、または単純なテキスト（例：ロゴ）です。 |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | 現在のページをビットマップとして変換し、バイトの配列を返します。 |
| [AsXml](../../aspose.pdf/page/asxml/)() | 現在のページを UTF-8 エンコーディングの XML として変換します。 |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | 可視マージンなしでコンテンツを含む矩形の bbox 値を計算します。 |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | DSR、OMR、OCR 画像ストリーム用にページを PNG に変換します。 |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | ページからグラフィックスを削除します。 [`Remove`](../../aspose.pdf.vector/graphicelement/remove/) メソッドで要素を1つずつ削除するよりも高速です。 |
| [Dispose](../../aspose.pdf/page/dispose/)() | メモリを解放します。 |
| [Flatten](../../aspose.pdf/page/flatten/)() | ページ上のすべてのフィールドを削除し、その値を代わりに配置します。 |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | キャッシュされたデータをクリアします。 |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | ページコンテンツに対する内部操作に関する通知を返します。（現在、テキスト追加シナリオにおける段落イベントに関する通知のみがサポートされています。） |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | CropBox（または CropBox が null の場合は MediaBox）に従ってページの矩形を返します。 |
| [GetResources](../../aspose.pdf/page/getresources/)() | ページに関連付けられたリソースを取得します。 |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | ページにベクターグラフィックスが存在するかどうかを検出します。 |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | ページが空であるかどうかのフラグを取得します。 |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | ページをグレースケールに変換します。 |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | ページ上のすべてのレイヤーを指定された新しいレイヤー名の単一のレイヤーにマージします。 |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | ページ上のすべてのレイヤーを指定された新しいレイヤー名とオプションのコンテンツグループ ID の単一のレイヤーにマージします。 |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | ページのサイズを変更します。 |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | 指定されたページデバイスで処理するためにページを送信します。 |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | 指定されたページデバイスで処理するためにページを送信します。 |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | ページのサイズを設定します。 |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | ページにベクターグラフィックスが存在する場合、それを保存しようとします。保存形式は SVG です。 |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | 整数値を対応する回転列挙メンバーに変換します。 |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | 回転列挙メンバーを整数値に変換します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | ヘッダーとフッターをカスタマイズするためのイベント。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | ヘッダーとフッターをカスタマイズするための手続き。 |

### 参照

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)