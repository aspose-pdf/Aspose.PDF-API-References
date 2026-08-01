---
title: "클래스 TocGenerator"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.TocGenerator 클래스. Aspose.PDF TocGenerator 플러그인을 나타냅니다."
type: docs
weight: 9580
url: /ko/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Aspose.PDF TocGenerator 플러그인을 나타냅니다.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TocGenerator](tocgenerator/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | IDisposable 구현. 실제로 TocGenerator에 필요하지 않습니다. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | 지정된 매개변수로 PdfGenerator 처리를 시작합니다. |

## 예제

이 예제는 PDF 파일에 TOC를 추가하는 방법을 보여줍니다.

```csharp
// TocGenerator를 생성합니다.
var generator = new TocGenerator();
// 지시사항을 설정하기 위해 TocOptions 객체를 생성합니다.
var opt = new TocOptions();
// 입력 파일 경로를 추가합니다.
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
// 추출 프로세스를 수행합니다.
generator.Process(opt);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


