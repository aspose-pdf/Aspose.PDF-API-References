---
title: GetAttachment
second_title: Referencia de API de Aspose.PDF para .NET
description: Almacena el archivo adjunto en el archivo.
type: docs
weight: 140
url: /es/net/aspose.pdf.facades/pdfextractor/getattachment/
---
## GetAttachment(string) {#getattachment_1}

Almacena el archivo adjunto en el archivo.

```csharp
public void GetAttachment(string outputPath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputPath | String | Ruta del directorio donde se almacenarán los archivos adjuntos. Cadena nula o vacía significa que los archivos adjuntos se colocarán en el directorio de la aplicación. |

### Ver también

* class [PdfExtractor](../../pdfextractor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfextractor)
* asamblea [Aspose.PDF](../../../)

---

## GetAttachment() {#getattachment}

Guarda todo el archivo adjunto en streams.

```csharp
public MemoryStream[] GetAttachment()
```

### Valor_devuelto

La matriz de flujo del archivo adjunto en el documento pdf.

### Ejemplos

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

### Ver también

* class [PdfExtractor](../../pdfextractor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfextractor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->