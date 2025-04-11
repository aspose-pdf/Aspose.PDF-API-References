---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Zu einer Eigenschaft dieses Typs können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung des externen Speicherns von Bildern implementiert, die aus SVG extrahiert wurden, die aus PDF erstellt wurden und während der Konvertierung von PDF nach HTML als externe Ressource gespeichert werden müssen. In diesem Fall kann die Verarbeitung (wie selbstgemachtes Speichern in einen Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen, und dieser benutzerdefinierte Code muss einen Pfad (oder einen anderen String ohne Anführungszeichen) zurückgeben, der anschließend in das generierte SVG anstelle des ursprünglich vorgesehenen Pfades zu dieser Bildressource integriert wird. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Bildes im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'imageSavingInfo'-Parameter. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code gäbe. repräsentiert Informationen über das gespeicherte Bild, die im benutzerdefinierten Code verwendet werden können, und muss einen String zurückgeben, der die URL des Bildes darstellt, das in das SVG eingefügt wird.
type: docs
weight: 10240
url: /de/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy-Delegat

Zu einer Eigenschaft dieses Typs können Sie einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung des externen Speicherns von Bildern implementiert, die aus SVG extrahiert wurden, die aus PDF erstellt wurden und während der Konvertierung von PDF nach HTML als externe Ressource gespeichert werden müssen. In diesem Fall kann die Verarbeitung (wie selbstgemachtes Speichern in einen Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen, und dieser benutzerdefinierte Code muss einen Pfad (oder einen anderen String ohne Anführungszeichen) zurückgeben, der anschließend in das generierte SVG anstelle des ursprünglich vorgesehenen Pfades zu dieser Bildressource integriert wird. In diesem Fall müssen alle notwendigen Aktionen zum Speichern des Bildes im Code der bereitgestellten Methode durchgeführt werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'imageSavingInfo'-Parameter. Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code gäbe. repräsentiert Informationen über das gespeicherte Bild, die im benutzerdefinierten Code verwendet werden können, und muss einen String zurückgeben, der die URL des Bildes darstellt, das in das SVG eingefügt wird.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Siehe auch

* Klasse [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* Klasse [SvgSaveOptions](../svgsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)