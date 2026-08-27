---
title: "클래스 Html"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.Html 클래스. Html 플러그인을 나타냅니다."
type: docs
weight: 8950
url: /ko/net/aspose.pdf.plugins/html/
---
## Html class

`Html` 플러그인을 나타냅니다.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Html](html/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | IDisposable 구현. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | 지정된 매개변수로 `Html` 처리를 시작합니다. |

## 예제

예제에서는 PDF를 HTML 문서로 변환하는 방법을 보여줍니다.

```csharp
// Html 생성
var converter = new Html();
// 임베드된 리소스를 포함한 파일로 출력 데이터 유형을 설정하기 위해 PdfToHtmlOptions 객체를 생성합니다.
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// 입력 파일 경로를 추가합니다
opt.AddInput(new FileDataSource(inputPath));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

예제에서는 HTML을 PDF 문서로 변환하는 방법을 보여줍니다.

```csharp
// Html 생성
var converter = new Html();
// HtmlToPdfOptions 생성
var opt = new HtmlToPdfOptions();
// 입력 파일 경로를 추가합니다
opt.AddInput(new FileDataSource(inputPath));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


