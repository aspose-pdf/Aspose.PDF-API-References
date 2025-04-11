---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Tablo yöntemi. Bir DataView nesnesinin verilerini tabloya aktarır
type: docs
weight: 270
url: /tr/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView yöntemi

Bir DataView nesnesinin verilerini tabloya aktarır.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceDataView | DataView | Aktarılacak DataView nesnesi. |
| isColumnNamesImported | Boolean | Sütun adlarının ilk satır olarak aktarılıp aktarılmayacağını belirtir. |
| firstFilledRow | Int32 | Aktarmanın başlayacağı hedef tablodaki ilk hücrenin sıfır tabanlı satır numarası. Hedef tablo bu satırı içermiyorsa, bu satır (ve gerekirse tüm önceki satırlar) oluşturulacaktır. |
| firstFilledColumn | Int32 | Aktarmanın başlayacağı hedef tablodaki ilk hücrenin sıfır tabanlı sütun numarası. Hedef tablo, aktarım başlamadan önce bu sütunu içermelidir, aksi takdirde bir istisna fırlatılacaktır. |
| maxRows | Int32 | Kaynak dataview'den aktarılacak maksimum satır sayısı. |
| maxColumns | Int32 | Kaynak dataview'den aktarılacak maksimum sütun sayısı. |

### Ayrıca Bakınız

* sınıf [Table](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)