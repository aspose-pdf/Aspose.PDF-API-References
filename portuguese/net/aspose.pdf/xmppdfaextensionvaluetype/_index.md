---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XmpPdfAExtensionValueType. O esquema ValueType do PDF/A é necessário para todos os tipos de valor de propriedade que não estão definidos na especificação XMP 2004, ou seja, para tipos de valor fora da seguinte lista: - Tipos de Array: Alt, Bag, Seq - Tipos de valor básico: Boolean, Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipos de valor de gerenciamento de mídia: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo de valor básico de Job/Workflow: Job - Tipos de valor do esquema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Namespace URI do esquema: http//www.aiim.org/pdfa/ns/type Prefixo do namespace do esquema necessário: pdfaType
type: docs
weight: 11490
url: /pt/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## Classe XmpPdfAExtensionValueType

O esquema ValueType do PDF/A é necessário para todos os tipos de valor de propriedade que não estão definidos na especificação XMP 2004, ou seja, para tipos de valor fora da seguinte lista: - Tipos de Array (estes são tipos de contêiner que podem conter um ou mais campos): Alt, Bag, Seq - Tipos de valor básico: Boolean, (aberto e fechado) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipos de valor de gerenciamento de mídia: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo de valor básico de Job/Workflow: Job - Tipos de valor do esquema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Namespace URI do esquema: http://www.aiim.org/pdfa/ns/type# Prefixo do namespace do esquema necessário: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Inicializa um novo objeto. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Obtém a descrição. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Obtém a lista de campos. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Obtém o namespace URI. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Obtém o prefixo. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Obtém o tipo de valor. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Obtém ou define o valor. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Adiciona um novo campo. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Adiciona a faixa de campos. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Limpa todos os campos. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Retorna a lista de elementos xml que representam o tipo de valor na árvore xml. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Remove o campo da lista de campos. |

### Veja Também

* classe [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)