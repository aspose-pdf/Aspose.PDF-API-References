---
title: "클래스 XslFoLoadOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.XslFoLoadOptions 클래스. XSLFO 파일을 PDF 문서에 로드/임포트하기 위한 옵션을 나타냅니다."
type: docs
weight: 11720
url: /ko/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

XSL-FO 파일을 PDF 문서에 로드/임포트하기 위한 옵션을 나타냅니다.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | xsl 데이터 없이 `XslFoLoadOptions` 객체를 생성합니다. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | xsl 데이터를 포함하여 `XslFoLoadOptions` 객체를 생성합니다. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | xsl 데이터를 포함하여 `XslFoLoadOptions` 객체를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | 로드된 SVG 파일에서 참조된 외부 리소스(있는 경우)의 상대 경로를 검색하는 기본 경로/URL입니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 해제하는 플래그를 가져오거나 설정합니다. `true`인 경우 해당 글꼴의 라이선스에서 금지된 작업을 수행할 수 있게 하며, 예를 들어 라이선스 규정이 임베딩을 금지하더라도 글꼴을 PDF 문서에 삽입할 수 있습니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `[`LoadOptions`](../loadoptions/)`가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환하면 Load 작업이 중단됩니다. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML을 PDF 문서로 변환하기 위한 xsl 데이터를 가져옵니다. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | 기존 xls 매개변수에 값을 삽입하기 위한 XsltArgumentList. XLS 파일에 값이 없는 'animal' 매개변수가 있습니다: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); 이제 변환기는 XLS 파일에 값이 'cat'인 'animal' 매개변수가 있다고 가정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | 소스 XSLFO 문서에 형식 오류가 포함될 수 있습니다. 이 열거형은 해당 오류를 처리하는 가능한 전략을 나열합니다. |

## 예제

다음 예제는 XSL-FO 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
// 문서 디렉터리 경로.
string dataDir = @"YOUR_DATA_DIRECTORY";

// XSL-FO 파일의 경로입니다.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// 출력 PDF 파일 경로.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// XslFoLoadOptions 초기화	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // PDF 파일 저장
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 또 보기

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


