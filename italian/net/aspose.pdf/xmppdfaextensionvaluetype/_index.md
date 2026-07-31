---
title: "Classe XmpPdfAExtensionValueType"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.XmpPdfAExtensionValueType. Lo schema PDF/A ValueType è richiesto per tutti i tipi di valore delle proprietà che non sono definiti nella specifica XMP 2004, cioè per i tipi di valore al di fuori della seguente lista: tipi di array (questi sono tipi contenitore che possono contenere uno o più campi) Alt Bag Seq; tipi di valore di base Boolean, open e closed, Choice, Date, Dimensions, Integer, Lang, Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath; tipi di valore di Media Management AgentName, RenditionClass, ResourceEvent, ResourceRef, Version; tipo di valore di base Job/Workflow Job; tipi di valore dello schema EXIF Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational; namespace dello schema URI http//www.aiim.org/pdfa/ns/type; prefisso del namespace dello schema richiesto pdfaType"
type: docs
weight: 11680
url: /it/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class

Lo schema PDF/A ValueType è richiesto per tutti i tipi di valore di proprietà che non sono definiti nella specifica XMP 2004, cioè per i tipi di valore al di fuori della seguente lista: - Tipi di array (sono tipi contenitori che possono contenere uno o più campi): Alt, Bag, Seq - Tipi di valore di base: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipi di valore per la gestione dei media: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo di valore base per Job/Workflow: Job - Tipi di valore dello schema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Namespace URI dello schema: http://www.aiim.org/pdfa/ns/type# Prefisso richiesto per lo schema: pdfaType

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
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Ottiene l'URI dello spazio dei nomi. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Ottiene il prefisso. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Ottiene il tipo di valore. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Ottiene o imposta il valore. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Aggiungi un nuovo campo. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Aggiunge l'intervallo di campi. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Cancella tutti i campi. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Restituisce l'elenco degli elementi xml che rappresentano il tipo di valore nell'albero xml. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Rimuove il campo dall'elenco dei campi. |

### Vedi anche

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


