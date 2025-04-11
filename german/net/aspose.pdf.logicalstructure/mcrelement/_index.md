---
title: Class MCRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.MCRElement-Klasse. Stellt ein Referenzobjekt für markierte Inhalte in der logischen Struktur dar
type: docs
weight: 6500
url: /de/net/aspose.pdf.logicalstructure/mcrelement/
---
## MCRElement-Klasse

Stellt ein Referenzobjekt für markierte Inhalte in der logischen Struktur dar.

```csharp
public sealed class MCRElement : Element
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Gibt die Sammlung der Kind-Elementobjekte zurück. |
| [MCID](../../aspose.pdf.logicalstructure/mcrelement/mcid/) { get; } | Gibt die MCID des Referenzobjekts für markierte Inhalte zurück. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Gibt das übergeordnete Element zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Fügt ein Element zur Sammlung der Kinder hinzu. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Löscht alle Kinder. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Findet Elemente eines bestimmten Typs |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Fügt ein Element an einem bestimmten Index in die Sammlung der Kinder ein. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Entfernt das Kind an. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_2)(Annotation) | Bindet ein Strukturelement an die Annotation. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag)(Artifact) | Bindet ein Strukturelement an das Artefakt. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_1)(BDC) | Bindet ein Strukturelement an den Inhaltstream BDC-Operator. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_3)(XForm) | Bindet ein Strukturelement an den Inhaltstream XForm. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_4)(XImage) | Bindet ein Strukturelement an das XImage. |
| override [ToString](../../aspose.pdf.logicalstructure/mcrelement/tostring/)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* Klasse [Element](../element/)
* Namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* Assembly [Aspose.PDF](../../)