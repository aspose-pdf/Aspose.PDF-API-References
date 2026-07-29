---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "com.aspose.pdf.devices パッケージは、ドキュメントを画像またはプレーンテキストとして表現するために使用されるクラスを提供します。"
type: docs
weight: 140
url: /ja/java/com.aspose.pdf.devices/
---
com.aspose.pdf.devices パッケージは、ドキュメントを画像またはプレーンテキストとして表現するために使用されるクラスを提供します。

## クラス

| クラス | 説明 |
| --- | --- |
| [BmpDevice](./bmpdevice/) | PDF ドキュメントのページを BMP 形式で保存するのに役立つ画像デバイスを表します。 |
| [Device](./device/) | すべてのデバイスタイプの抽象クラスです。デバイスは PDF ドキュメントをある形式で表すために使用されます。たとえば、ドキュメントページは画像またはテキストとして表現できます。 |
| [DicomDevice](./dicomdevice/) | PDF ドキュメントのページを DICOM 形式で保存するのに役立つ画像デバイスを表します。 |
| [DocumentDevice](./documentdevice/) | PDF ドキュメント全体を処理するために使用されるすべてのデバイスの抽象クラスです。 |
| [EmfDevice](./emfdevice/) | PDF ドキュメントのページを EMF 形式で保存するのに役立つ画像デバイスを表します。 |
| [FormPresentationMode](./formpresentationmode/) | 印刷時または PDF ドキュメントを画像に変換する際のフォーム表示モードを指定するために使用されます。 |
| [GifDevice](./gifdevice/) | PDF ドキュメントのページを GIF 形式で保存するのに役立つ画像デバイスを表します。 |
| [GraphicsDevice](./graphicsdevice/) | PDF ドキュメントのページをグラフィックにレンダリングするのに役立つ画像デバイスを表します。 |
| [ImageDevice](./imagedevice/) | 画像デバイス用の抽象クラスです。 |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | PDF ドキュメントのページを JPEG 形式で保存するのに役立つ画像デバイスを表します。 |
| [Margins](./margins/) | このクラスは画像の余白を表します。 |
| [PageDevice](./pagedevice/) | PDF ドキュメントの特定のページを処理するために使用されるすべてのデバイスの抽象クラスです。 |
| [PngDevice](./pngdevice/) | PDF ドキュメントのページを PNG 形式で保存するのに役立つ画像デバイスを表します。 |
| [Resolution](./resolution/) | 画像解像度を保持するクラスを表します。 |
| [TextDevice](./textdevice/) | <p> PDF ドキュメントのページをテキストに変換するクラスを表します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> {@code TextDevice} オブジェクトは基本的に PDF ページからテキストを抽出するために使用されます。 </p> |
| [ThumbnailDevice](./thumbnaildevice/) | PDF ドキュメントのページをサムネイル画像として保存する画像デバイスを表します。 |
| [TiffDevice](./tiffdevice/) | このクラスは、PDF ドキュメントのページを 1 つの TIFF 画像にページごとに保存するのに役立ちます。 |
| [TiffSettings](./tiffsettings/) | このクラスは PDF を TIFF にインポートするための設定を表します。 |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | インデックス変換タイプを表すクラス |
## Enums

| 列挙型 | 説明 |
| --- | --- |
| [ColorDepth](./colordepth/) | Tiff 画像デバイスに渡されるパラメータ値を指定するために使用されます。 |
| [CompressionType](./compressiontype/) | Tiff 画像デバイスに渡されるパラメータ値を指定するために使用されます。 |
| [ShapeType](./shapetype/) | この列挙型は抽出された画像の形状タイプを表します。 |
