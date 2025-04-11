---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Merger 클래스. Merger 플러그인을 나타냅니다.
type: docs
weight: 8940
url: /ko/net/aspose.pdf.plugins/merger/
---
## Merger 클래스

`Merger` 플러그인을 나타냅니다.

```csharp
public sealed class Merger : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Merger](merger/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | 지정된 매개변수로 `Merger` 처리를 시작합니다. |

## 예제

이 예제는 두 개의 PDF 문서를 병합하는 방법을 보여줍니다.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)