---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.Element-Klasse. Stellt eine Basisklasse für Elemente in der logischen Struktur dar
type: docs
weight: 6320
url: /de/net/aspose.pdf.logicalstructure/element/
---
## Element-Klasse

Stellt eine Basisklasse für Elemente in der logischen Struktur dar.

```csharp
public abstract class Element
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gibt die Sammlung von Kind-Elementobjekten zurück. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Gibt das übergeordnete Element zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Fügt ein Element zur Sammlung der Kinder hinzu. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Löscht alle Kinder. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Findet Elemente eines bestimmten Typs |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Fügt ein Element an der angegebenen Stelle in die Sammlung der Kinder ein. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Entfernt das Kind an. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Bindet ein Strukturelement an die Annotation. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Bindet ein Strukturelement an das Artefakt. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Bindet ein Strukturelement an den Inhaltsstrom BDC-Operator. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Bindet ein Strukturelement an den Inhaltsstrom XForm. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Bindet ein Strukturelement an das XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)