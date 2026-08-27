---
title: "TableGenerator 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.TableGenerator 클래스. Aspose.PDF TableGenerator 플러그인을 나타냅니다."
type: docs
weight: 9500
url: /ko/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

Aspose.PDF TableGenerator 플러그인을 나타냅니다.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TableGenerator](tablegenerator/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | IDisposable 구현. 실제로 TableGenerator에 필요하지 않습니다. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | 지정된 매개변수로 PdfGenerator 처리를 시작합니다. |

## 예제

예제에서는 PDF 파일에 표를 추가하는 방법을 보여줍니다.

```csharp
// TableGenerator 생성
var generator = new TableGenerator();
// 지시사항을 설정하기 위해 TableOptions 객체를 생성합니다.
var opt = new TableOptions();
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


