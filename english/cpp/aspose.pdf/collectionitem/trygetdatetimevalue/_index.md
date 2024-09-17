---
title: Aspose::Pdf::CollectionItem::TryGetDateTimeValue method
linktitle: TryGetDateTimeValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionItem::TryGetDateTimeValue method. Tries to get the value of type DateTime from the collection item by the specified name in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf/collectionitem/trygetdatetimevalue/
---
## CollectionItem::TryGetDateTimeValue method


Tries to get the value of type DateTime from the collection item by the specified name.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::CollectionItem::TryGetDateTimeValue(System::String name, System::SharedPtr<CollectionItem::Value<System::DateTime>> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | System::String | The name of the value to retrieve. |
| value | System::SharedPtr\<CollectionItem::Value\<System::DateTime\>\>\& | When this method returns, contains the value associated with the specified name, if the name is found; otherwise, null. This parameter is passed uninitialized. |

### ReturnValue

true if the value associated with the specified name is successfully retrieved; otherwise, false.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>name</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The name of the value to retrieve.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>When this method returns, contains the value associated with the specified name, if the name is found; otherwise, null. This parameter is passed uninitialized.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
