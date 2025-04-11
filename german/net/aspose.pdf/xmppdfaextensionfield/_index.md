---
title: Class XmpPdfAExtensionField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionField-Klasse. Dieses Schema beschreibt ein Feld in einem strukturierten Typ. Es ist sehr ähnlich dem PDF/A Property Value Type-Schema, definiert jedoch ein Feld in einer Struktur anstelle einer Eigenschaft. Schema-Namensraum-URI http//www.aiim.org/pdfa/ns/field Erforderlicher Schema-Namensraum-Präfix pdfaField
type: docs
weight: 11440
url: /de/net/aspose.pdf/xmppdfaextensionfield/
---
## Klasse XmpPdfAExtensionField

Dieses Schema beschreibt ein Feld in einem strukturierten Typ. Es ist sehr ähnlich dem PDF/A Property Value Type-Schema, definiert jedoch ein Feld in einer Struktur anstelle einer Eigenschaft. Schema-Namensraum-URI: http://www.aiim.org/pdfa/ns/field# Erforderlicher Schema-Namensraum-Präfix: pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | Initialisiert das Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Gibt die Beschreibung zurück. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | Feldname. Feldnamen müssen gültige XML-Elementnamen sein. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Gibt den Wert zurück oder setzt ihn. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | Feldwerttyp, entnommen aus der XMP-Spezifikation 2004 oder einem eingebetteten PDF/A-Werttyp-Erweiterungsschema. Vorgegebene XMP-Typnamen oder Namen benutzerdefinierter Typen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | Gibt die Liste der XML-Elemente zurück, die das Feld im XML-Baum darstellen. |

### Siehe auch

* Klasse [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namensraum [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)