---
title: Aspose::Pdf::CollectionItem::TryGetTextValue method
linktitle: TryGetTextValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionItem::TryGetTextValue method. Tries to get the text value with the specified name from the collection item in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/collectionitem/trygettextvalue/
---
## CollectionItem::TryGetTextValue method


Tries to get the text value with the specified name from the collection item.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::CollectionItem::TryGetTextValue(System::String name, System::SharedPtr<CollectionItem::Value<System::String>> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | System::String | The name of the text value. |
| value | System::SharedPtr\<CollectionItem::Value\<System::String\>\>\& | When this method returns, contains the text value associated with the specified name, if the name is found; otherwise, null. |

### ReturnValue

true if the text value with the specified name is found; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>name</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The name of the text value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>When this method returns, contains the text value associated with the specified name, if the name is found; otherwise, null.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
