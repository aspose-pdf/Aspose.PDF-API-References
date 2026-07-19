---
title: "System::Xml::Schema::XmlSchemaElement класс"
linktitle: "XmlSchemaElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Xml::Schema::XmlSchemaElement класс. Представляет элемент element из XML Schema, как указано Всемирным консорциумом паутины (W3C). Этот класс является базовым классом для всех типов частиц и используется для описания элемента в XML‑документе в C++."
type: docs
weight: 2600
url: /ru/cpp/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement class


Представляет элемент **element** из XML [Schema](../) в соответствии с Всемирным консорциумом [Web](../../system.web/) (W3C). Этот класс является базовым классом для всех типов частиц и используется для описания элемента в XML‑документе.

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Block](./get_block/)() | Возвращает производное **Block**. |
| [get_BlockResolved](./get_blockresolved/)() | Возвращает посткомпиляционную интерпретацию значения **Block**. |
| [get_Constraints](./get_constraints/)() | Возвращает коллекцию ограничений элемента. |
| [get_DefaultValue](./get_defaultvalue/)() | Возвращает значение по умолчанию элемента, если его содержимое является простым типом или содержимое элемента — **textOnly**. |
| [get_ElementSchemaType](./get_elementschematype/)() | Возвращает объект [XmlSchemaType](../xmlschematype/), представляющий тип элемента на основе значений [XmlSchemaElement::get_SchemaType](./get_schematype/) или [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) элемента. |
| [get_ElementType](./get_elementtype/)() | Возвращает объект на основе [XmlSchemaElement](./) или [XmlSchemaElement](./) элемента, который содержит посткомпиляционную интерпретацию значения **ElementType**. |
| [get_Final](./get_final/)() | Возвращает значение **Final**, указывающее, что дальнейшие производные недопустимы. |
| [get_FinalResolved](./get_finalresolved/)() | Возвращает посткомпиляционную интерпретацию значения **Final**. |
| [get_FixedValue](./get_fixedvalue/)() | Возвращает фиксированное значение. |
| [get_Form](./get_form/)() | Возвращает форму элемента. |
| [get_IsAbstract](./get_isabstract/)() | Возвращает информацию, указывающую, может ли элемент использоваться в документе‑экземпляре. |
| [get_IsNillable](./get_isnillable/)() | Возвращает информацию, указывающую, может ли **xsi:nil** встречаться в данных экземпляра. Указывает, может ли элементу быть присвоено явное значение nil. |
| [get_Name](./get_name/)() | Возвращает имя элемента. |
| [get_QualifiedName](./get_qualifiedname/)() | Возвращает фактическое квалифицированное имя данного элемента. |
| [get_RefName](./get_refname/)() | Возвращает ссылочное имя элемента, объявленного в этой схеме (или в другой схеме, указанной заданным пространством имён). |
| [get_SchemaType](./get_schematype/)() | Возвращает тип элемента. Это может быть сложный тип или простой тип. |
| [get_SchemaTypeName](./get_schematypename/)() | Возвращает имя встроенного типа данных, определённого в этой схеме или в другой схеме, указанной заданным пространством имён. |
| [get_SubstitutionGroup](./get_substitutiongroup/)() | Возвращает имя элемента, который заменяется этим элементом. |
| [set_Block](./set_block/)(XmlSchemaDerivationMethod) | Устанавливает производное **Block**. |
| [set_DefaultValue](./set_defaultvalue/)(const String\&) | Устанавливает значение по умолчанию элемента, если его содержимое является простым типом или содержимое элемента — **textOnly**. |
| [set_Final](./set_final/)(XmlSchemaDerivationMethod) | Устанавливает значение **Final**, указывающее, что дальнейшие производные недопустимы. |
| [set_FixedValue](./set_fixedvalue/)(const String\&) | Устанавливает фиксированное значение. |
| [set_Form](./set_form/)(XmlSchemaForm) | Устанавливает форму элемента. |
| [set_IsAbstract](./set_isabstract/)(bool) | Устанавливает информацию, указывающую, может ли элемент использоваться в документе‑экземпляре. |
| [set_IsNillable](./set_isnillable/)(bool) | Устанавливает информацию, указывающую, может ли **xsi:nil** встречаться в данных экземпляра. Указывает, может ли элементу быть присвоено явное значение nil. |
| [set_Name](./set_name/)(const String\&) | Устанавливает имя элемента. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает ссылочное имя элемента, объявленного в этой схеме (или в другой схеме, указанной заданным пространством имён). |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaType\>\&) | Устанавливает тип элемента. Это может быть сложный тип или простой тип. |
| [set_SchemaTypeName](./set_schematypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя встроенного типа данных, определённого в этой схеме или в другой схеме, указанной заданным пространством имён. |
| [set_SubstitutionGroup](./set_substitutiongroup/)(const SharedPtr\<XmlQualifiedName\>\&) | Устанавливает имя элемента, который заменяется этим элементом. |
| [XmlSchemaElement](./xmlschemaelement/)() | Инициализирует новый экземпляр класса [XmlSchemaElement](./). |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |
## Примечания



Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

## См. также

* Class [XmlSchemaParticle](../xmlschemaparticle/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
