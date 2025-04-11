---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi garis
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## Metode PdfContentEditor.CreateLine

Membuat anotasi garis.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| x1 | Single | Koordinat horizontal awal dari garis. |
| y1 | Single | Koordinat vertikal awal dari garis. |
| x2 | Single | Koordinat horizontal akhir dari garis. |
| y2 | Single | Koordinat vertikal akhir dari garis. |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| border | Int32 | Lebar batas dalam poin. Jika nilai ini 0, tidak ada batas yang digambar. Nilai default adalah 1. |
| clr | Color | Warna garis. |
| borderStyle | String | Gaya batas yang menentukan lebar dan pola garis putus-putus yang akan digunakan dalam menggambar garis. Nilai ini bisa: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | Int32[] | Array garis putus-putus yang mendefinisikan pola garis putus-putus dan celah yang akan digunakan dalam menggambar batas putus-putus. Jika digunakan, borderSyle harus diatur sesuai dengan "D". |
| LEArray | String[] | Array dari dua nilai yang masing-masing menentukan gaya awal dan akhir dari garis yang digambar. Nilai dapat berupa: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)