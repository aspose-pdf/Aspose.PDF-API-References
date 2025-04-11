---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Signature 클래스. 서명 플러그인을 나타냅니다.
type: docs
weight: 9260
url: /ko/net/aspose.pdf.plugins/signature/
---
## 서명 클래스

`Signature` 플러그인을 나타냅니다.

```csharp
public sealed class Signature : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Signature](signature/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | 지정된 매개변수로 `Signature` 처리를 시작합니다. |

## 예제

이 예제는 PDF 문서에 서명하는 방법을 보여줍니다.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)