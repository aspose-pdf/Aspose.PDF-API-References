---
title: Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation constructor
linktitle: SoundAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation constructor. Creates new Sound annotation on the specified page in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.annotations/soundannotation/soundannotation/
---
## SoundAnnotation::SoundAnnotation(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::String) constructor


Creates new Sound annotation on the specified page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation(System::SharedPtr<Aspose::Pdf::Page> page, System::SharedPtr<Rectangle> rect, System::String soundFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | The document's page where annotation should be created. |
| rect | System::SharedPtr\<Rectangle\> | The annotation rectangle, defining the location of the annotation on the page. |
| soundFile | System::String | A sound file defining the sound to be played when the annotation is activated. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document's page where annotation should be created.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The annotation rectangle, defining the location of the annotation on the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>soundFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A sound file defining the sound to be played when the annotation is activated.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [SoundAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## SoundAnnotation::SoundAnnotation(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::String, System::SharedPtr\<SoundSampleData\>) constructor


Creates new Sound annotation on the specified page.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::SoundAnnotation::SoundAnnotation(System::SharedPtr<Aspose::Pdf::Page> page, System::SharedPtr<Rectangle> rect, System::String soundFile, System::SharedPtr<SoundSampleData> soundSampleData)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Aspose::Pdf::Page\> | The document's page where annotation should be created. |
| rect | System::SharedPtr\<Rectangle\> | The annotation rectangle, defining the location of the annotation on the page. |
| soundFile | System::String | A sound file defining the sound to be played when the annotation is activated. |
| soundSampleData | System::SharedPtr\<SoundSampleData\> | A sound sample data contains extra of sound parameters such as sampling rate, bits per sample and so on. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document's page where annotation should be created.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The annotation rectangle, defining the location of the annotation on the page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>soundFile</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A sound file defining the sound to be played when the annotation is activated.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>soundSampleData</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A sound sample data contains extra of sound parameters such as sampling rate, bits per sample and so on.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [SoundSampleData](../../soundsampledata/)
* Class [SoundAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
