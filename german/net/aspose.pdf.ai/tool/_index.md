---
title: Class Tool
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.Tool-Klasse. Stellt ein Werkzeug dar, das vom Modell aufgerufen werden kann
type: docs
weight: 1190
url: /de/net/aspose.pdf.ai/tool/
---
## Werkzeugklasse

Stellt ein Werkzeug dar, das vom Modell aufgerufen werden kann.

```csharp
public class Tool
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Tool](tool/#constructor)() | Initialisiert eine neue Instanz der `Tool`-Klasse. |
| [Tool](tool/#constructor_1)(Function) | Initialisiert eine neue Instanz der `Tool`-Klasse mit der angegebenen Funktion. |
| [Tool](tool/#constructor_2)(string) | Initialisiert eine neue Instanz der `Tool`-Klasse mit dem angegebenen Werkzeugtyp. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | Gibt eine Werkzeuginstanz zurück, die einen Code-Interpreter darstellt. |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | Gibt eine Werkzeuginstanz zurück, die ein Datei-Suchwerkzeug darstellt. |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | Ruft die Funktion ab oder legt die Funktion fest, die das Modell aufrufen kann. |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | Ruft den Typ des Werkzeugs ab oder legt ihn fest. Derzeit wird nur die Funktion unterstützt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | Erstellt eine neue Werkzeuginstanz mit der angegebenen Funktion. |

### Siehe auch

* Namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* Assembly [Aspose.PDF](../../)