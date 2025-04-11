---
title: PdfExtractor.GetAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 方法。将附件存储到文件中
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/pdfextractor/getattachment/
---
## GetAttachment(string) {#getattachment_1}

将附件存储到文件中。

```csharp
public void GetAttachment(string outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputPath | 字符串 | 附件将存储的目录路径。空值或空字符串表示附件将放置在应用程序目录中。 |

### 另请参见

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## GetAttachment() {#getattachment}

将所有附件文件保存到流中。

```csharp
public MemoryStream[] GetAttachment()
```

### 返回值

pdf 文档中附件文件的流数组。

## 示例

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

### 另请参见

* 类 [PdfExtractor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)