---
title: System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength method
linktitle: GetTransferCodingLength
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength method. Converts a passed string from the specified index to an instance of the TransferCodingHeaderValue class in C++.'
type: docs
weight: 700
url: /cpp/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength method


Converts a passed string from the specified index to an instance of the [TransferCodingHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | String | A string to parse. |
| startIndex | int32_t | A start position for parsing. |
| parsedValue | const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\& | An instance where a parsed object will be assigned. |
| transferCodingCreator | System::SharedPtr\<TransferCodingHeaderValue\>\& | The delegate that is used to create instances of the [TransferCodingHeaderValue](../) class. |

### ReturnValue

Returns the length of a parsed substring, otherwise 0.

## See Also

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TransferCodingHeaderValue](../)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
