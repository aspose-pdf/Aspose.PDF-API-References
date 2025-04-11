---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsResourceLoadingResult class. Result of custom loading of resource
type: docs
weight: 6150
url: /de/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult-Klasse

Ergebnis des benutzerdefinierten Ladens von Ressourcen

```csharp
public class ResourceLoadingResult
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Erstellt eine Instanz des Ladeergebnisses |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Binärdaten, die mit dem benutzerdefinierten Loader geladen wurden - sie müssen nach dem Laden festgelegt werden |

## Felder

| Name | Beschreibung |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Manchmal ist die Kodierung der Ressource nach oder während des Ladens bekannt. In diesem Fall kann benutzerdefinierter Code dem Konverter dieses Wissen über diesen Parameter bereitstellen. Sie können diesen Parameter auf null lassen, wenn die Kodierung unbekannt oder unwichtig ist. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Manchmal ist es aus irgendeinem Grund unmöglich, die angeforderte Ressource zu laden. Die Unverfügbarkeit der Ressource führt oft nicht zu einem Absturz des Konverters, und das Ergebnisdokument kann trotzdem erstellt werden (aber vielleicht in etwas schlechterer Qualität, ohne Bilder usw.). Wenn während des Ladens eine Ausnahme aufgetreten ist, fangen Sie sie einfach ab und setzen Sie sie in diesen Parameter - manchmal ist diese Information für den Konverter nützlich, um das Ergebnis darzustellen. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Manchmal sollte das Laden aus bestimmten Gründen nicht durch benutzerdefinierten Code erfolgen. In diesem Fall setzen Sie bitte dieses Flag auf Wahr. In diesem Fall wird der Konverter versuchen, den internen Standardressourcen-Loader zu verwenden, um dieses Ergebnis zu erhalten (wie es sich in Situationen verhält, in denen keine benutzerdefinierte Strategie bereitgestellt wird). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Manchmal ist das Wissen über den MIME-Typ der geladenen Ressource für den Konverter nützlich. Sie können den MIME-Typ (wenn er nach dem Laden bekannt ist) in diesem Parameter angeben. Bitte lassen Sie den Parameter auf null, wenn der MIME-Typ unbekannt ist oder es nicht notwendig ist, ihn bereitzustellen. |

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)