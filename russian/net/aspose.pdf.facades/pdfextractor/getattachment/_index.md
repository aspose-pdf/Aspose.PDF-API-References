---
title: GetAttachment
second_title: Aspose.PDF для справочника API .NET
description: Сохраняет вложение в файл.
type: docs
weight: 140
url: /ru/net/aspose.pdf.facades/pdfextractor/getattachment/
---
## GetAttachment(string) {#getattachment_1}

Сохраняет вложение в файл.

```csharp
public void GetAttachment(string outputPath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputPath | String | Путь к каталогу, в котором будут храниться вложения. Нулевая или пустая строка означает, что вложения будут помещены в каталог приложения. |

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

---

## GetAttachment() {#getattachment}

Сохраняет все вложенные файлы в потоки.

```csharp
public MemoryStream[] GetAttachment()
```

### Возвращаемое значение

Потоковый массив вложенного файла в pdf-документе.

### Примеры

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

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
