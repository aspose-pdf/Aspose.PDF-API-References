---
title: PdfExtractor.GetAttachment
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Armazena anexo em arquivo
type: docs
weight: 140
url: /pt/net/aspose.pdf.facades/pdfextractor/getattachment/
---
## GetAttachment(string) {#getattachment_1}

Armazena anexo em arquivo.

```csharp
public void GetAttachment(string outputPath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputPath | String | Caminho do diretório onde o(s) anexo(s) serão armazenados. Nulo ou string vazia significa que o(s) anexo(s) serão colocados no diretório da aplicação. |

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetAttachment() {#getattachment}

Salva todos os arquivos de anexo em streams.

```csharp
public MemoryStream[] GetAttachment()
```

### Valor de Retorno

O array de streams do arquivo de anexo no documento pdf.

## Exemplos

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

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)