---
title: "클래스 XmlLoadOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.XmlLoadOptions 클래스. XML 파일을 PDF 문서로 로드/임포트하기 위한 옵션을 나타냅니다."
type: docs
weight: 11580
url: /ko/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

XML 파일을 PDF 문서에 로드/임포트하기 위한 옵션을 나타냅니다.

```csharp
public class XmlLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | `XmlLoadOptions` 객체를 xsl 데이터 없이 생성합니다. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | `XmlLoadOptions` 객체를 xsl 데이터와 함께 생성합니다. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | `XmlLoadOptions` 객체를 xsl 데이터와 함께 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 해제하는 플래그를 가져오거나 설정합니다. `true`인 경우 해당 글꼴의 라이선스에서 금지된 작업을 수행할 수 있게 하며, 예를 들어 라이선스 규정이 임베딩을 금지하더라도 글꼴을 PDF 문서에 삽입할 수 있습니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `[`LoadOptions`](../loadoptions/)`가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환하면 Load 작업이 중단됩니다. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML을 PDF 문서로 변환하기 위한 xsl 데이터를 가져옵니다. |

## 예제

다음 예제는 XML 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// 문서 디렉터리 경로.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// XML 파일의 경로입니다.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// 출력 PDF 파일 경로.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// XmlLoadOptions 초기화	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// XML 파일 저장
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


