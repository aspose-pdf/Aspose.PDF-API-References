---
title: PdfExtractor.GetAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor 메서드. 첨부 파일을 파일에 저장합니다.
type: docs
weight: 140
url: /ko/net/aspose.pdf.facades/pdfextractor/getattachment/
---
## GetAttachment(string) {#getattachment_1}

첨부 파일을 파일에 저장합니다.

```csharp
public void GetAttachment(string outputPath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputPath | 문자열 | 첨부 파일이 저장될 디렉터리 경로. Null 또는 빈 문자열은 첨부 파일이 애플리케이션 디렉터리에 배치됨을 의미합니다. |

### 참조

* 클래스 [PdfExtractor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetAttachment() {#getattachment}

모든 첨부 파일을 스트림으로 저장합니다.

```csharp
public MemoryStream[] GetAttachment()
```

### 반환 값

PDF 문서의 첨부 파일 스트림 배열입니다.

## 예제

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

### 참조

* 클래스 [PdfExtractor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)