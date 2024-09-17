---
title: Aspose::Pdf::Annotations::GoToAction::GoToAction constructor
linktitle: GoToAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::GoToAction::GoToAction constructor. Constructor for GoToAction class in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.annotations/gotoaction/gotoaction/
---
## GoToAction::GoToAction(int32_t) constructor


Constructor for [GoToAction](../) class.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::GoToAction::GoToAction(int32_t page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | int32_t | The destination page number to jump to. |
## Remarks


<xrefsect id="deprecated_1_deprecated000123">
  <xreftitle>Deprecated</xreftitle>
  <xrefdescription>
    <para>Use constructor with <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Aspose.Pdf.Page</ref> parameter instead of this one. Reason: if to use this constructor there is the problem with the document when to resave it in Adobe Acrobat. </para>
  </xrefdescription>
</xrefsect><parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The destination page number to jump to.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(System::SharedPtr\<Page\>) constructor


Constructor for [GoToAction](../) class.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::GoToAction::GoToAction(System::SharedPtr<Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | [Aspose.Pdf.Page](../../../aspose.pdf/page/) destination object to jump to. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Aspose.Pdf.Page</ref> destination object to jump to.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(System::SharedPtr\<Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) constructor


Constructor for [GoToAction](../) class.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::GoToAction::GoToAction(System::SharedPtr<Page> page, ExplicitDestinationType type, const System::ArrayPtr<double> &values)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | Destination page. |
| type | ExplicitDestinationType | Destination type. |
| values | const System::ArrayPtr\<double\>\& | Action parameters. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Destination page.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>type</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Destination type.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>values</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Action parameters.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Enum [ExplicitDestinationType](../../explicitdestinationtype/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(System::SharedPtr\<ExplicitDestination\>) constructor


Constructor.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::GoToAction::GoToAction(System::SharedPtr<ExplicitDestination> destination)
```


| Parameter | Type | Description |
| --- | --- | --- |
| destination | System::SharedPtr\<ExplicitDestination\> | Explicit destination. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>destination</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Explicit destination.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ExplicitDestination](../../explicitdestination/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction() constructor


Constructor.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::GoToAction::GoToAction()
```

## Remarks


<xrefsect id="deprecated_1_deprecated000124">
  <xreftitle>Deprecated</xreftitle>
  <xrefdescription>
    <para>Use constructors with parameters. </para>
  </xrefdescription>
</xrefsect>
## See Also

* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## GoToAction::GoToAction(System::SharedPtr\<Document\>, System::String) constructor


Action which linked with Named Destination.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Annotations::GoToAction::GoToAction(System::SharedPtr<Document> doc, System::String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| doc | System::SharedPtr\<Document\> | [Document](../../../aspose.pdf/document/) where action will be created. |
| name | System::String | Name of the destination. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>doc</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> where action will be created.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>name</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of the destination.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../../aspose.pdf/document/)
* Class [GoToAction](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
