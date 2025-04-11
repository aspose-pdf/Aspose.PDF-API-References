---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Metode dokumen. Melinierkan dokumen untuk membuka halaman pertama secepat mungkin, menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin, menampilkan halaman secara bertahap saat data untuk halaman dikirim melalui saluran yang lambat, menampilkan data yang paling berguna terlebih dahulu, mengizinkan interaksi pengguna seperti mengikuti tautan untuk dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan. Memanggil metode ini tidak benar-benar menyimpan dokumen. Sebaliknya, dokumen hanya dipersiapkan untuk memiliki struktur yang dioptimalkan, panggil kemudian Simpan untuk mendapatkan dokumen yang dioptimalkan.
type: docs
weight: 750
url: /id/net/aspose.pdf/document/optimize/
---
## Metode Document.Optimize

Melinierkan dokumen untuk - membuka halaman pertama secepat mungkin; - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin; - menampilkan halaman secara bertahap saat data untuk halaman dikirim melalui saluran yang lambat (menampilkan data yang paling berguna terlebih dahulu); - mengizinkan interaksi pengguna, seperti mengikuti tautan, untuk dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan. Memanggil metode ini tidak benar-benar menyimpan dokumen. Sebaliknya, dokumen hanya dipersiapkan untuk memiliki struktur yang dioptimalkan, panggil kemudian Simpan untuk mendapatkan dokumen yang dioptimalkan.

```csharp
public void Optimize()
```

### Contoh

Contoh berikut menunjukkan cara mengoptimalkan dokumen PDF untuk web.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimize for web
	pdfDocument.Optimize();

	// Save output document
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

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)