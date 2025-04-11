---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Tablo yöntemi. System.Data.DataTable'dan Aspose.Pdf.Table'a veri aktarır
type: docs
weight: 260
url: /tr/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

System.Data.DataTable'dan Aspose.Pdf.Table'a veri aktarır

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| importedDataTable | DataTable | System.Data.DataTable'ın kaynak örneği |
| isColumnNamesImported | Boolean | sütun adlarının ilk satır olarak aktarılıp aktarılmayacağını belirtir |
| firstFilledRow | Int32 | aktarımın başlayacağı hedef tablodaki ilk satırın sıfıra dayalı numarasını belirtir, eğer böyle bir numaraya sahip satır (ve bazı önceki satırlar) hedef tabloda yoksa, önce bunlar oluşturulacaktır |
| firstFilledColumn | Int32 | hedef tabloda ilk hedef sütunun numarasını belirtir, sütun aktarım başlamadan önce hedef tabloda mevcut olmalıdır |

### Ayrıca Bakınız

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Bir DataTable nesnesini tabloya aktarır.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| importedDataTable | DataTable | Aktarılacak DataTable nesnesi. |
| isColumnNamesShown | Boolean | kaynak veri tablosunun sütun adlarının ilk satır olarak aktarılıp aktarılmayacağını belirtir. |
| firstFilledRow | Int32 | aktarımın başlayacağı hedef tablodaki ilk satırın sıfıra dayalı numarasını belirtir, eğer böyle bir numaraya sahip satır (ve bazı önceki satırlar) hedef tabloda yoksa, önce bunlar oluşturulacaktır |
| firstFilledColumn | Byte | hedef tabloda ilk hedef sütunun numarasını belirtir, sütun aktarım başlamadan önce hedef tabloda mevcut olmalıdır |
| maxRows | Int32 | kaynak tablodan aktarılacak maksimum satır sayısı. |
| maxColumns | Int32 | kaynak tablodan aktarılacak maksimum sütun sayısı. |
| isHtmlSupported | Boolean | Metnin html dizesi olup olmadığını belirtir. |

### Ayrıca Bakınız

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Bir DataTable nesnesini, ancak bütün bir varlık olarak değil. Sadece belirtilen satırlar ve sütunlar aktarılır.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| importedDataTable | DataTable | Aktarılacak DataTable nesnesi. |
| sourceRowList | Int32[] | aktarılması gereken kaynak DataTable nesnesindeki satırların numaralarının dizisi. Liste null olmamalı ve yalnızca mevcut satır numaralarını içermelidir, aksi takdirde bir istisna fırlatılacaktır. |
| sourceColumnList | Int32[] | aktarılması gereken kaynak DataTable nesnesindeki sütunların numaralarının dizisi. Liste null olmamalı ve yalnızca mevcut sütun numaralarını içermelidir, aksi takdirde bir istisna fırlatılacaktır. |
| firstFilledRow | Int32 | aktarımın başlayacağı hedef tablodaki ilk hücrenin sıfıra dayalı satır numarası. Hedef tablo o satırı içermiyorsa, o (ve gerekirse tüm önceki) oluşturulacaktır |
| firstFilledColumn | Int32 | aktarımın başlayacağı hedef tablodaki ilk hücrenin sıfıra dayalı sütun numarası. Hedef tablo o sütunu içermelidir, aksi takdirde bir istisna fırlatılacaktır. |
| showColumnNamesAsFirstRow | Boolean | kaynak veri tablosunun sütun adlarının ilk satır olarak aktarılıp aktarılmayacağını belirtir. |
| isHtmlSupported | Boolean | Metnin html dizesi olup olmadığını belirtir. |

### Ayrıca Bakınız

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)