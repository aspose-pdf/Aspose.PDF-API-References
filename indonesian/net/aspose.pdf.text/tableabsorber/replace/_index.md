---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: Metode TableAbsorber. Mengganti AbsorbedTable dengan Table di halaman
type: docs
weight: 60
url: /id/net/aspose.pdf.text/tableabsorber/replace/
---
## Metode TableAbsorber.Replace

Mengganti [`AbsorbedTable`](../../absorbedtable/) dengan [`Table`](../../../aspose.pdf/table/) di halaman.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Halaman | Objek halaman dokumen Pdf. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) yang akan diganti. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) untuk mengganti tabel lama. |

## Catatan

Harap diperhatikan bahwa ini mengubah koleksi TableList. Jika menghapus/mengganti tabel dalam loop, harap gunakan salinan koleksi TableList.

### Lihat Juga

* kelas [Page](../../../aspose.pdf/page/)
* kelas [AbsorbedTable](../../absorbedtable/)
* kelas [Table](../../../aspose.pdf/table/)
* kelas [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)