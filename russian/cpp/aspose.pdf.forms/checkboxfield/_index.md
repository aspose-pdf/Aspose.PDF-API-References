---
title: "Aspose::Pdf::Forms::CheckboxField класс"
linktitle: "CheckboxField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::CheckboxField класс. Класс, представляющий поле флажка в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.forms/checkboxfield/
---
## CheckboxField class


Класс, представляющий поле флажка.

```cpp
class CheckboxField : public Aspose::Pdf::Forms::Field
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddOption](./addoption/)(const System::String\&) | Добавляет новый флажок в группу флажков, в которой одновременно может быть отмечен не более одного флажка. Новый флажок добавляется в нижнюю часть группы. |
| [AddOption](./addoption/)(const System::String\&, const System::SharedPtr\<Rectangle\>\&) | Добавляет новый флажок в группу флажков, в которой одновременно может быть отмечен не более одного флажка. |
| [AddOption](./addoption/)(const System::String\&, int32_t, const System::SharedPtr\<Rectangle\>\&) | Добавляет новый флажок в группу флажков, в которой одновременно может быть отмечен не более одного флажка. |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор класса [CheckboxField](./). |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Rectangle\>\&) | Конструктор класса [CheckboxField](./). |
| [CheckboxField](./checkboxfield/)() | Создать экземпляр [CheckboxField](./). |
| [CheckboxField](./checkboxfield/)(const System::SharedPtr\<Document\>\&) | Конструктор для использования с Generator. |
| [Clone](./clone/)() override | Клонировать флажок. |
| [get_ActiveState](./get_activestate/)() override | Получает текущее состояние внешнего вида аннотации. |
| [get_AllowedStates](./get_allowedstates/)() | Возвращает список разрешённых состояний. |
| [get_Checked](./get_checked/)() | Получает состояние флажка. |
| [get_ExportValue](./get_exportvalue/)() | Получает экспортное значение поля CheckBox. |
| [get_Style](./get_style/)() | Получает стиль флажка. |
| [get_Value](./get_value/)() override | Получает значение поля флажка. |
| [set_ActiveState](./set_activestate/)(System::String) override | Устанавливает текущее состояние внешнего вида аннотации. |
| [set_Checked](./set_checked/)(bool) | Устанавливает состояние флажка. |
| [set_ExportValue](./set_exportvalue/)(const System::String\&) | Устанавливает экспортное значение поля CheckBox. |
| [set_Style](./set_style/)(BoxStyle) | Устанавливает стиль флажка. |
| [set_Value](./set_value/)(System::String) override | Устанавливает значение поля флажка. |
## См. также

* Class [Field](../field/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
