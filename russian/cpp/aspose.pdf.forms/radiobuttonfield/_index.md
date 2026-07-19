---
title: "Aspose::Pdf::Forms::RadioButtonField класс"
linktitle: "RadioButtonField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::RadioButtonField класс. Класс, представляющий поле переключателя в C++."
type: docs
weight: 2100
url: /ru/cpp/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class


Класс, представляющий поле радиокнопки.

```cpp
class RadioButtonField : public Aspose::Pdf::Forms::ChoiceField
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<RadioButtonOptionField\>\&) | Добавляет новое поле опции к полю RadioButton. |
| [AddOption](./addoption/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Добавить опцию переключателя с указанным прямоугольником. |
| [AddOption](./addoption/)(System::String) override | Добавить опцию к переключателю. |
|  | [get_NoToggleToOff](./get_notoggletooff/)() | Получает или задает флаг, позволяющий переключателю не иметь выбранного значения. Если **true** |

, в любой момент должен быть выбран ровно один переключатель; выбор уже выбранного переключателя не оказывает эффекта. Если **false**

, щелчок по выбранному переключателю снимает выделение, оставляя все переключатели невыбранными. |
| [get_Options](./get_options/)() override | Получает коллекцию вариантов радиокнопки. |
| [get_PageIndex](./get_pageindex/)() override | Получает индекс страницы, содержащей это поле RadioButton. |
| [get_Selected](./get_selected/)() override | Получает индекс выбранного элемента. Нумерация элементов начинается с 1. |
| [get_Style](./get_style/)() | Стиль поля. |
| [get_Value](./get_value/)() override | Получает значение поля. |
| [RadioButtonField](./radiobuttonfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&) | Конструктор для RadiouttonField. |
| [RadioButtonField](./radiobuttonfield/)(const System::SharedPtr\<Document\>\&) | Конструктор для [RadioButtonField](./). |
|  | [set_NoToggleToOff](./set_notoggletooff/)(bool) | Получает или задает флаг, позволяющий переключателю не иметь выбранного значения. Если **true** |

, в любой момент должен быть выбран ровно один переключатель; выбор уже выбранного переключателя не оказывает эффекта. Если **false**

, щелчок по выбранному переключателю снимает выделение, оставляя все переключатели невыбранными. |
| [set_Selected](./set_selected/)(int32_t) override | Устанавливает индекс выбранного элемента. Нумерация элементов начинается с 1. |
| [set_Style](./set_style/)(BoxStyle) | Стиль поля. |
| [set_Value](./set_value/)(System::String) override | Устанавливает значение поля. |
| [SetPosition](./setposition/)(System::SharedPtr\<Point\>) override | Перемещает все подпункты радиокнопки в указанные позиции на странице. |
## См. также

* Class [ChoiceField](../choicefield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
