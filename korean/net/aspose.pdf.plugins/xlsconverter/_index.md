---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.XlsConverter 클래스. XlsConverter 플러그인을 나타냅니다.
type: docs
weight: 9450
url: /ko/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter 클래스

`XlsConverter` 플러그인을 나타냅니다.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XlsConverter](xlsconverter/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | IDisposable의 구현입니다. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | 지정된 매개변수로 PdfToExcel 처리를 시작합니다. |

## 예제

이 예제는 PDF를 XLSX 문서로 변환하는 방법을 보여줍니다.

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)