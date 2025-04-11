---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Html 클래스. Html 플러그인을 나타냅니다.
type: docs
weight: 8820
url: /ko/net/aspose.pdf.plugins/html/
---
## Html 클래스

`Html` 플러그인을 나타냅니다.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Html](html/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | IDisposable의 구현입니다. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | 지정된 매개변수로 `Html` 처리를 시작합니다. |

## 예제

이 예제는 PDF를 HTML 문서로 변환하는 방법을 보여줍니다.

```csharp
// create Html
var converter = new Html();
// create PdfToHtmlOptions object to set output data type as file with embedded resources
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

이 예제는 HTML을 PDF 문서로 변환하는 방법을 보여줍니다.

```csharp
// create Html
var converter = new Html();
// create HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)