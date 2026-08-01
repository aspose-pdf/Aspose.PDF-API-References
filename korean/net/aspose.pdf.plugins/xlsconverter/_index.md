---
title: "클래스 XlsConverter"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.XlsConverter 클래스. XlsConverter 플러그인을 나타냅니다"
type: docs
weight: 9600
url: /ko/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

`XlsConverter` 플러그인을 나타냅니다.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XlsConverter](xlsconverter/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | IDisposable 구현. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | 지정된 매개변수로 PdfToExcel 처리를 시작합니다. |

## 예제

예제는 PDF를 XLSX 문서로 변환하는 방법을 보여줍니다.

```csharp
// XlsConverter 변환기를 생성합니다
var converter = new XlsConverter();
// PdfToXLSOptions를 생성합니다
var opt = new PdfToXLSOptions();
// 입력 파일 경로를 추가합니다
opt.AddInput(new FileDataSource(inputPath));
// 출력 파일 경로를 설정합니다.
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


