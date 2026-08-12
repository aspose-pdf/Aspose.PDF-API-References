---
title: "System::Security::SecurityElement clase"
linktitle: "SecurityElement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Security::SecurityElement clase. Modelo de objeto XML para codificar objetos de seguridad. No implementado. Los objetos de esta clase solo deben ser asignados usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.security/securityelement/
---
## SecurityElement class


Modelo de objeto XML para codificar objetos de seguridad. No implementado. Los objetos de esta clase solo deben ser asignados usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class SecurityElement : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddAttribute](./addattribute/)(const String\&, const String\&) | Añade un atributo a la etiqueta. |
| [AddChild](./addchild/)(SecurityElement) | Añade una etiqueta hija. |
| [Attribute](./attribute/)(const String\&) | Obtiene el valor del atributo. |
| [Copy](./copy/)() | Clona la etiqueta. |
| [Equal](./equal/)(SecurityElement) | Comprueba la igualdad de parámetros. |
| static [Escape](./escape/)(const String\&) | Escapa caracteres en la cadena XML. |
| static [FromString](./fromstring/)(const String\&) | Crea un elemento a partir del código XML. |
| [get_Attributes](./get_attributes/)() | Obtiene los atributos de la etiqueta. |
| [get_Children](./get_children/)() | Obtiene los objetos hijos de la etiqueta. |
| [get_Tag](./get_tag/)() | Obtiene el nombre de la etiqueta. |
| [get_Text](./get_text/)() | Obtiene el texto interno de la etiqueta. |
| static [IsValidAttributeName](./isvalidattributename/)(const String\&) | Comprueba si el nombre del atributo es válido. |
| static [IsValidAttributeValue](./isvalidattributevalue/)(const String\&) | Comprueba si el valor del atributo es válido. |
| static [IsValidTag](./isvalidtag/)(const String\&) | Comprueba si la etiqueta es válida. |
| static [IsValidText](./isvalidtext/)(const String\&) | Comprueba si el texto es válido. |
| [SearchForChildByTag](./searchforchildbytag/)(const String\&) | Obtiene la etiqueta hija por nombre. |
| [SearchForTextOfTag](./searchfortextoftag/)(const String\&) | Obtiene el texto interno de la etiqueta hija por nombre de etiqueta. |
| [SecurityElement](./securityelement/)(const String\&) | Constructor. |
| [SecurityElement](./securityelement/)(const String\&, const String\&) | Constructor. |
| [set_Attributes](./set_attributes/)(System::Collections::Generic::Dictionary\<String, String\>) | Establece los atributos de la etiqueta. |
| [set_Children](./set_children/)(System::Collections::Generic::List\<SecurityElement\>) | Establece los objetos hijos de la etiqueta. |
| [set_Tag](./set_tag/)(const String\&) | Establece el nombre de la etiqueta. |
| [set_Text](./set_text/)(const String\&) | Establece el texto interno de la etiqueta. |
| [ToString](./tostring/)() const override | Convierte la etiqueta a cadena. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Security](../)
* Library [Aspose.PDF for C++](../../)
