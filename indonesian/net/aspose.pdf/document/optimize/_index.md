---
title: "Document.Optimize"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Document. Lineariskan dokumen agar  membuka halaman pertama secepat mungkin  menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin  menampilkan halaman secara bertahap saat data halaman tiba ketika data untuk sebuah halaman dikirim melalui saluran lambat menampilkan data yang paling berguna terlebih dahulu  memungkinkan interaksi pengguna seperti mengikuti tautan dapat dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan. Memanggil metode ini tidak benar‑benar menyimpan dokumen. Sebaliknya dokumen hanya dipersiapkan dengan struktur yang dioptimalkan; panggil kemudian Save untuk mendapatkan dokumen yang dioptimalkan"
type: docs
weight: 770
url: /id/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

Linearize dokumen untuk - membuka halaman pertama secepat mungkin; - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin; - menampilkan halaman secara inkremental saat data halaman tiba ketika data untuk sebuah halaman dikirim melalui saluran lambat (menampilkan data yang paling berguna terlebih dahulu); - memungkinkan interaksi pengguna, seperti mengikuti tautan, dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan. Memanggil metode ini tidak benar-benar menyimpan dokumen. Sebaliknya dokumen hanya dipersiapkan untuk memiliki struktur yang dioptimalkan, panggil Save kemudian untuk mendapatkan dokumen yang dioptimalkan.

```csharp
public void Optimize()
```

### Contoh

Contoh berikut menunjukkan cara mengoptimalkan dokumen PDF untuk web.

```csharp
[C#]
	// Jalur ke File PDF Anda.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Buka dokumen
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimalkan untuk web
	pdfDocument.Optimize();

	// Simpan dokumen output
	pdfDocument.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
	
    ' Open document
    Using pdfDocument As Document = New Document(pdfFilePath)

        ' Optimize for web
        pdfDocument.Optimize()

        ' Save output document
        pdfDocument.Save(pdfFilePath)
    End Using
```

### Lihat Juga

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


