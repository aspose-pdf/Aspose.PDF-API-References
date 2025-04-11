---
title: Class SaveableFacade
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.SaveableFacade 클래스. 모든 저장 가능한 파사드의 기본 클래스
type: docs
weight: 4700
url: /ko/net/aspose.pdf.facades/saveablefacade/
---
## SaveableFacade class

모든 저장 가능한 파사드의 기본 클래스입니다.

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 파사드가 작업 중인 문서를 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 파사드를 초기화합니다. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 파사드와 연결된 Aspose.Pdf.Document를 해제합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 해제합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save)(Stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save_1)(string) | PDF 문서를 지정된 파일에 저장합니다. |

### See Also

* class [Facade](../facade/)
* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)