---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Optimizer 클래스. 최적화기 플러그인을 나타냅니다.
type: docs
weight: 8970
url: /ko/net/aspose.pdf.plugins/optimizer/
---
## 최적화기 클래스

`Optimizer` 플러그인을 나타냅니다.

```csharp
public sealed class Optimizer : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Optimizer](optimizer/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | 지정된 매개변수로 `Optimizer` 처리를 시작합니다. |

## 예제

이 예제는 PDF 문서를 최적화하는 방법을 보여줍니다.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)