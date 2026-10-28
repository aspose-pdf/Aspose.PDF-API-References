---
title: "Optimizer 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.Optimizer 클래스. Optimizer 플러그인을 나타냅니다."
type: docs
weight: 9120
url: /ko/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

`Optimizer` 플러그인을 나타냅니다.

```csharp
public sealed class Optimizer : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Optimizer](optimizer/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | 지정된 매개변수로 `Optimizer` 처리를 시작합니다. |

## 예제

예제에서는 PDF 문서를 최적화하는 방법을 보여줍니다.

```csharp
// Optimizer 생성
var optimizer = new Optimizer();
// 지시사항을 설정하기 위해 OptimizeOptions 객체를 생성합니다.
var opt = new OptimizeOptions();
// 입력 파일 경로를 추가합니다.
opt.AddInput(new FileDataSource(inputPath));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
// 프로세스를 수행합니다.
optimizer.Process(opt);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


