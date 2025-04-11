---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Splitter 클래스. 분할기 플러그인을 나타냅니다.
type: docs
weight: 9280
url: /ko/net/aspose.pdf.plugins/splitter/
---
## 분할기 클래스

`Splitter` 플러그인을 나타냅니다.

```csharp
public class Splitter : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Splitter](splitter/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | 지정된 매개변수로 `Splitter` 처리를 시작합니다. |

## 예제

이 예제는 PDF 문서를 분할하는 방법을 보여줍니다.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)