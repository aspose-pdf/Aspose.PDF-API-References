---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions-Feld. Dieses Feld kann eine Speicherstrategie enthalten, die verwendet werden muss, wenn sie während der Konvertierung vorhanden ist, um eine benutzerdefinierte Handhabung der erstellten referenzierten externen Bilddateien wie eingebettete BMP oder JPEG, die in das gespeicherte SVG eingebettet sind, zu ermöglichen. Diese Strategie muss Ressourcen verarbeiten und einen String zurückgeben, der die gewünschte URI der gespeicherten Ressource im generierten SVG darstellt. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'imageSavingInfo'. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code gäbe.
type: docs
weight: 30
url: /de/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving-Feld

Dieses Feld kann eine Speicherstrategie enthalten, die verwendet werden muss (wenn vorhanden) während der Konvertierung für eine benutzerdefinierte Handhabung der erstellten referenzierten externen Bilddateien (wie eingebettete BMP oder JPEG), die in das gespeicherte SVG eingebettet sind. Diese Strategie muss Ressourcen verarbeiten und einen String zurückgeben, der die gewünschte URI der gespeicherten Ressource im generierten SVG darstellt. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'imageSavingInfo'. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code gäbe.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Siehe auch

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)