---
title: "Splitter 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.Splitter 클래스. Splitter 플러그인을 나타냅니다."
type: docs
weight: 9430
url: /ko/net/aspose.pdf.plugins/splitter/
---
## Splitter class

`Splitter` 플러그인을 나타냅니다.

```csharp
public class Splitter : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Splitter](splitter/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | 지정된 매개변수로 `Splitter` 처리를 시작합니다. |

## 예제

예제는 PDF 문서를 분할하는 방법을 보여줍니다.

```csharp
// Splitter 생성
var splitter = new Splitter();
// SplitOptions 객체를 생성하여 지시사항을 설정합니다.
var opt = new SplitOptions();
// 입력 파일 경로를 추가합니다.
opt.AddInput(new FileDataSource(inputPath));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// 프로세스를 수행합니다.
splitter.Process(opt);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


