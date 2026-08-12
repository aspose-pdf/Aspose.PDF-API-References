---
title: "Aspose::Pdf::XForm класс"
linktitle: "XForm"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::XForm класс. Класс представляет XForm в C++."
type: docs
weight: 19500
url: /ru/cpp/aspose.pdf/xform/
---
## XForm class


Класс представляет [XForm](./).

```cpp
class XForm : public System::IDisposable,
              public Aspose::Pdf::ISupportsMemoryCleanup,
              public Aspose::Pdf::IOperatorContainer
```

## Методы

| Метод | Описание |
| --- | --- |
| static [CreateNewForm](./createnewform/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Document\>\&) | Создаёт [XForm](./), который дублирует содержимое страницы. |
| [Dispose](./dispose/)() override | Освобождает память. |
| [FreeMemory](./freememory/)() override | Очищает кэшированные данные. |
| [get_BBox](./get_bbox/)() | Получает ограничивающий прямоугольник формы. |
| [get_Contents](./get_contents/)() override | Получает операторы формы. |
| [get_IT](./get_it/)() | Получает IT формы. IT формы — это имя, описывающее назначение XObject. |
| [get_Matrix](./get_matrix/)() | Получает матрицу формы. |
| [get_Name](./get_name/)() | Получает имя формы. Имя формы — это имя, используемое для ссылки на форму в словаре XObject в ресурсах страницы. |
| [get_Opi](./get_opi/)() | Получает Open Prepress Interface (OPI). |
| [get_Rectangle](./get_rectangle/)() | Получает прямоугольник формы. |
| [get_Resources](./get_resources/)() override | Получает ресурсы Form XObject. |
| [get_Subtype](./get_subtype/)() | Получает подтип формы. |
| [GetResources](./getresources/)(bool) | Возвращает ресурсы Form X-Object. |
| [GetResources](./getresources/)() override | Возвращает ресурсы Form X-Object. Если у Form нет ресурсов и allowCreate равно true, [Resources](../resources/) будут автоматически созданы для формы. |
| [set_BBox](./set_bbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает ограничивающий прямоугольник формы. |
| [set_Matrix](./set_matrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | Устанавливает матрицу формы. |
| [set_Name](./set_name/)(const System::String\&) | Устанавливает имя формы. Имя формы — это имя, которое используется для ссылки на форму в словаре XObejct ductionary в ресурсах страницы. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Class [IOperatorContainer](../ioperatorcontainer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
