---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: RenderingOptions-Eigenschaft. Ersetzt Schriftarten nach Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. Der Algorithmus zur Schriftartsubstitution folgt diesen Schritten: 1. Wenn der Benutzer die Eigenschaft DefaultFontName ausdrücklich festlegt, überprüfen Sie, ob die angegebene Schriftart die gewünschten Zeichen anzeigen kann. 2. Wenn keine benutzerdefinierte Schriftart festgelegt ist, suchen Sie nach Schriftarten, die über die FontRepository.Sources hinzugefügt wurden. 3. Analysieren Sie den Text, um sein Alphabet oder seine Schrift zu identifizieren, und schlagen Sie entsprechende Schriftartnamen vor. Versuchen Sie, diese Schriftarten im System zu finden und zu verwenden. 4. Als Fallback suchen Sie im System nach einer Schriftart, die in der Lage ist, die erforderlichen Zeichen anzuzeigen.
type: docs
weight: 20
url: /de/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts-Eigenschaft

Ersetzt Schriftarten nach Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. Der Algorithmus zur Schriftartsubstitution folgt diesen Schritten: 1. Wenn der Benutzer die Eigenschaft DefaultFontName ausdrücklich festlegt, überprüfen Sie, ob die angegebene Schriftart die gewünschten Zeichen anzeigen kann. 2. Wenn keine benutzerdefinierte Schriftart festgelegt ist, suchen Sie nach Schriftarten, die über die !:FontRepository.Sources hinzugefügt wurden. 3. Analysieren Sie den Text, um sein Alphabet oder seine Schrift zu identifizieren, und schlagen Sie entsprechende Schriftartnamen vor. Versuchen Sie, diese Schriftarten im System zu finden und zu verwenden. 4. Als Fallback suchen Sie im System nach einer Schriftart, die in der Lage ist, die erforderlichen Zeichen anzuzeigen.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Siehe auch

* Klasse [RenderingOptions](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)