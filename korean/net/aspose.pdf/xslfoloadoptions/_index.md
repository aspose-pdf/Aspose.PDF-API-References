---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptions 클래스. PDF 문서에 XSLFO 파일을 로드/가져오기 위한 옵션을 나타냅니다.
type: docs
weight: 11530
url: /ko/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions 클래스

PDF 문서에 XSL-FO 파일을 로드/가져오기 위한 옵션을 나타냅니다.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | XSL 데이터 없이 `XslFoLoadOptions` 객체를 생성합니다. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | XSL 데이터와 함께 `XslFoLoadOptions` 객체를 생성합니다. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | XSL 데이터와 함께 `XslFoLoadOptions` 객체를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | 로드된 SVG 파일에서 참조된 외부 리소스에 대한 상대 경로를 검색하는 기본 경로/URL입니다(있는 경우). |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 비활성화하는 플래그를 가져오거나 설정합니다. `true`일 때, 이 글꼴의 라이선스에 의해 금지된 글꼴로 작업을 수행할 수 있도록 허용합니다. 예를 들어, 이 글꼴에 대한 임베딩 규칙이 비활성화되어 있어도 PDF 문서에 글꼴을 임베드할 수 있습니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/)가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 로드 작업이 계속되지만, 사용자가 Abort를 반환할 경우 로드 작업은 중단되어야 합니다. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML을 PDF 문서로 변환하기 위한 XSL 데이터를 가져옵니다. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | 기존 XLS 매개변수에 값을 삽입하기 위한 XsltArgumentList입니다. XLS 파일에는 값이 없는 'animal' 매개변수가 있습니다: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); 이제 변환기는 XLS 파일에 'cat' 값이 있는 'animal' 매개변수가 있다고 가정합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | 원본 XSLFO 문서에는 형식 오류가 포함될 수 있습니다. 이 열거형은 이러한 오류를 처리하는 가능한 전략을 나열합니다. |

## 예제

다음 예제는 XSL-FO 파일을 PDF 파일로 변환하는 방법을 보여줍니다.

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
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

### 참조

* 클래스 [XmlLoadOptions](../xmlloadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)