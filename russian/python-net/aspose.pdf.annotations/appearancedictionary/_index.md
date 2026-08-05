---
title: "AppearanceDictionary"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Словарь внешнего вида аннотации, указывающий, как аннотация должна отображаться визуально на странице."
type: docs
weight: 60
url: /ru/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Словарь внешнего вида аннотации, указывающий, как аннотация должна отображаться визуально на странице.

Тип AppearanceDictionary раскрывает следующие члены:
## Свойства
| Имя | Описание |
| :- | :- |
| is_fixed_size | Получает значение, указывающее, имеет ли словарь фиксированный размер. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | Значения D).state,<br/>            где N — обычное отображение, R — отображение при наведении, D — отображение при нажатии, а state — имя состояния<br/>            (например, On, Off для флажков). |
| значения | Получает список значений словаря. <br/>            Коллекция Result содержит список объектов XForm. |
| is_synchronized | Получает значение, указывающее, синхронизирован ли доступ к словарю (потокобезопасный). |
| sync_root | Получает объект, который можно использовать для синхронизации доступа к словарю. |
## Методы
| Имя | Описание |
| :- | :- |
| add(key, value) | Добавляет элемент с указанным ключом и значением. |
| add(key, value) | Добавить X-форму для указанного ключа. |
| copy_to(array, index) | Копирует элементы словаря в массив, начиная с указанного индекса массива. |
| contains_key(key) | Определяет, содержит ли этот словарь указанный ключ. |
| remove(key) | Удаляет ключ из словаря. |
| try_get_value(key, value) | Пытается найти ключ в словаре и получить значение, если найдено. |

### См. также

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

