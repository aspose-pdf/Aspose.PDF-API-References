---
title: Class SaveableFacade
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.SaveableFacade. Classe base para todas as fachadas salváveis
type: docs
weight: 4700
url: /pt/net/aspose.pdf.facades/saveablefacade/
---
## Classe SaveableFacade

Classe base para todas as fachadas salváveis.

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Desfaz o Aspose.Pdf.Document vinculado a uma fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save)(Stream) | Salva o documento PDF no fluxo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save_1)(string) | Salva o documento PDF no arquivo especificado. |

### Veja Também

* classe [Facade](../facade/)
* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)