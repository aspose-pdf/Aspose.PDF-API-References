---
title: Aspose::Pdf::Metadata::Contains method
linktitle: Contains
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Metadata::Contains method. Checks does key is contained in metadata in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf/metadata/contains/
---
## Metadata::Contains(const System::String\&) const method


Checks does key is contained in metadata.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Metadata::Contains(const System::String &key) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | The key of entry to find. |

### ReturnValue

True if key is contained in the metadata.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The key of entry to find.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Contains(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const method


Checks does specified key-value pair is contained in the dictionary.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Metadata::Contains(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Key-value pair. |

### ReturnValue

true if this pauir was found.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>item</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key-value pair.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
