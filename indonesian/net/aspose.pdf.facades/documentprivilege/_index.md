---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.DocumentPrivilege. Mewakili hak akses untuk mengakses file Pdf. Lihat PdfFileSecurity. Ada 4 cara menggunakan kelas ini 1. Menggunakan hak akses yang telah ditentukan sebelumnya secara langsung. 2. Berdasarkan hak akses yang telah ditentukan sebelumnya dan mengubah beberapa izin spesifik. 3. Berdasarkan hak akses yang telah ditentukan sebelumnya dan mengubah beberapa kombinasi izin Adobe Professional yang spesifik. 4. Menggabungkan cara 2 dan cara 3
type: docs
weight: 4230
url: /id/net/aspose.pdf.facades/documentprivilege/
---
## Kelas DocumentPrivilege

Mewakili hak akses untuk mengakses file Pdf. Lihat [`PdfFileSecurity`](../pdffilesecurity/). Ada 4 cara menggunakan kelas ini: 1. Menggunakan hak akses yang telah ditentukan sebelumnya secara langsung. 2. Berdasarkan hak akses yang telah ditentukan sebelumnya dan mengubah beberapa izin spesifik. 3. Berdasarkan hak akses yang telah ditentukan sebelumnya dan mengubah beberapa kombinasi izin Adobe Professional yang spesifik. 4. Menggabungkan cara 2 dan cara 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Semua diizinkan. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Mengizinkan penggabungan file. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Mengizinkan penyalinan file. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Mengizinkan pencetakan yang terdegradasi. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Mengizinkan pengisian formulir dalam file. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Semua dilarang. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Mengizinkan modifikasi anotasi file. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Mengizinkan modifikasi file. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Mengizinkan pencetakan file. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Mengizinkan pembaca layar saja. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Mengatur izin yang mengizinkan penggabungan atau tidak. true adalah diizinkan dan false adalah dilarang. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Mengatur izin yang mengizinkan penyalinan atau tidak. true adalah diizinkan dan false adalah dilarang. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Mengatur izin yang mengizinkan pencetakan terdegradasi atau tidak. true adalah diizinkan dan false adalah dilarang. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Mengatur izin yang mengizinkan pengisian formulir atau tidak. true adalah diizinkan dan false adalah dilarang. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Mengatur izin yang mengizinkan modifikasi anotasi atau tidak. true adalah diizinkan dan false adalah dilarang. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Mengatur izin yang mengizinkan modifikasi konten atau tidak. true adalah diizinkan dan false adalah dilarang. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Mengatur izin yang mengizinkan pencetakan atau tidak. true adalah diizinkan dan false adalah dilarang. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Mengatur izin yang mengizinkan pembaca layar atau tidak. true adalah diizinkan dan false adalah dilarang. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Mendapatkan dan mengatur tingkat perubahan hak akses dokumen. Sama seperti pengaturan Perubahan yang Diizinkan di Adobe Professional. 0: Tidak ada. 1: Menyisipkan, Menghapus, dan Memutar halaman. 2: Mengisi bidang formulir dan menandatangani bidang tanda tangan yang ada. 3: Mengomentari, mengisi bidang formulir, dan menandatangani bidang tanda tangan yang ada. 4: Apa pun kecuali mengekstrak halaman. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Mendapatkan dan mengatur tingkat salinan hak akses dokumen. Sama seperti pengaturan izin Adobe Professional. 0: Tidak ada. 1: Mengaktifkan akses teks untuk perangkat pembaca layar bagi penyandang disabilitas visual. 2: Mengaktifkan penyalinan teks, gambar, dan konten lainnya. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Mendapatkan dan mengatur tingkat pencetakan hak akses dokumen. Sama seperti pengaturan Pencetakan yang Diizinkan di Adobe Professional. 0: Tidak ada. 1: Resolusi Rendah (150 dpi). 2: Resolusi Tinggi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Membandingkan dua objek `DocumentPrivilege`. Objek yang dibandingkan. Sebuah integer bertanda yang menunjukkan nilai relatif dari instance ini dan nilai. Kurang dari nol instance ini kurang dari nilai. Nol instance ini sama dengan nilai. Lebih dari nol instance ini lebih besar dari nilai. |

## Contoh

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)