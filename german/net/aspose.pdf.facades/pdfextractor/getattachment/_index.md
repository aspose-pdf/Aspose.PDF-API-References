---
title: PdfExtractor.GetAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-Methode. Speichert Anhang in Datei
type: docs
weight: 140
url: /de/net/aspose.pdf.facades/pdfextractor/getattachment/
---
## GetAttachment(string) {#getattachment_1}

Speichert Anhang in Datei.

```csharp
public void GetAttachment(string outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputPath | String | Verzeichnispfad, in dem der/die Anhang/Anhänge gespeichert werden. Null oder leerer String bedeutet, dass der/die Anhang/Anhänge im Anwendungsverzeichnis abgelegt werden. |

### Siehe auch

* Klasse [PdfExtractor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetAttachment() {#getattachment}

Speichert alle Anhangdateien in Streams.

```csharp
public MemoryStream[] GetAttachment()
```

### Rückgabewert

Das Stream-Array der Anhangdatei im PDF-Dokument.

## Beispiele

```csharp
[C#]
PdfExtractor extractor = new PdfExtractor();     
extractor.BindPdf(path + "Attach.pdf");
extractor.ExtractAttachment();
IList names = extractor.GetAttachNames();
MemoryStream[] tempStreams =  extractor.GetAttachment();
for (int i=0; i<tempStreams.Length; i++)
{
	string name = (string)names[i];
	FileStream fs = new FileStream(path + name,System.IO.FileMode.Create);
	byte[] tempBytes = new byte[4096];
	tempStreams[i].Position = 0;

	for (; ; )
	{
		int numOfBytes = tempStreams[i].Read(tempBytes, 0, 4096);
		if (numOfBytes < 1)
		break;
		fs.Write(tempBytes, 0, numOfBytes);
	}
	fs.Close();
}

[Visual Basic]
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(path + "Attach.pdf")
extractor.ExtractAttachment()
extractor.GetAttachment(path)
Dim names As IList =  extractor.GetAttachNames() 
Dim tempStreams() As MemoryStream =  extractor.GetAttachment() 
for(Integer i = 0 i<tempStreams.Length i++)
{
	Dim name As String = CType(names(i), String)
	Dim fs As FileStream =  New FileStream(path + name,System.IO.FileMode.Create) 
	Dim tempBytes() As Byte =  New Byte(4096) {} 
	tempStreams(i).Position = 0

	for()
	{
		Dim numOfBytes As Integer =  tempStreams(i).Read(tempBytes,0,4096) 
		If numOfBytes < 1 Then
			break
		End If
		fs.Write(tempBytes, 0, numOfBytes)
	}
	fs.Close()
}
```

### Siehe auch

* Klasse [PdfExtractor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)