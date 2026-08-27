---
title: "Document.Convert"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document メソッド。ドキュメントを変換し、エラーを指定されたファイルに保存します。"
type: docs
weight: 600
url: /ja/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Document を変換し、エラーを指定されたファイルに保存します。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputLogFileName | String | コメントが保存されるファイルへのパス。 |
| フォーマット | PdfFormat | PDF フォーマット。 |
| アクション | ConvertErrorAction | 変換できないオブジェクトに対するアクション |
| transparencyAction | ConvertTransparencyAction | 画像マスクオブジェクトに対するアクション。 |

### 戻り値

操作結果。

### 関連項目

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Document を変換し、エラーを指定されたファイルに保存します。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputLogStream | Stream | コメントが保存されるストリーム。 |
| フォーマット | PdfFormat | PDF フォーマット。 |
| アクション | ConvertErrorAction | 変換できないオブジェクトに対するアクション |
| transparencyAction | ConvertTransparencyAction | 画像マスクオブジェクトに対するアクション。 |

### 戻り値

操作結果。

### 関連項目

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Document を変換し、エラーを指定されたファイルに保存します。

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputLogFileName | String | コメントが保存されるファイルへのパス。 |
| フォーマット | PdfFormat | PDF フォーマット。 |
| アクション | ConvertErrorAction | 変換できないオブジェクトに対するアクション |

### 戻り値

操作結果。

### 関連項目

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

指定された変換オプションを使用して Document を変換します

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| オプション | PdfFormatConversionOptions | PDF ドキュメントを変換するためのオプションのセット。 |

### 戻り値

操作結果。

### 関連項目

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Document 内の画像を認識し、hocr 文字列を上に追加します。

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | hocr 認識で処理される画像に対するアクション。 |
| flattenImages | Boolean | PDF 画像内のテキストはマスクのメカニズムを使用して描画でき、その場合画像はフラット化する必要があります。 |

### 戻り値

操作結果。ドキュメントに画像がない場合は !:false を返します。

### 関連項目

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Document 内の画像を認識し、hocr 文字列を上に追加します。

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| callback | CallBackGetHocr | hocr 認識で処理される画像に対するアクション。 |
| flattenImages | Boolean | PDF 画像内のテキストはマスクのメカニズムを使用して描画でき、その場合画像はフラット化する必要があります。 |

### 戻り値

操作結果。ドキュメントに画像がない場合は !:false を返します。

### 関連項目

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Document を変換し、エラーを指定されたストリームに保存します。

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputLogStream | Stream | コメントが保存されるストリーム。 |
| フォーマット | PdfFormat | PDF フォーマット。 |
| アクション | ConvertErrorAction | 変換できないオブジェクトに対するアクション |

### 戻り値

操作結果。

### 関連項目

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Fixup を適用して Document を変換します。

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fixup | Fixup | Fixup のタイプです。 |
| outputLog | Stream | プロセスのログです。 |
| onlyValidation | Boolean | ドキュメントの検証のみです。 |
| パラメータ | Object[] | 設定できない Fixup のプロパティです。 |

### 戻り値

操作結果です。

### 関連項目

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Fixup を適用して Document を変換します。

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fixup | Fixup | Fixup のタイプです。 |
| outputLog | String | プロセスのログです。 |
| onlyValidation | Boolean | ドキュメントの検証のみです。 |
| パラメータ | Object[] | 設定できない Fixup のプロパティです。 |

### 戻り値

操作結果です。

### 関連項目

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

ソース形式のソースファイルをデスティネーション形式のデスティネーションファイルに変換します。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcFileName | String | ソースファイル名です。 |
| loadOptions | LoadOptions | ソースファイル形式です。 |
| dstFileName | String | 宛先ファイル名です。 |
| saveOptions | SaveOptions | 宛先ファイル形式です。 |

### 関連項目

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

ストリームをソース形式からデスティネーション形式のデスティネーションファイルに変換します。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcStream | Stream | ソースストリームです。 |
| loadOptions | LoadOptions | ソースストリーム形式です。 |
| dstFileName | String | 宛先ファイル名です。 |
| saveOptions | SaveOptions | 宛先ファイル形式です。 |

### 関連項目

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

ソース形式のソースファイルをデスティネーション形式のストリームに変換します。

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcFileName | String | ソースファイル名です。 |
| loadOptions | LoadOptions | ソースファイル形式です。 |
| dstStream | Stream | 宛先ストリームです。 |
| saveOptions | SaveOptions | 宛先ストリーム形式です。 |

### 関連項目

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

ストリームをソース形式からデスティネーション形式のストリームに変換します。

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcStream | Stream | ソースストリームです。 |
| loadOptions | LoadOptions | ソースストリーム形式です。 |
| dstStream | Stream | 宛先ストリームです。 |
| saveOptions | SaveOptions | 宛先ファイル形式です。 |

### 関連項目

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


