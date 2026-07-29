---
title: "TextDevice"
linktitle: "TextDevice"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> PDF ドキュメントのページをテキストに変換するクラスを表します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 Document doc = new.</pre>"
type: docs
weight: 190
url: /ja/java/com.aspose.pdf.devices/textdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.TextDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.TextDevice

```
public final class TextDevice extends PageDevice
```

<p> PDF ドキュメントのページをテキストに変換するクラスを表します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> {@code TextDevice} オブジェクトは基本的に PDF ページからテキストを抽出するために使用されます。 </p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextDevice](#TextDevice--) | Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。 |
| [TextDevice](#TextDevice-java.nio.charset.Charset-) | Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。 |
| [TextDevice](#TextDevice-com.aspose.pdf.TextEncodingInternal-) | Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。 |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-) | Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。 |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-) | Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。 |
| [TextDevice](#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-) | Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEncoding](#getEncoding--) | <p> 抽出されたテキストのエンコーディングを取得します。 </p> |
| [getEncodingInternal](#getEncodingInternal--) | <p> 抽出されたテキストのエンコーディングを取得します。 </p> |
| [getExtractionOptions](#getExtractionOptions--) | <p> テキスト抽出オプションを取得します。 </p> |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | <p> ページを変換し、テキストストリームとして保存します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre> |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | ページを変換し、テキストストリームとして保存します。 |
| [setEncoding](#setEncoding-java.nio.charset.Charset-) | 抽出されたテキストのエンコーディングを設定します。 |
| [setEncodingInternal](#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-) | <p> 抽出されたテキストのエンコーディングを設定します。 </p> |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> テキスト抽出オプションを設定します。 </p> |

### TextDevice {#TextDevice--}
```
public TextDevice()
```

Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。

### TextDevice {#TextDevice-java.nio.charset.Charset-}
Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。

### TextDevice {#TextDevice-com.aspose.pdf.TextEncodingInternal-}
Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-}
Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-java.nio.charset.Charset-}
Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。

### TextDevice {#TextDevice-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextEncodingInternal-}
Raw テキストフォーマットモードと Unicode テキストエンコーディングを使用して、{@code TextDevice} の新しいインスタンスを初期化します。

### getEncoding {#getEncoding--}
```
public Charset getEncoding()
```

<p> 抽出されたテキストのエンコーディングを取得します。 </p>

**Returns:**
文字セット要素 <hr> <pre> この例は、抽出されたテキストを UTF-8 エンコーディングで表現する方法を示しています。 Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName(\"UTF-8\")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getEncodingInternal {#getEncodingInternal--}
```
public TextEncodingInternal getEncodingInternal()
```

<p> 抽出されたテキストのエンコーディングを取得します。 </p>

**Returns:**
TextEncodingInternal 要素 <hr> <pre> この例は、抽出されたテキストを UTF-8 エンコーディングで表現する方法を示しています。 Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(java.nio.charset.Charset.forName(\"UTF-8\")); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> テキスト抽出オプションを取得します。 </p>

**Returns:**
TextExtractionOptions 要素 <hr> <pre> この例は、生の順序でテキストを抽出する方法を示しています。 Document doc = new Document(inFile); String extractedText; // create text device TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw)); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), outFile); </pre>

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
<p> ページを変換し、テキストストリームとして保存します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); // create text device TextDevice device = new TextDevice(); // convert the page and save text to the stream device.process(doc.getPages().get_Item(1), ms); // use the extracted text extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); </pre>

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
ページを変換し、テキストストリームとして保存します。

### setEncoding {#setEncoding-java.nio.charset.Charset-}
抽出されたテキストのエンコーディングを設定します。

### setEncodingInternal {#setEncodingInternal-com.aspose.pdf.TextEncodingInternal-}
<p> 抽出されたテキストのエンコーディングを設定します。 </p>

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> テキスト抽出オプションを設定します。 </p>
