---
title: "System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength method"
linktitle: "GetTransferCodingLength"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength method. Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса TransferCodingHeaderValue в C++."
type: docs
weight: 700
url: /ru/cpp/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength method


Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | String | Строка для разбора. |
| startIndex | int32_t | Начальная позиция для разбора. |
| parsedValue | const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\& | Экземпляр, в который будет присвоен разобранный объект. |
| transferCodingCreator | System::SharedPtr\<TransferCodingHeaderValue\>\& | Делегат, используемый для создания экземпляров класса [TransferCodingHeaderValue](../). |

### ReturnValue

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TransferCodingHeaderValue](../)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
