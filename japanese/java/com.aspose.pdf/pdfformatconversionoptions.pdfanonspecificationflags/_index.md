---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは、ソース PDF ドキュメントが PDF 仕様に合致しない場合の PDF/A 変換を制御するフラグを保持します。このクラスのフラグが使用されると、変換が減少します。"
type: docs
weight: 3740
url: /ja/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

このクラスは、ソース PDF ドキュメントが PDF 仕様に準拠していない場合の PDF/A 変換を制御するフラグを保持します。これらのフラグを使用するとパフォーマンスが低下しますが、通常の方法でソース PDF ドキュメントを PDF/A 形式に変換できない場合に必要です。デフォルトではすべてのフラグが false に設定されています。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | 一部の PDF ドキュメントには、内部データで名前が異なるフォントが含まれています。このフラグを使用すると、BaseFont フィールドと FontDescriptor.FontName フィールドが異なる場合の特別な処理ロジックが強制されます。 |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | 一部の PDF ドキュメントには、内部データで名前が異なるフォントが含まれています。このフラグを使用すると、BaseFont フィールドと FontDescriptor.FontName フィールドが異なる場合の特別な処理ロジックが強制されます。 |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

コンストラクタ

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

一部の PDF ドキュメントには、内部データで名前が異なるフォントが含まれています。このフラグを使用すると、BaseFont フィールドと FontDescriptor.FontName フィールドが異なる場合の特別な処理ロジックが強制されます。

**Returns:**
ブール値

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

一部の PDF ドキュメントには、内部データで名前が異なるフォントが含まれています。このフラグを使用すると、BaseFont フィールドと FontDescriptor.FontName フィールドが異なる場合の特別な処理ロジックが強制されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
