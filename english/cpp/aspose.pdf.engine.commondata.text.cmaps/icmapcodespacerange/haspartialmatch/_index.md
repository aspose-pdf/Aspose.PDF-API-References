---
title: Aspose::Pdf::Engine::CommonData::Text::CMaps::ICMapCodeSpaceRange::HasPartialMatch method
linktitle: HasPartialMatch
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Engine::CommonData::Text::CMaps::ICMapCodeSpaceRange::HasPartialMatch method. Detects is the passed raw code represented in byte array form has a partial match with CMap''s codespace ranges - partial match means that first element(s) in array is in range(s) but all the raw code bytes are not fully in any range in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.engine.commondata.text.cmaps/icmapcodespacerange/haspartialmatch/
---
## ICMapCodeSpaceRange::HasPartialMatch method


Detects is the passed raw code represented in byte array form has a partial match with CMap's codespace ranges - partial match means that first element(s) in array is in range(s) but all the raw code bytes are not fully in any range.

```cpp
virtual bool Aspose::Pdf::Engine::CommonData::Text::CMaps::ICMapCodeSpaceRange::HasPartialMatch(System::ArrayPtr<uint8_t> values, int32_t size)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| values | System::ArrayPtr\<uint8_t\> | raw code in a byte array form |
| size | int32_t | count of bytes in byte array |

### ReturnValue

true/false
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>values</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>raw code in a byte array form</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>size</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>count of bytes in byte array</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ICMapCodeSpaceRange](../)
* Namespace [Aspose::Pdf::Engine::CommonData::Text::CMaps](../../)
* Library [Aspose.PDF for C++](../../../)
