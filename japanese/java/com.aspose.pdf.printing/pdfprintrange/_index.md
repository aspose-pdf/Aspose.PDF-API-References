---
title: "PdfPrintRange"
linktitle: "PdfPrintRange"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "印刷するドキュメントの部分を指定します。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf.printing/pdfprintrange/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrintRange

```
public final class PdfPrintRange extends Object
```

印刷するドキュメントの部分を指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [AllPages](#AllPages) | すべてのページが印刷されます。 |
| [CurrentPage](#CurrentPage) | 現在表示されているページが印刷されます |
| [Selection](#Selection) | 選択されたページが印刷されます。 |
| [SomePages](#SomePages) | FromPage と ToPage の間のページが印刷されます。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfPrintRange](#PdfPrintRange--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNames](#getNames--) | PdfPrintRange の文字列名を取得 |
| [toString](#toString-int-) | PdfPrintRange 要素の文字列名を取得 |

### AllPages {#AllPages}
```
public static final int AllPages
```

すべてのページが印刷されます。

### CurrentPage {#CurrentPage}
```
public static final int CurrentPage
```

現在表示されているページが印刷されます

### Selection {#Selection}
```
public static final int Selection
```

選択されたページが印刷されます。

### SomePages {#SomePages}
```
public static final int SomePages
```

FromPage と ToPage の間のページが印刷されます。

### PdfPrintRange {#PdfPrintRange--}
```
public PdfPrintRange()
```



### getNames {#getNames--}
```
public static String [] getNames()
```

PdfPrintRange の文字列名を取得

**Returns:**
String[] オブジェクト

### toString {#toString-int-}
```
public static String toString(int pdfPrintRange)
```

PdfPrintRange 要素の文字列名を取得

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfPrintRange |  | PdfPrintRange 要素 |

**Returns:**
文字列オブジェクト @see PdfPrintRange
