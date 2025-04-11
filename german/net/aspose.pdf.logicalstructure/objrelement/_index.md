---
title: Class OBJRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.OBJRElement-Klasse. Stellt eine Objektverweiskategorie in der logischen Struktur dar
type: docs
weight: 6530
url: /de/net/aspose.pdf.logicalstructure/objrelement/
---
## Klasse OBJRElement

Stellt eine Objektverweiskategorie in der logischen Struktur dar.

```csharp
public sealed class OBJRElement : Element
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Ruft die Sammlung von Kind-Elementobjekten ab. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Ruft das übergeordnete Element ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Fügt ein Element zur Sammlung der Kinder hinzu. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Löscht alle Kinder. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Findet Elemente eines bestimmten Typs |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Fügt ein Element an der angegebenen Stelle in die Sammlung der Kinder ein. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Entfernt das Kind an. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_2)(Annotation) | Bindet ein Strukturelement an die Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag)(Artifact) | Bindet ein Strukturelement an das Artefakt. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_1)(BDC) | Bindet ein Strukturelement an den Inhaltstream BDC-Operator. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_3)(XForm) | Bindet ein Strukturelement an den Inhaltstream XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/objrelement/tag/#tag_4)(XImage) | Bindet ein Strukturelement an das XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/objrelement/tostring/)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* Klasse [Element](../element/)
* Namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* Assembly [Aspose.PDF](../../)