---
title: "PdfContentEditor.CreateLine"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat anotasi garis"
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

Membuat anotasi garis.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang menentukan lokasi anotasi pada halaman. |
| isi | String | Isi anotasi. |
| x1 | Single | Koordinat horizontal awal garis. |
| y1 | Single | Koordinat vertikal awal garis. |
| x2 | Single | Koordinat horizontal akhir garis. |
| y2 | Single | Koordinat vertikal akhir garis. |
| halaman | Int32 | Jumlah halaman asli tempat anotasi akan dibuat. |
| border | Int32 | Lebar border dalam poin. Jika nilai ini 0 tidak ada border yang digambar. Nilai default adalah 1. |
| clr | Color | Warna garis. |
| borderStyle | String | Gaya border yang menentukan lebar dan pola dash yang akan digunakan untuk menggambar garis. Nilai ini dapat: "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline). |
| dashArray | Int32[] | Array dash yang mendefinisikan pola dash dan celah yang akan digunakan untuk menggambar border dash. Jika digunakan, borderSyle harus disetel ke "D". |
| LEArray | String[] | Array dua nilai yang masing-masing menentukan gaya awal dan akhir garis gambar. Nilai dapat berupa: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


