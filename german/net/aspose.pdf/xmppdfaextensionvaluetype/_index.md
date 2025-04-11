---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionValueType-Klasse. Das PDF/A ValueType-Schema ist für alle Eigenschaftswerttypen erforderlich, die in der XMP 2004-Spezifikation nicht definiert sind, d.h. für Werttypen außerhalb der folgenden Liste: - Array-Typen (dies sind Containertypen, die ein oder mehrere Felder enthalten können): Alt, Bag, Seq - Grundlegende Werttypen: Boolean, (offene und geschlossene) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Medienverwaltungswerttypen: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Grundlegender Job/Workflow-Werttyp: Job - EXIF-Schema-Werttypen: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema-Namespace-URI: http://www.aiim.org/pdfa/ns/type# Erforderlicher Schema-Namespace-Präfix: pdfaType
type: docs
weight: 11490
url: /de/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## Klasse XmpPdfAExtensionValueType

Das PDF/A ValueType-Schema ist für alle Eigenschaftswerttypen erforderlich, die in der XMP 2004-Spezifikation nicht definiert sind, d.h. für Werttypen außerhalb der folgenden Liste: - Array-Typen (dies sind Containertypen, die ein oder mehrere Felder enthalten können): Alt, Bag, Seq - Grundlegende Werttypen: Boolean, (offene und geschlossene) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Medienverwaltungswerttypen: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Grundlegender Job/Workflow-Werttyp: Job - EXIF-Schema-Werttypen: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema-Namespace-URI: http://www.aiim.org/pdfa/ns/type# Erforderlicher Schema-Namespace-Präfix: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Initialisiert ein neues Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Gibt die Beschreibung zurück. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Gibt die Liste der Felder zurück. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Gibt die Namespace-URI zurück. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Gibt das Präfix zurück. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Gibt den Werttyp zurück. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Gibt den Wert zurück oder setzt ihn. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Fügt ein neues Feld hinzu. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Fügt den Bereich von Feldern hinzu. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Löscht alle Felder. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Gibt die Liste der XML-Elemente zurück, die den Werttyp im XML-Baum darstellen. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Entfernt das Feld aus der Liste der Felder. |

### Siehe auch

* Klasse [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)