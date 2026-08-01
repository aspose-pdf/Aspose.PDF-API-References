---
title: "클래스 Signature"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.Signature 클래스. Signature 플러그인을 나타냅니다"
type: docs
weight: 9410
url: /ko/net/aspose.pdf.plugins/signature/
---
## Signature class

`Signature` 플러그인을 나타냅니다.

```csharp
public sealed class Signature : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Signature](signature/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | 지정된 매개변수로 `Signature` 처리를 시작합니다. |

## 예제

예제는 PDF 문서에 서명하는 방법을 보여줍니다.

```csharp
// Signature 생성
var plugin = new Signature();
// 지시사항을 설정하기 위해 SignOptions 객체를 생성합니다
var opt = new SignOptions(inputPfx, inputPfxPassword);
// 입력 파일 경로를 추가합니다
opt.AddInput(new FileDataSource(inputPath));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
// 프로세스를 수행합니다.
plugin.Process(opt);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


