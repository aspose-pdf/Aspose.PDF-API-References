---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.XmpPdfAExtensionValueType. Lo schema ValueType PDF/A è richiesto per tutti i tipi di valore delle proprietà che non sono definiti nella specifica XMP 2004, cioè per i tipi di valore al di fuori della seguente lista - Tipi Array Alt, Bag, Seq - Tipi di valore di base Boolean, Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipi di valore di gestione dei media AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo di valore di base Job/Workflow Job - Tipi di valore dello schema EXIF Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI http//www.aiim.org/pdfa/ns/type# Prefisso dello schema namespace richiesto pdfaType
type: docs
weight: 11490
url: /it/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## Classe XmpPdfAExtensionValueType

Lo schema ValueType PDF/A è richiesto per tutti i tipi di valore delle proprietà che non sono definiti nella specifica XMP 2004, cioè per i tipi di valore al di fuori della seguente lista: - Tipi Array (questi sono tipi contenitore che possono contenere uno o più campi): Alt, Bag, Seq - Tipi di valore di base: Boolean, (aperto e chiuso) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipi di valore di gestione dei media: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo di valore di base Job/Workflow: Job - Tipi di valore dello schema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Prefisso dello schema namespace richiesto: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Inizializza un nuovo oggetto. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Ottiene la descrizione. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Ottiene l'elenco dei campi. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Ottiene l'URI del namespace. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Ottiene il prefisso. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Ottiene il tipo di valore. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Ottiene o imposta il valore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Aggiunge un nuovo campo. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Aggiunge l'intervallo di campi. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Pulisce tutti i campi. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Restituisce l'elenco degli elementi xml che rappresentano il tipo di valore nell'albero xml. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Rimuove il campo dall'elenco dei campi. |

### Vedi Anche

* classe [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)