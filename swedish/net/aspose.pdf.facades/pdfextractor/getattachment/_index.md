---
title: GetAttachment
second_title: Aspose.PDF för .NET API Referens
description: Lagrar bilaga i fil.
type: docs
weight: 140
url: /sv/net/aspose.pdf.facades/pdfextractor/getattachment/
---
## GetAttachment(string) {#getattachment_1}

Lagrar bilaga i fil.

```csharp
public void GetAttachment(string outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputPath | String | Katalogsökväg där bilagor kommer att lagras. Null eller tom sträng betyder att bilagor kommer att placeras i applikationskatalogen. |

### Se även

* class [PdfExtractor](../../pdfextractor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfextractor)
* hopsättning [Aspose.PDF](../../../)

---

## GetAttachment() {#getattachment}

Sparar alla bifogade filer till streams.

```csharp
public MemoryStream[] GetAttachment()
```

### Returvärde

Streamarrayen för den bifogade filen i pdf-dokumentet.

### Exempel

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

### Se även

* class [PdfExtractor](../../pdfextractor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfextractor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
