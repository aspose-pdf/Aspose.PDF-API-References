---
title: "Clase System::Drawing::StringFormat"
linktitle: "StringFormat"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::StringFormat. Encapsula información de diseño de texto, manipulaciones de visualización y características OpenType. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2500
url: /es/cpp/system.drawing/stringformat/
---
## StringFormat class


Encapsula información de diseño de texto, manipulaciones de visualización y características OpenType. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class StringFormat : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() | Devuelve una copia exacta del objeto actual. |
| [get_Alignment](./get_alignment/)() const | Devuelve un valor que indica la alineación horizontal de la cadena. |
| [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Devuelve un valor que indica el idioma que se utiliza cuando los dígitos locales se sustituyen por dígitos occidentales. |
| [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Devuelve el método de sustitución de dígitos. |
| [get_FormatFlags](./get_formatflags/)() const | Devuelve una combinación bit a bit de [StringFormatFlags](../stringformatflags/) que especifica el formato de cadena representado por el objeto actual. |
| static [get_GenericDefault](./get_genericdefault/)() | Devuelve un objeto [StringFormat](./) que representa un formato predeterminado genérico. |
| static [get_GenericTypographic](./get_generictypographic/)() | Devuelve un objeto [StringFormat](./) que representa un formato tipográfico genérico. |
| [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Devuelve el valor que indica cómo se muestra el prefijo de tecla de acceso rápido. |
| [get_LineAlignment](./get_linealignment/)() const | Devuelve un valor que indica la alineación vertical de la cadena. |
| [get_Trimming](./get_trimming/)() const | Devuelve un valor que indica cómo se recorta la cadena. |
| [GetCharacterRangesCount](./getcharacterrangescount/)() const | Obtiene el tamaño de la matriz [CharacterRange](../characterrange/). |
| [GetTabStops](./gettabstops/)(float\&) const | Devuelve los tabuladores del objeto [StringFormat](./) actual. |
| [set_Alignment](./set_alignment/)(StringAlignment) | Establece la alineación horizontal de la cadena. |
| [set_FormatFlags](./set_formatflags/)(StringFormatFlags) | Establece los indicadores de formato de cadena. |
| [set_HotkeyPrefix](./set_hotkeyprefix/)(Text::HotkeyPrefix) | Establece el valor que especifica cómo debe mostrarse el prefijo de tecla de acceso rápido. |
| [set_LineAlignment](./set_linealignment/)(StringAlignment) | Establece la alineación vertical de la cadena. |
| [set_Trimming](./set_trimming/)(StringTrimming) | Establece un valor que especifica cómo se recorta la cadena. |
| [SetDigitSubstitution](./setdigitsubstitution/)(int32_t, StringDigitSubstitute) | Establece el idioma y el método de sustitución de dígitos. |
| [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const ArrayPtr\<CharacterRange\>\&) | Establece una matriz de objetos [CharacterRange](../characterrange/) que representan los rangos de caracteres medidos mediante una llamada al método MeasureCharacterRanges(). |
| [SetTabStops](./settabstops/)(float, const ArrayPtr\<float\>\&) | Establece los tabuladores para el objeto [StringFormat](./) actual. |
| [StringFormat](./stringformat/)() | Construye una nueva instancia de la clase [StringFormat](./). |
| [StringFormat](./stringformat/)(StringFormatFlags, int32_t) | Construye una nueva instancia de la clase [StringFormat](./) con los indicadores de formato y el idioma especificados. |
| [StringFormat](./stringformat/)(const SharedPtr\<StringFormat\>\&) | Constructor de copia. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
