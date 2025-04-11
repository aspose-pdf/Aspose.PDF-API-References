---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.OptimizationOptions-Klasse. Klasse, die den Algorithmus zur Dokumentoptimierung beschreibt. Eine Instanz dieser Klasse kann als Parameter der OptimizeResources-Methode verwendet werden.
type: docs
weight: 7980
url: /de/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions-Klasse

Klasse, die den Algorithmus zur Dokumentoptimierung beschreibt. Eine Instanz dieser Klasse kann als Parameter der OptimizeResources()-Methode verwendet werden.

```csharp
public class OptimizationOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Wenn wahr, werden die Seiteninhalte wiederverwendet, wenn das Dokument für gleiche Seiten optimiert wird. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Wenn dieses Flag auf `true` gesetzt ist, werden Pdf-Objekte in Objektströme gepackt und komprimiert, um die PDF-Dateigröße zu reduzieren. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Eine Reihe von Optionen, die beschreiben, ob Bilder im Dokument komprimiert werden und die Parameter der Kompression. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Der verwendete Bildencoder. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Wenn dieses Flag auf wahr gesetzt ist, werden Ressourcenströme analysiert. Wenn doppelte Ströme gefunden werden (d.h. wenn die Inhalte der Ströme gleich sind), werden diese Ströme als ein Objekt gespeichert. Dies ermöglicht es, die Dokumentgröße in einigen Fällen zu verringern (zum Beispiel, wenn dasselbe Dokument mehrfach zusammengefügt wurde). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Scanning-Level. Tiefere Scans (höherer Wert) dauern länger, können jedoch kleinere Ergebnisdateien erzeugen. Standardwert: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Gibt die maximale Auflösung von Bildern an. Wenn ein Bild eine höhere Auflösung hat, wird es skaliert. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Entfernt private Informationen (Seitenstückinformationen). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Wenn dieses Flag auf wahr gesetzt ist, werden alle Dokumentobjekte überprüft und ungenutzte Objekte (d.h. Objekte, die keine Referenz haben) werden aus dem Dokument entfernt. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Wenn dieses Flag auf wahr gesetzt ist, wird jede Ressource auf ihre Verwendung überprüft. Wenn eine Ressource nie verwendet wird, wird sie entfernt. Dies kann die Dokumentgröße verringern, zum Beispiel wenn Seiten aus dem Dokument extrahiert wurden. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Schriftarten werden in Teilmengen umgewandelt, wenn auf wahr gesetzt. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Macht Schriftarten nicht eingebettet, wenn auf wahr gesetzt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Erstellt eine Optimierungsstrategie mit allen aktivierten Optionen. Bitte beachten Sie, dass nur Optionen aktiviert werden, die keine Funktionalität des Dokuments ändern. D.h. die Bildkompression und das Entbetten von Schriftarten werden nicht aktiviert (und können manuell eingebettet werden). |

### Siehe auch

* Namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* Assembly [Aspose.PDF](../../)