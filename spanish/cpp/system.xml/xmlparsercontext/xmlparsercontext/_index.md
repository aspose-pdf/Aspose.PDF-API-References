---
title: "Constructor System::Xml::XmlParserContext::XmlParserContext"
linktitle: "XmlParserContext"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Constructor System::Xml::XmlParserContext::XmlParserContext. Inicializa una nueva instancia de la clase XmlParserContext con los XmlNameTable, XmlNamespaceManager, URI base, xml:lang, xml:space y los valores de tipo de documento especificados en C++."
type: docs
weight: 100
url: /es/cpp/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con los [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI base, **xml:lang**, **xml:space** y los valores de tipo de documento.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar para atomizar cadenas. Si es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) a usar para buscar información de espacios de nombres, o **nullptr**. |
| docTypeName | const String\& | El nombre de la declaración del tipo de documento. |
| pubId | const String\& | El identificador público. |
| sysId | const String\& | El identificador del sistema. |
| internalSubset | const String\& | El subconjunto interno DTD. El subconjunto DTD se usa para la resolución de entidades, no para la validación del documento. |
| baseURI | const String\& | El URI base para el fragmento XML (la ubicación desde la que se cargó el fragmento). |
| xmlLang | const String\& | El alcance de **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Un valor [XmlSpace](../../xmlspace/) que indica el alcance de **xml:space**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con los [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI base, **xml:lang**, **xml:space**, codificación y los valores de tipo de documento.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar para atomizar cadenas. Si es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) a usar para buscar información de espacios de nombres, o **nullptr**. |
| docTypeName | const String\& | El nombre de la declaración del tipo de documento. |
| pubId | const String\& | El identificador público. |
| sysId | const String\& | El identificador del sistema. |
| internalSubset | const String\& | El subconjunto interno DTD. El DTD se usa para la resolución de entidades, no para la validación del documento. |
| baseURI | const String\& | El URI base para el fragmento XML (la ubicación desde la que se cargó el fragmento). |
| xmlLang | const String\& | El alcance de **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Un valor [XmlSpace](../../xmlspace/) que indica el alcance de **xml:space**. |
| enc | const SharedPtr\<System::Text::Encoding\>\& | Un objeto Encoding que indica la configuración de codificación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con los [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** y **xml:space**.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar para atomizar cadenas. Si es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) a usar para buscar información de espacios de nombres, o **nullptr**. |
| xmlLang | const String\& | El alcance de **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Un valor [XmlSpace](../../xmlspace/) que indica el alcance de **xml:space**. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Inicializa una nueva instancia de la clase [XmlParserContext](../) con los [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** y codificación.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | El [XmlNameTable](../../xmlnametable/) a usar para atomizar cadenas. Si es **nullptr**, se utiliza la tabla de nombres usada para construir el **nsMgr**. Para obtener más información sobre las cadenas atomizadas, consulte [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | El [XmlNamespaceManager](../../xmlnamespacemanager/) a usar para buscar información de espacios de nombres, o **nullptr**. |
| xmlLang | const String\& | El alcance de **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Un valor [XmlSpace](../../xmlspace/) que indica el alcance de **xml:space**. |
| enc | const SharedPtr\<System::Text::Encoding\>\& | Un objeto Encoding que indica la configuración de codificación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
