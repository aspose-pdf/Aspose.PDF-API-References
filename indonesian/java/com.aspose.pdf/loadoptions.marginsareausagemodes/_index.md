---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili mode penggunaan area margin selama konversi (seperti HTML, EPUB, dll), mendefinisikan penanganan instruksi format yang diimpor terkait penggunaan margin."
type: docs
weight: 2800
url: /id/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Mewakili mode penggunaan area margin selama konversi (seperti HTML, EPUB, dll), mendefinisikan penanganan instruksi format yang diimpor terkait penggunaan margin.

## Fields

| Field | Deskripsi |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | Mode ini secara ketat melarang penggunaan area margin, sehingga konverter tidak akan pernah menggunakan area margin untuk rendering, bahkan jika CSS atau format dokumen sumber mengizinkan atau memerlukannya. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | Dalam mode ini konverter mematuhi format dokumen yang diimpor (mis. CSS dari HTML yang diimpor) dalam penggunaan area margin. Jadi, jika format dokumen yang diimpor memerlukan penggunaan area margin untuk rendering, konverter akan mengizinkannya. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

Mode ini secara ketat melarang penggunaan area margin, sehingga konverter tidak akan pernah menggunakan area margin untuk rendering, bahkan jika CSS atau format dokumen sumber mengizinkan atau memerlukannya.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

Dalam mode ini konverter mematuhi format dokumen yang diimpor (mis. CSS dari HTML yang diimpor) dalam penggunaan area margin. Jadi, jika format dokumen yang diimpor memerlukan penggunaan area margin untuk rendering, konverter akan mengizinkannya.
