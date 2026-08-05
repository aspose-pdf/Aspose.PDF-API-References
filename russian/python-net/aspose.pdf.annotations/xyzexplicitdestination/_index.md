---
title: "XYZExplicitDestination"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет явное назначение, которое отображает страницу с координатами (left, top), расположенными в левом верхнем углу окна, и содержимое страницы увеличивается в соответствии с коэффициентом zoom. Значение null для любого из параметров left, top или zoom указывает, что текущее значение этого параметра должно оставаться без изменений. Значение zoom, равное 0, имеет то же значение, что и null."
type: docs
weight: 880
url: /ru/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Представляет явное назначение, которое отображает страницу с координатами (left, top), расположенными в левом верхнем углу окна, и содержимое страницы увеличивается в соответствии с коэффициентом zoom. Значение null для любого из параметров left, top или zoom указывает, что текущее значение этого параметра должно оставаться без изменений. Значение zoom, равное 0, имеет то же значение, что и null.

Тип XYZExplicitDestination раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | Инициализирует новый экземпляр класса XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | Инициализирует новый экземпляр класса XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | Инициализирует новый экземпляр класса XYZExplicitDestination |
## Свойства
| Имя | Описание |
| :- | :- |
| страница | Получает объект целевой страницы |
| page_number | Получает номер целевой страницы |
| left | Получает горизонтальную координату слева верхнего левого угла окна. |
| top | Получает вертикальную координату сверху верхнего левого угла окна. |
| zoom | Получает коэффициент масштабирования. |
## Методы
| Имя | Описание |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Создайте назначение в указанное место страницы, учитывая поворот страницы, если требуется. |
| create_destination(page, type, values) | Создаёт экземпляры наследников класса ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Создаёт экземпляры наследников класса ExplicitDestination. |
| create_destination(page_number, type, values) | Создаёт экземпляры наследников класса ExplicitDestination. |
| create_destination_to_upper_left_corner(page, zoom) | Создайте назначение в верхний левый угол указанной страницы. |
| create_destination_to_upper_left_corner(page) | Создайте назначение в верхний левый угол указанной страницы. |
| to_string() | Преобразует состояние объекта в строковое значение. Пример: "1 XYZ 100 200 3". |

### См. также

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

