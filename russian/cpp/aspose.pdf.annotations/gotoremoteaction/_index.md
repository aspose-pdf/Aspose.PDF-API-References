---
title: "Aspose::Pdf::Annotations::GoToRemoteAction класс"
linktitle: "GoToRemoteAction"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::GoToRemoteAction класс. Представляет удалённое действие перехода, аналогичное обычному действию перехода, но переходит к назначению в другом PDF‑файле вместо текущего файла в C++."
type: docs
weight: 4400
url: /ru/cpp/aspose.pdf.annotations/gotoremoteaction/
---
## GoToRemoteAction class


Представляет удалённое действие перехода (go-to), аналогичное обычному действию перехода, но переходящее к точке назначения в другом PDF‑файле вместо текущего.

```cpp
class GoToRemoteAction : public Aspose::Pdf::Annotations::GoToAction
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Destination](./get_destination/)() override | Получает назначение для перехода. |
| [get_File](./get_file/)() | Получает спецификацию файла, в котором находится назначение. |
| [get_NewWindow](./get_newwindow/)() | Получает флаг, указывающий, открывать ли документ назначения в новом окне. |
| [GoToRemoteAction](./gotoremoteaction/)(const System::String\&, int32_t) | Инициализирует объект [GoToRemoteAction](./). |
| [GoToRemoteAction](./gotoremoteaction/)(const System::String\&, const System::SharedPtr\<ExplicitDestination\>\&) | Инициализирует объект [GoToRemoteAction](./). |
| [set_Destination](./set_destination/)(System::SharedPtr\<IAppointment\>) override | Устанавливает назначение для перехода. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | Устанавливает спецификацию файла, в котором находится назначение. |
| [set_NewWindow](./set_newwindow/)(ExtendedBoolean) | Устанавливает флаг, указывающий, открывать ли документ назначения в новом окне. |
## См. также

* Class [GoToAction](../gotoaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
