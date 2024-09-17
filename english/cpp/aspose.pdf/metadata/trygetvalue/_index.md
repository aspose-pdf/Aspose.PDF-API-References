---
title: Aspose::Pdf::Metadata::TryGetValue method
linktitle: TryGetValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Metadata::TryGetValue method. Tries to find key in the dictionary and retreives value if found in C++.'
type: docs
weight: 2200
url: /cpp/aspose.pdf/metadata/trygetvalue/
---
## Metadata::TryGetValue method


Tries to find key in the dictionary and retreives value if found.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Metadata::TryGetValue(const System::String &key, System::SharedPtr<XmpValue> &value) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key to search in the dictionary. |
| value | System::SharedPtr\<XmpValue\>\& | Retreived value. |

### ReturnValue

true if key was found.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key to search in the dictionary.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Retreived value.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
