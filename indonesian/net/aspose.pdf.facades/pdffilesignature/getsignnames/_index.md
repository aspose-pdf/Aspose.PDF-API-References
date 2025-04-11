---
title: PdfFileSignature.GetSignNames
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSignature. Mendapatkan nama semua tanda tangan yang tidak kosong
type: docs
weight: 230
url: /id/net/aspose.pdf.facades/pdffilesignature/getsignnames/
---
## Metode PdfFileSignature.GetSignNames

Mendapatkan nama semua tanda tangan yang tidak kosong.

```csharp
public IList<string> GetSignNames(bool onlyActive = true)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| onlyActive | Boolean | jika true, hanya mengembalikan tanda tangan aktif; jika tidak, mengembalikan semua tanda tangan. |

### Nilai Kembali

Mengembalikan IList&lt;string&gt;.

## Contoh

```csharp
[C#]
string inFile=TestPath + "example1.pdf";
PdfFileSignature pdfSign=new PdfFileSignature();
pdfSign.BindPdf(inFile); 
var names=pdfSign.GetSignNames();
or(int i=0;i<names.Count;i++)

 Console.WriteLine("signature name:"+names[i]);
 Console.WriteLine("coverswholedocument:"+pdfSign.IsCoversWholeDocument(names[i]));
 Console.WriteLine("revision:"+pdfSign.GetRevision(names[i]));	
 Console.WriteLine("verifysigned:"+pdfSign.VerifySigned(names[i]));
 Console.WriteLine("reason:"+pdfSign.GetReason(names[i]));
 Console.WriteLine("location:"+pdfSign.GetLocation(names[i]));
 Console.WriteLine("datatime:"+pdfSign.GetDateTime(names[i]));		
}
Console.WriteLine("totalvision:"+pdfSign.GetTotalRevision());
[Visual Basic]
Dim pdfSign as PdfFileSignature =new  PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names=pdfSign.GetSignNames()
For i=0 To names.Count

	Console.WriteLine("signature name:" + (string)names[i])
	Console.WriteLine("coverswholedocument:" + pdfSign.IsCoversWholeDocument((string)names[i]))
	Console.WriteLine("revision:" + pdfSign.GetRevision((string)names[i]))	
	Console.WriteLine("verifysigned:" + pdfSign.VerifySigned((string)names[i]))
	Console.WriteLine("reason:" + pdfSign.GetReason((string)names[i]))
	Console.WriteLine("location:" + pdfSign.GetLocation((string)names[i]))
	Console.WriteLine("datatime:" + pdfSign.GetDateTime((string)names[i]))	
Next i
Console.WriteLine("totalvision:"+pdfSign.GetTotalRevision())
```

### Lihat Juga

* kelas [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)