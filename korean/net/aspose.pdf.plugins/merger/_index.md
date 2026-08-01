---
title: "클래스 Merger"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.Merger 클래스. Merger 플러그인을 나타냅니다."
type: docs
weight: 9070
url: /ko/net/aspose.pdf.plugins/merger/
---
## Merger class

`Merger` 플러그인을 나타냅니다.

```csharp
public sealed class Merger : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Merger](merger/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | `Merger` 처리를 지정된 매개변수와 함께 시작합니다. |

## 예제

예제는 두 개의 PDF 문서를 병합하는 방법을 보여줍니다.

```csharp
// Merger 생성
var merger = new Merger();
// MergeOptions 객체를 생성하여 지시사항을 설정합니다.
var opt = new MergeOptions();
// 입력 파일 경로를 추가합니다.
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
// 프로세스를 수행합니다.
merger.Process(opt);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


