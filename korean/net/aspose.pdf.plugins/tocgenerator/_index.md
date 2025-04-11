---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TocGenerator 클래스. Aspose.PDF TocGenerator 플러그인을 나타냅니다.
type: docs
weight: 9430
url: /ko/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator 클래스

Aspose.PDF TocGenerator 플러그인을 나타냅니다.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TocGenerator](tocgenerator/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | IDisposable의 구현입니다. 사실, TocGenerator에는 필요하지 않습니다. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | 지정된 매개변수로 PdfGenerator 처리를 시작합니다. |

## 예제

이 예제는 PDF 파일에 TOC를 추가하는 방법을 보여줍니다.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)