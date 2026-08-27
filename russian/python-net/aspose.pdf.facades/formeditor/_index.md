---
title: "FormEditor"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Класс для редактирования форм (добавление/удаление полей и т.д.)"
type: docs
weight: 110
url: /ru/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Класс для редактирования форм (добавление/удаление полей и т.д.)

Тип FormEditor раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| FormEditor(src_stream, dest_stream) | Инициализирует новый экземпляр класса FormEditor |
| FormEditor(src_file_name, dest_file_name) | Инициализирует новый экземпляр класса FormEditor |
| FormEditor() | Конструктор для FormEditor. |
| FormEditor(document) | Инициализирует новый экземпляр класса FormEditor |
| FormEditor(document, dest_file_name) | Инициализирует новый экземпляр класса FormEditor |
| FormEditor(document, dest_stream) | Инициализирует новый экземпляр класса FormEditor |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
| src_file_name | Получает или задает имя исходного файла. |
| dest_file_name | Получает или задает имя файла назначения. |
| src_stream | Получает или задает исходный поток. |
| dest_stream | Получает или задает поток назначения. |
| items | Устанавливает элементы, которые будут добавлены в только что созданный список или комбобокс. |
| export_items | Устанавливает параметры для комбобокса с экспортируемыми значениями. |
| facade | Устанавливает визуальные атрибуты поля. |
| radio_gap | Элемент, фиксирующий расстояние между двумя соседними радиокнопками в пикселях, по умолчанию 50. |
| radio_horiz | Флаг, указывающий, расположены ли радиокнопки горизонтально или вертикально, значение по умолчанию — true. |
| radio_button_item_size | Получает или задает размер элемента радиокнопки (при добавлении нового поля радиокнопки). |
| submit_flag | Устанавливает флаги отправки кнопки отправки. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(src_file) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_stream) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_doc) | Привязывает PDF-документ для редактирования. |
| save() | Сохраняет изменения в целевой файл. |
| save(dest_file) | Сохраняет изменения в целевой файл. |
| save(dest_stream) | Сохраняет изменения в целевой файл. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Добавляет поле указанного типа в форму. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Добавляет поле указанного типа в форму. |
| copy_inner_field(field_name, new_field_name, page_num) | Копирует существующее поле в то же положение на указанном номере страницы.<br/>            Новый документ будет создан, содержащий всё, что есть в исходном документе, за исключением только что скопированного поля. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Копирует существующее поле в новое положение, указанное номером страницы и координатами.<br/>            Новый документ будет создан, содержащий всё, что есть в исходном документе, за исключением только что скопированного поля. |
| copy_outer_field(src_file_name, field_name) | Копирует существующее поле из одного PDF-документа в другой документ с оригинальным номером страницы и координатами.<br/>            Примечание: Только для полей AcroForm (исключая переключатели). |
| copy_outer_field(src_file_name, field_name, page_num) | Копирует существующее поле из одного PDF-документа в другой документ с указанным номером страницы и оригинальными координатами.<br/>             Примечание: Только для полей AcroForm (исключая переключатели). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Копирует существующее поле из одного PDF-документа в другой документ с указанным номером страницы и координатами.<br/>            Примечание: Только для полей AcroForm (исключая переключатели). |
| decorate_field(field_name) | Изменяет визуальные атрибуты указанного поля. |
| decorate_field(field_type) | Изменяет визуальные атрибуты всех полей указанного типа. |
| decorate_field() | Изменяет визуальные атрибуты указанного поля. |
| add_list_item(field_name, item_name) | Добавляет новый элемент в список. |
| add_list_item(field_name, export_name) | Добавьте новый элемент со значением Export в существующее поле списка, только для поля комбобокса AcroForm. |
| close() | Закрывает фасад. |
| set_field_attribute(field_name, flag) | Устанавливает атрибуты поля. |
| set_field_appearance(field_name, flags) | Устанавливает флаги поля |
| get_field_appearance(field_name) | Получает флаги поля. |
| set_submit_flag(field_name, submit_form_flag) | Устанавливает флаг отправки для кнопки отправки. |
| set_submit_url(field_name, url) | Устанавливает URL кнопки. |
| set_field_limit(field_name, field_limit) | Устанавливает максимальное количество символов текстового поля. |
| set_field_comb_number(field_name, comb_number) | Устанавливает количество ячеек для обычного однострочного текстового поля (поле <br/>            автоматически делится на столько равноотстоящих позиций, или ячеек, <br/>            сколько указано в параметре combNumber). |
| move_field(field_name, llx, lly, urx, ury) | Устанавливает новое положение поля. |
| remove_field(field_name) | Удаляет поле из формы. |
| reset_facade() | Сбросить все визуальные атрибуты к пустому значению. |
| reset_inner_facade() | Сбросить все визуальные атрибуты внутреннего фасада к пустому значению. |
| rename_field(field_name, new_field_name) | Изменить имя поля. |
| remove_field_action(field_name) | Удалить действие отправки поля. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Добавить кнопку отправки на форму. |
| del_list_item(field_name, item_name) | Удалить элемент из списка поля. |
| set_field_script(field_name, script) | Установить JavaScript для поля PushButton. Если существовал старый JavaScript, он будет заменён новым. |
| add_field_script(field_name, script) | Добавить JavaScript для поля PushButton. Если существует старое событие, новое событие будет добавлено после него. |
| single_2_multiple(field_name) | Преобразовать однострочное текстовое поле в многострочное. |
| set_field_alignment(field_name, alignment) | Установить стиль выравнивания текстового поля. |
| set_field_alignment_v(field_name, alignment) | Установить стиль вертикального выравнивания текстового поля. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

