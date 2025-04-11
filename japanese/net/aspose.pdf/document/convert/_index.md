---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントメソッド。ドキュメントを変換し、エラーを指定されたファイルに保存します
type: docs
weight: 580
url: /ja/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

ドキュメントを変換し、エラーを指定されたファイルに保存します。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputLogFileName | String | コメントが保存されるファイルへのパス。 |
| format | PdfFormat | PDFフォーマット。 |
| action | ConvertErrorAction | 変換できないオブジェクトに対するアクション |
| transparencyAction | ConvertTransparencyAction | 画像マスクオブジェクトに対するアクション |

### 戻り値

操作結果

### 参照

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

ドキュメントを変換し、エラーを指定されたファイルに保存します。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputLogStream | Stream | コメントが保存されるストリーム。 |
| format | PdfFormat | PDFフォーマット。 |
| action | ConvertErrorAction | 変換できないオブジェクトに対するアクション |
| transparencyAction | ConvertTransparencyAction | 画像マスクオブジェクトに対するアクション |

### 戻り値

操作結果

### 参照

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

ドキュメントを変換し、エラーを指定されたファイルに保存します。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputLogFileName | String | コメントが保存されるファイルへのパス。 |
| format | PdfFormat | PDFフォーマット。 |
| action | ConvertErrorAction | 変換できないオブジェクトに対するアクション |

### 戻り値

操作結果

### 参照

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

指定された変換オプションを使用してドキュメントを変換します。

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | PdfFormatConversionOptions | PDFドキュメントを変換するためのオプションのセット |

### 戻り値

操作結果

### 参照

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

ドキュメント内の画像を認識し、その上にhocr文字列を追加します。

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | hocr認識によって処理される画像に対するアクション。 |
| flattenImages | Boolean | PDF画像内のテキストはマスクのメカニズムを使用して描画される可能性があるため、その場合は画像をフラット化する必要があります。 |

### 戻り値

操作結果。ドキュメントに画像がない場合は !:false を返します。

### 参照

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

ドキュメント内の画像を認識し、その上にhocr文字列を追加します。

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| callback | CallBackGetHocr | hocr認識によって処理される画像に対するアクション。 |
| flattenImages | Boolean | PDF画像内のテキストはマスクのメカニズムを使用して描画される可能性があるため、その場合は画像をフラット化する必要があります。 |

### 戻り値

操作結果。ドキュメントに画像がない場合は !:false を返します。

### 参照

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

ドキュメントを変換し、エラーを指定されたストリームに保存します。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputLogStream | Stream | コメントが保存されるストリーム。 |
| format | PdfFormat | PDFフォーマット。 |
| action | ConvertErrorAction | 変換できないオブジェクトに対するアクション |

### 戻り値

操作結果

### 参照

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Fixupを適用してドキュメントを変換します。

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fixup | Fixup | Fixupタイプ。 |
| outputLog | Stream | プロセスのログ。 |
| onlyValidation | Boolean | ドキュメントの検証のみ。 |
| parameters | Object[] | 設定できないFixupのプロパティ。 |

### 戻り値

操作結果。

### 参照

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Fixupを適用してドキュメントを変換します。

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fixup | Fixup | Fixupタイプ。 |
| outputLog | String | プロセスのログ。 |
| onlyValidation | Boolean | ドキュメントの検証のみ。 |
| parameters | Object[] | 設定できないFixupのプロパティ。 |

### 戻り値

操作結果。

### 参照

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

ソースファイルをソースフォーマットからデスティネーションファイルのデスティネーションフォーマットに変換します。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcFileName | String | ソースファイル名。 |
| loadOptions | LoadOptions | ソースファイルフォーマット。 |
| dstFileName | String | デスティネーションファイル名。 |
| saveOptions | SaveOptions | デスティネーションファイルフォーマット。 |

### 参照

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

ソースフォーマットのストリームをデスティネーションファイルのデスティネーションフォーマットに変換します。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcStream | Stream | ソースストリーム。 |
| loadOptions | LoadOptions | ソースストリームフォーマット。 |
| dstFileName | String | デスティネーションファイル名。 |
| saveOptions | SaveOptions | デスティネーションファイルフォーマット。 |

### 参照

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

ソースファイルをソースフォーマットからデスティネーションストリームのデスティネーションフォーマットに変換します。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcFileName | String | ソースファイル名。 |
| loadOptions | LoadOptions | ソースファイルフォーマット。 |
| dstStream | Stream | デスティネーションストリーム。 |
| saveOptions | SaveOptions | デスティネーションストリームフォーマット。 |

### 参照

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

ソースフォーマットのストリームをデスティネーションフォーマットのストリームに変換します。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcStream | Stream | ソースストリーム。 |
| loadOptions | LoadOptions | ソースストリームフォーマット。 |
| dstStream | Stream | デスティネーションストリーム。 |
| saveOptions | SaveOptions | デスティネーションファイルフォーマット。 |

### 参照

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)