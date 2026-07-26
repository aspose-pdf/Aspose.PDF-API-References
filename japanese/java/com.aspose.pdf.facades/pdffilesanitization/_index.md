---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "サニタイズおよびリカバリ API を表します。他の方法でドキュメントを作成/開くことができない場合に使用してください。"
type: docs
weight: 510
url: /ja/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

サニタイズおよびリカバリ API を表します。他の方法でドキュメントを作成/開くことができない場合に使用してください。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | 新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.io.InputStream-) | サニタイズ用に Pdf ストリームをバインドします。 |
| [bindPdf](#bindPdf-java.lang.String-) | サニタイズ用に Pdf ファイルをバインドします。 |
| [close](#close--) | ファサードを閉じます。 |
| [getLog](#getLog--) | ファイルが保存された後、ファイルで何が行われたかを確認できます。 |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | ドキュメント用に新しい xref とトレーラを生成できるようにします。 |
| [getUseTrimBottom](#getUseTrimBottom--) | pdf データの後のデータを削除できるようにします。 |
| [getUseTrimTop](#getUseTrimTop--) | pdf データの前のデータを削除できるようにします。 |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | 古い xref とトレーラを削除し、新しい xref とトレーラを作成します。 |
| [recover](#recover--) | ドキュメントを復元します。プロパティを使用してカスタマイズしてください。 |
| [save](#save-java.io.OutputStream-) | 結果の PDF をストリームに保存します。 |
| [save](#save-java.lang.String-) | 結果の PDF をファイルに保存します。 |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | ドキュメント用に新しい xref とトレーラを生成できるようにします。 |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | pdf データの後のデータを削除できるようにします。 |
| [setUseTrimTop](#setUseTrimTop-boolean-) | pdf データの前のデータを削除できるようにします。 |
| [trimBottom](#trimBottom--) | 最後の %%EOF の後のデータを削除します。 |
| [trimTop](#trimTop--) | %PDF の前のデータを削除します。 |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

新しいインスタンスを初期化します。

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.io.InputStream-}
サニタイズ用に Pdf ストリームをバインドします。

### bindPdf {#bindPdf-java.lang.String-}
サニタイズ用に Pdf ファイルをバインドします。

### close {#close--}
```
public void close()
```

ファサードを閉じます。

### getLog {#getLog--}
```
public final List < String > getLog()
```

ファイルが保存された後、ファイルで何が行われたかを確認できます。

**Returns:**
String 要素のリスト

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

ドキュメント用に新しい xref とトレーラを生成できるようにします。

**Returns:**
ブール値

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

pdf データの後のデータを削除できるようにします。

**Returns:**
ブール値

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

pdf データの前のデータを削除できるようにします。

**Returns:**
ブール値

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

古い xref とトレーラを削除し、新しい xref とトレーラを作成します。

### recover {#recover--}
```
public final void recover()
```

ドキュメントを復元します。プロパティを使用してカスタマイズしてください。

### save {#save-java.io.OutputStream-}
結果の PDF をストリームに保存します。

### save {#save-java.lang.String-}
結果の PDF をファイルに保存します。

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

ドキュメント用に新しい xref とトレーラを生成できるようにします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

pdf データの後のデータを削除できるようにします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

pdf データの前のデータを削除できるようにします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

最後の %%EOF の後のデータを削除します。

### trimTop {#trimTop--}
```
public final void trimTop()
```

%PDF の前のデータを削除します。
