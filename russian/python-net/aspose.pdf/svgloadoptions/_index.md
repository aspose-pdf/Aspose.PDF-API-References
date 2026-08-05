---
title: "SvgLoadOptions"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет параметры загрузки/импорта SVG‑файла в PDF‑документ."
type: docs
weight: 1450
url: /ru/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

Представляет параметры загрузки/импорта SVG‑файла в PDF‑документ.

Тип SvgLoadOptions раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| SvgLoadOptions() | Инициализирует новый экземпляр класса SvgLoadOptions |
## Свойства
| Имя | Описание |
| :- | :- |
| warning_handler | Обратный вызов для обработки любых сгенерированных предупреждений. <br/>            WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. <br/>            Continue является действием по умолчанию, и операция Load продолжается, однако пользователь также может вернуть Abort, в этом случае операция Load должна быть прекращена. |
| load_format | Представляет файловый формат, который описывается в [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| page_info | Получает или задаёт информацию о странице, которая должна применяться при загрузке документа.<br/>            ПРИМЕЧАНИЕ, что этот параметр работает только когда ConversionEngine == ConversionEngines.NewEngine |
| adjust_page_size | Регулирует размер pdf‑страницы до размера svg |
| conversion_engine | Позволяет выбрать движок конвертации, который будет использоваться во время преобразования.<br/>            В настоящее время новый движок находится в стадии B‑тестирования, поэтому это значение по умолчанию устанавливается в <br/>            ConversionEngines.LegacyEngine |

### См. также

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

