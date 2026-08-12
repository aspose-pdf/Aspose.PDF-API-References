---
title: "System::Drawing::StringFormat класс"
linktitle: "StringFormat"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::StringFormat класс. Инкапсулирует информацию о размещении текста, манипуляции отображением и функции OpenType. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2500
url: /ru/cpp/system.drawing/stringformat/
---
## StringFormat class


Инкапсулирует информацию о размещении текста, манипуляции отображением и функции OpenType. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class StringFormat : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() | Возвращает точную копию текущего объекта. |
| [get_Alignment](./get_alignment/)() const | Возвращает значение, указывающее горизонтальное выравнивание строки. |
| [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Возвращает значение, указывающее язык, используемый при замене локальных цифр на западные цифры. |
| [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Возвращает метод замены цифр. |
| [get_FormatFlags](./get_formatflags/)() const | Возвращает побитовое сочетание [StringFormatFlags](../stringformatflags/), которое задаёт формат строки, представленный текущим объектом. |
| static [get_GenericDefault](./get_genericdefault/)() | Возвращает объект [StringFormat](./), представляющий общий формат по умолчанию. |
| static [get_GenericTypographic](./get_generictypographic/)() | Возвращает объект [StringFormat](./), представляющий общий типографический формат. |
| [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Возвращает значение, указывающее, как отображается префикс горячей клавиши. |
| [get_LineAlignment](./get_linealignment/)() const | Возвращает значение, указывающее вертикальное выравнивание строки. |
| [get_Trimming](./get_trimming/)() const | Возвращает значение, указывающее, как обрезается строка. |
| [GetCharacterRangesCount](./getcharacterrangescount/)() const | Получает размер массива [CharacterRange](../characterrange/). |
| [GetTabStops](./gettabstops/)(float\&) const | Возвращает позиции табуляции для текущего объекта [StringFormat](./). |
| [set_Alignment](./set_alignment/)(StringAlignment) | Устанавливает горизонтальное выравнивание строки. |
| [set_FormatFlags](./set_formatflags/)(StringFormatFlags) | Устанавливает флаги формата строки. |
| [set_HotkeyPrefix](./set_hotkeyprefix/)(Text::HotkeyPrefix) | Устанавливает значение, определяющее, как должен отображаться префикс горячей клавиши. |
| [set_LineAlignment](./set_linealignment/)(StringAlignment) | Устанавливает вертикальное выравнивание строки. |
| [set_Trimming](./set_trimming/)(StringTrimming) | Устанавливает значение, определяющее, как обрезается строка. |
| [SetDigitSubstitution](./setdigitsubstitution/)(int32_t, StringDigitSubstitute) | Устанавливает язык и метод замены цифр. |
| [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const ArrayPtr\<CharacterRange\>\&) | Устанавливает массив объектов [CharacterRange](../characterrange/), представляющих диапазоны символов, измеренные вызовом метода MeasureCharacterRanges(). |
| [SetTabStops](./settabstops/)(float, const ArrayPtr\<float\>\&) | Устанавливает позиции табуляции для текущего объекта [StringFormat](./). |
| [StringFormat](./stringformat/)() | Создаёт новый экземпляр класса [StringFormat](./). |
| [StringFormat](./stringformat/)(StringFormatFlags, int32_t) | Создаёт новый экземпляр класса [StringFormat](./) с указанными флагами формата и языком. |
| [StringFormat](./stringformat/)(const SharedPtr\<StringFormat\>\&) | Конструктор копирования. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
