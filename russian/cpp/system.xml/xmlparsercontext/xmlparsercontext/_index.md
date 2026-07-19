---
title: "Конструктор System::Xml::XmlParserContext::XmlParserContext"
linktitle: "XmlParserContext"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор System::Xml::XmlParserContext::XmlParserContext. Инициализирует новый экземпляр класса XmlParserContext с указанными XmlNameTable, XmlNamespaceManager, базовым URI, xml:lang, xml:space и значениями типа документа в C++."
type: docs
weight: 100
url: /ru/cpp/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor


Инициализирует новый экземпляр класса [XmlParserContext](../) с указанными [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), базовым URI, **xml:lang**, **xml:space** и значениями типа документа.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | Таблица [XmlNameTable](../../xmlnametable/), используемая для атомизации строк. Если это **nullptr**, используется таблица имен, применённая при построении **nsMgr**. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для поиска информации о пространствах имён, или **nullptr**. |
| docTypeName | const String\& | Имя объявления типа документа. |
| pubId | const String\& | Публичный идентификатор. |
| sysId | const String\& | Системный идентификатор. |
| internalSubset | const String\& | Внутренний набор DTD. Набор DTD используется для разрешения сущностей, а не для проверки документа. |
| baseURI | const String\& | Базовый URI для фрагмента XML (место, из которого был загружен фрагмент). |
| xmlLang | const String\& | Область **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Значение [XmlSpace](../../xmlspace/) указывает область **xml:space**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Инициализирует новый экземпляр класса [XmlParserContext](../) с указанными [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), базовым URI, **xml:lang**, **xml:space**, кодировкой и значениями типа документа.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | Таблица [XmlNameTable](../../xmlnametable/), используемая для атомизации строк. Если это **nullptr**, используется таблица имен, применённая при построении **nsMgr**. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для поиска информации о пространствах имён, или **nullptr**. |
| docTypeName | const String\& | Имя объявления типа документа. |
| pubId | const String\& | Публичный идентификатор. |
| sysId | const String\& | Системный идентификатор. |
| internalSubset | const String\& | Внутренний набор DTD. DTD используется для разрешения сущностей, а не для проверки документа. |
| baseURI | const String\& | Базовый URI для фрагмента XML (место, из которого был загружен фрагмент). |
| xmlLang | const String\& | Область **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Значение [XmlSpace](../../xmlspace/) указывает область **xml:space**. |
| enc | const SharedPtr\<System::Text::Encoding\>\& | Объект Encoding, указывающий настройку кодировки. |

## См. также

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


Инициализирует новый экземпляр класса [XmlParserContext](../) с указанными [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), значениями **xml:lang** и **xml:space**.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | Таблица [XmlNameTable](../../xmlnametable/), используемая для атомизации строк. Если это **nullptr**, используется таблица имен, применённая при построении **nsMgr**. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для поиска информации о пространствах имён, или **nullptr**. |
| xmlLang | const String\& | Область **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Значение [XmlSpace](../../xmlspace/) указывает область **xml:space**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Инициализирует новый экземпляр класса [XmlParserContext](../) с указанными [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** и кодировкой.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| nt | const SharedPtr\<XmlNameTable\>\& | Таблица [XmlNameTable](../../xmlnametable/), используемая для атомизации строк. Если это **nullptr**, используется таблица имён, применённая при построении **nsMgr**. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../../xmlnametable/). |
| nsMgr | const SharedPtr\<XmlNamespaceManager\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для поиска информации о пространствах имён, или **nullptr**. |
| xmlLang | const String\& | Область **xml:lang**. |
| xmlSpace | System::Xml::XmlSpace | Значение [XmlSpace](../../xmlspace/) указывает область **xml:space**. |
| enc | const SharedPtr\<System::Text::Encoding\>\& | Объект Encoding, указывающий настройку кодировки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
