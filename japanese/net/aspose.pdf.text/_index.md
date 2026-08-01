---
title: "Aspose.Pdf.Text"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text 名前空間は、ドキュメントからテキストを抽出したり、テキストを追加したり、既存のテキストを操作したりできるクラスを提供します。また、ドキュメントのフォントを抽出、置換、代替することができるクラスも含まれています。"
type: docs
weight: 250
url: /ja/net/aspose.pdf.text/
---
この **Aspose.Pdf.Text** 名前空間は、テキストを抽出し、テキストを追加し、document の既存テキストを操作できるクラスを提供します。また、フォントを抽出、置換、代替できるクラスも含まれています。

## クラス

| クラス | 説明 |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | ページ上に存在するテーブルのセルを表します |
| [AbsorbedRow](./absorbedrow/) | ページ上に存在するテーブルの行を表します |
| [AbsorbedTable](./absorbedtable/) | ページ上に存在するテーブルを表します |
| [CharInfo](./charinfo/) | 文字情報オブジェクトを表します。文字の位置情報を提供します。 |
| [CharInfoCollection](./charinfocollection/) | CharInfo オブジェクトのコレクションを表します。 |
| [CustomFontSubstitutionBase](./customfontsubstitutionbase/) | カスタムフォント置換戦略の基底クラスを表します。 |
| [FileFontSource](./filefontsource/) | 単一のフォントファイルソースを表します。 |
| [FolderFontSource](./folderfontsource/) | フォントファイルを含むフォルダーを表します。 |
| [Font](./font/) | フォントオブジェクトを表します。 |
| [FontAbsorber](./fontabsorber/) | フォントの吸収オブジェクトを表します。フォントの検索を実行し、検索結果へは[`Fonts`](../aspose.pdf.text/fontabsorber/fonts/)コレクションを介してアクセスできます。 |
| [FontCollection](./fontcollection/) | フォントコレクションを表します。 |
| [FontRepository](./fontrepository/) | フォント検索を実行します。システムにインストールされたフォントと標準 PDF フォントを検索します。また、カスタムフォントを開く機能も提供します。 |
| [FontSource](./fontsource/) | フォントソースの基底クラスを表します。 |
| [FontSourceCollection](./fontsourcecollection/) | フォントソースのコレクションを表します。 |
| [FontSubstitution](./fontsubstitution/) | フォント置換戦略の基底クラスを表します。 |
| [FontSubstitutionCollection](./fontsubstitutioncollection/) | フォント置換戦略のコレクションを表します。 |
| [MarkupParagraph](./markupparagraph/) | 段落を表します。 |
| [MarkupSection](./markupsection/) | マークアップセクションを表します - テキストを含み、他のテキストブロックと視覚的に分割できるページ上の矩形領域です。 |
| [MemoryFontSource](./memoryfontsource/) | 単一のフォントファイルソースを表します。 |
| [PageMarkup](./pagemarkup/) | ページのマークアップは[`MarkupSection`](../aspose.pdf.text/markupsection/) と [`MarkupParagraph`](../aspose.pdf.text/markupparagraph/) のコレクションで表されます。 |
| [ParagraphAbsorber](./paragraphabsorber/) | セクションや段落などのページ構造オブジェクトの吸収オブジェクトを表します。テキストのセクションと段落を検索し、テキスト座標空間でそれらを記述する矩形や多角形へのアクセスを提供します。また、テキストセグメントの検索を実行し、構造要素でグループ化された !:TextFragments コレクションを介して検索結果へアクセスできます。 |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | [`ParagraphAbsorber`](../aspose.pdf.text/paragraphabsorber/) のオプションを表します。 |
| [Position](./position/) | 位置オブジェクトを表します。 |
| [RegexManager](./regexmanager/) | 構成可能なタイムアウト設定を持つ正規表現操作のラッパーを提供します。 |
| [SimpleFontSubstitution](./simplefontsubstitution/) | シンプルなフォント置換戦略のクラスを表します。 |
| [SystemFontSource](./systemfontsource/) | システムにインストールされているすべてのフォントを表します。 |
| [SystemFontsSubstitution](./systemfontssubstitution/) | フォントをシステムフォントに置き換えるフォント置換戦略のクラスを表します。 |
| [TableAbsorber](./tableabsorber/) | テーブル要素の吸収オブジェクトを表します。検索を実行し、[`TableList`](../aspose.pdf.text/tableabsorber/tablelist/) コレクションを介して検索結果へのアクセスを提供します。 |
| [TabStop](./tabstop/) | 段落内のカスタムタブストップ位置を表します。 |
| [TabStops](./tabstops/) | [`TabStop`](../aspose.pdf.text/tabstop/) オブジェクトのコレクションを表します。 |
| [TextAbsorber](./textabsorber/) | テキストの吸収オブジェクトを表します。テキスト抽出を実行し、[`Text`](../aspose.pdf.text/textabsorber/text/) オブジェクトを介して結果へのアクセスを提供します。 |
| [TextBuilder](./textbuilder/) | テキストオブジェクトを Pdf ページに追加します。 |
| [TextEditOptions](./texteditoptions/) | テキスト編集操作のオプションを記述します。 |
| [TextExtractionError](./textextractionerror/) | PDF ドキュメントにテキスト抽出エラーが発生したことを記述します。 |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | テキスト抽出エラーが発生した PDF ドキュメント内の位置を表します。 |
| [TextExtractionOptions](./textextractionoptions/) | テキスト抽出オプションを表します。 |
| [TextFormattingOptions](./textformattingoptions/) | テキスト書式設定オプションを表します。 |
| [TextFragment](./textfragment/) | Pdf テキストのフラグメントを表します。 |
| [TextFragmentAbsorber](./textfragmentabsorber/) | テキストフラグメントの吸収オブジェクトを表します。テキスト検索を実行し、[`TextFragments`](../aspose.pdf.text/textfragmentabsorber/textfragments/) コレクションを介して検索結果へのアクセスを提供します。 |
| [TextFragmentCollection](./textfragmentcollection/) | テキストフラグメントのコレクションを表します。 |
| [TextFragmentState](./textfragmentstate/) | テキストフラグメントのテキスト状態を表します。 |
| [TextOptions](./textoptions/) | テキスト処理オプションを表します。 |
| [TextParagraph](./textparagraph/) | テキスト段落を複数行テキストオブジェクトとして表します。 |
| [TextReplaceOptions](./textreplaceoptions/) | テキスト置換オプションを表します。 |
| [TextSearchOptions](./textsearchoptions/) | テキスト検索オプションを表します。 |
| [TextSegment](./textsegment/) | Pdf テキストのセグメントを表します。 |
| [TextSegmentCollection](./textsegmentcollection/) | テキストセグメントのコレクションを表します |
| [TextState](./textstate/) | テキストの状態を表します |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IFontOptions](./ifontoptions/) | フォントの動作を調整するための便利なプロパティ |
| [ITableElement](./itableelement/) | このインターフェイスは、TableAbsorber によって抽出された既存のテーブルの要素を表します。 |
## 列挙体

| 列挙体 | 説明 |
| --- | --- |
| [CoordinateOrigin](./coordinateorigin/) | テキスト CoordinateOrigin 列挙体。 |
| [FontStyles](./fontstyles/) | テキストに適用されるスタイル情報を指定します。 |
| [FontTypes](./fonttypes/) | サポートされているフォントタイプの列挙体。 |
| [SubstitutionFontCategories](./substitutionfontcategories/) | 置き換えることができるフォントカテゴリを表します。 |
| [TabAlignmentType](./tabalignmenttype/) | タブの配置タイプを列挙します。 |
| [TabLeaderType](./tableadertype/) | タブリーダーのタイプを列挙します。 |
| [TextRenderingMode](./textrenderingmode/) | テキスト描画モード（Tmode）は、テキストを表示する際にグリフの輪郭をストロークするか、塗りつぶすか、クリッピング境界として使用するか、またはこれら三つの組み合わせのいずれかになるかを決定します。 |


