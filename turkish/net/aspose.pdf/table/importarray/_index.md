---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: Tablo yöntemi. Tek boyutlu veri dizisini tabloya aktarır. Aktarım, her dizinin öğesi için bir hücre alır ve parametrelerde tanımlanan satır ve sütundan başlar. Aktarım sırasında gerekli satırların hala mevcut olmadığı tespit edilirse (yani hedef tablo tüm verileri almak için çok küçükse), gerekli satırlar oluşturulacaktır.
type: docs
weight: 250
url: /tr/net/aspose.pdf/table/importarray/
---
## Table.ImportArray yöntemi

Tek boyutlu veri dizisini tabloya aktarır. Aktarım, her dizinin öğesi için bir hücre alır ve parametrelerde tanımlanan satır ve sütundan başlar. Aktarım sırasında, gerekli satırların hala mevcut olmadığı tespit edilirse (yani hedef tablo tüm verileri almak için çok küçükse), gerekli satırlar oluşturulacaktır.

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| importedArray | Object[] | aktarılan veri, null değerler boş dizeler olarak aktarılacaktır |
| firstFilledRow | Int32 | aktarımın başlayacağı hedef tablodaki ilk hedef satırın numarasını tanımlar. Hedef tablodaki satır sayısı gerekli olandan azsa, eksik satırlar önce oluşturulacaktır. |
| firstFilledColumn | Int32 | hedef tablodaki ilk hedef sütunun numarasını belirtir, sütun aktarım başlamadan önce hedef tabloda mevcut olmalıdır |
| isLeftColumnsFilled | Boolean | 'isLeftColumnsFilled'=false ise, ikinci ve tüm sonraki doldurulmuş satırlarda firstFilledColumn'un solundaki hücreler atlanacaktır |

### Ayrıca Bakınız

* sınıf [Table](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)