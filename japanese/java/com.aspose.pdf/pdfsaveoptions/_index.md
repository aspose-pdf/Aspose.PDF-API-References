---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF 形式へのエクスポート用の保存オプション"
type: docs
weight: 3790
url: /ja/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

PDF 形式へのエクスポート用の保存オプション

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | コンピュータに存在しないフォントに対してデフォルトで使用されるフォント名。PDF に保存される際に、文書自体やデバイスに存在しないフォントが含まれている場合、API はこれらのフォントをデフォルトフォントに置き換えます（デバイス上に {@code DefaultFontName} が見つかった場合）。 |
| [getTempPath](#getTempPath--) | 一時ファイルのパス。 |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | コンピュータに存在しないフォントに対してデフォルトで使用されるフォント名。PDF に保存される際に、文書自体やデバイスに存在しないフォントが含まれている場合、API はこれらのフォントをデフォルトフォントに置き換えます（デバイス上に {@code DefaultFontName} が見つかった場合）。 |
| [setTempPath](#setTempPath-java.lang.String-) | 一時ファイルのパス。 |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

コンストラクタ

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

コンピュータに存在しないフォントに対してデフォルトで使用されるフォント名。PDF に保存される際に、文書自体やデバイスに存在しないフォントが含まれている場合、API はこれらのフォントをデフォルトフォントに置き換えます（デバイス上に {@code DefaultFontName} が見つかった場合）。

**Returns:**
文字列値

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

一時ファイルのパス。

**Returns:**
文字列値

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
コンピュータに存在しないフォントに対してデフォルトで使用されるフォント名。PDF に保存される際に、文書自体やデバイスに存在しないフォントが含まれている場合、API はこれらのフォントをデフォルトフォントに置き換えます（デバイス上に {@code DefaultFontName} が見つかった場合）。

### setTempPath {#setTempPath-java.lang.String-}
一時ファイルのパス。
