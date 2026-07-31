---
title: "Kelas DocumentPrivilege"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Facades.DocumentPrivilege class. Mewakili hak istimewa untuk mengakses file Pdf. Refer toPdfFileSecurity. Ada 4 cara menggunakan kelas ini 1. Menggunakan hak istimewa yang telah ditentukan secara langsung. 2. Berdasarkan hak istimewa yang telah ditentukan dan mengubah beberapa izin tertentu. 3. Berdasarkan hak istimewa yang telah ditentukan dan mengubah kombinasi izin Adobe Professional tertentu. 4. Menggabungkan cara2 dan cara3."
type: docs
weight: 4350
url: /id/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Mewakili hak istimewa untuk mengakses file Pdf. Lihat[`PdfFileSecurity`](../pdffilesecurity/). Ada 4 cara menggunakan kelas ini: 1. Menggunakan hak istimewa yang telah ditentukan secara langsung. 2. Berdasarkan hak istimewa yang telah ditentukan dan mengubah beberapa izin tertentu. 3. Berdasarkan hak istimewa yang telah ditentukan dan mengubah kombinasi izin tertentu dari Adobe Professional. 4. Menggabungkan way2 dan way3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Semua diizinkan. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Mengizinkan perakitan file. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Mengizinkan penyalinan file. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Mengizinkan pencetakan beresolusi rendah. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Mengizinkan pengisian formulir dalam file. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Semua dilarang. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Mengizinkan modifikasi anotasi file. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Mengizinkan modifikasi file. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Mengizinkan pencetakan file. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Mengizinkan pembaca hanya pada layar. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Mengatur izin yang mengizinkan perakitan atau tidak. true berarti diizinkan dan false berarti dilarang. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Mengatur izin yang mengizinkan penyalinan atau tidak. true berarti diizinkan dan false berarti dilarang. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Mengatur izin yang mengizinkan pencetakan beresolusi rendah atau tidak. true berarti diizinkan dan false berarti dilarang. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Mengatur izin yang mengizinkan pengisian formulir atau tidak. true berarti diizinkan dan false berarti dilarang. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Mengatur izin yang mengizinkan modifikasi anotasi atau tidak. true berarti diizinkan dan false berarti dilarang. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Mengatur izin yang mengizinkan modifikasi konten atau tidak. true berarti diizinkan dan false berarti dilarang. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Mengatur izin yang mengizinkan pencetakan atau tidak. true berarti diizinkan dan false berarti dilarang. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Mengatur izin yang mengizinkan pembaca layar atau tidak. true berarti diizinkan dan false berarti dilarang. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Mendapatkan dan mengatur tingkat perubahan hak istimewa dokumen. Sama seperti pengaturan Changes Allowed pada Adobe Professional. 0: Tidak ada. 1: Menyisipkan, Menghapus, dan Memutar halaman. 2: Mengisi bidang formulir dan menandatangani bidang tanda tangan yang ada. 3: Memberi komentar, mengisi bidang formulir, dan menandatangani bidang tanda tangan yang ada. 4: Semua kecuali mengekstrak halaman. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Mendapatkan dan mengatur tingkat penyalinan hak istimewa dokumen. Sama seperti pengaturan izin pada Adobe Professional. 0: Tidak ada. 1: Mengaktifkan akses teks untuk perangkat pembaca layar bagi penyandang tunanetra. 2: Mengaktifkan penyalinan teks, gambar, dan konten lainnya. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Mendapatkan dan mengatur tingkat pencetakan hak istimewa dokumen. Sama seperti pengaturan Printing Allowed pada Adobe Professional. 0: Tidak ada. 1: Resolusi rendah (150 dpi). 2: Resolusi tinggi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Membandingkan dua objek `DocumentPrivilege`.  Objek yang dibandingkan. Sebuah integer bertanda yang menunjukkan nilai relatif antara instance ini dan nilai. Nilai kurang dari nol berarti instance ini lebih kecil dari nilai. Nol berarti instance ini sama dengan nilai. Nilai lebih dari nol berarti instance ini lebih besar dari nilai. |

## Contoh

```csharp
[C#]	
//Way1: Menggunakan hak istimewa yang telah ditentukan secara langsung.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Berdasarkan hak istimewa yang telah ditentukan dan mengubah beberapa izin tertentu.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Berdasarkan hak istimewa yang telah ditentukan dan mengubah beberapa kombinasi izin Adobe Professional yang spesifik.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Menggabungkan way2 dan way3
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


