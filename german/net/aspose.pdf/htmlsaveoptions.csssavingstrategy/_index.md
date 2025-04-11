---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Sie können dieser Eigenschaft eine benutzerdefinierte Strategie zuweisen, die die Verarbeitung und/oder das Speichern eines CSS-Teils implementiert, der während der Konvertierung von PDF zu HTML erstellt wurde. In diesem Fall muss die Verarbeitung (wie das Speichern in einen Stream oder auf die Festplatte) im benutzerdefinierten Code erfolgen.
type: docs
weight: 5590
url: /de/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy-Delegat

Sie können dieser Eigenschaft eine benutzerdefinierte Strategie zuweisen, die die Verarbeitung und/oder das Speichern eines CSS-Teils implementiert, der während der Konvertierung von PDF zu HTML erstellt wurde. In diesem Fall muss die Verarbeitung (wie das Speichern in einen Stream oder auf die Festplatte) im benutzerdefinierten Code erfolgen.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | stellt eine Menge von Daten dar, die zum Speichern des bereitgestellten CSS-Teils verwendet werden können |

### Siehe auch

* Klasse [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)