---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.IOperationResult-Schnittstelle. Allgemeine Schnittstelle für Operationsergebnisse, die gemeinsame Methoden definiert, die das konkrete Plugin-Operationsergebnis implementieren sollte
type: docs
weight: 8850
url: /de/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult-Schnittstelle

Allgemeine Schnittstelle für Operationsergebnisse, die gemeinsame Methoden definiert, die das konkrete Plugin-Operationsergebnis implementieren sollte.

```csharp
public interface IOperationResult
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Gibt die Rohdaten zurück. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Gibt an, ob das Ergebnis ein Pfad zu einer Ausgabedatei ist. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Gibt an, ob das Ergebnis ein Ausgabestream ist. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Gibt an, ob das Ergebnis eine Textzeichenfolge ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Versucht, das Ergebnis in die Datei zu konvertieren. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Versucht, das Ergebnis in das Stream-Objekt zu konvertieren. |

### Siehe auch

* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)