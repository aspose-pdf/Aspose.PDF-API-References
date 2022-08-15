---
title: RadioButtonField
second_title: Aspose.PDF for .NET API Reference
description: 
type: docs
weight: 3110
url: /net/aspose.pdf.forms/radiobuttonfield/
---
## RadioButtonField class

```csharp
public sealed class RadioButtonField : ChoiceField
```

## Constructors

| Name | Description |
| --- | --- |
| [RadioButtonField](radiobuttonfield#constructor)(Document) |  |
| [RadioButtonField](radiobuttonfield#constructor_1)(Page) |  |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } |  (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } |  |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } |  |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } |  |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } |  |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } |  |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } |  |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } |  |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } |  |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately) { get; set; } |  |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } |  |
| [Count](../../aspose.pdf.forms/field/count) { get; } |  |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } |  |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } |  |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } |  |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } |  |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } |  |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } |  |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } |  |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } |  |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } |  |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } |  |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } |  |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } |  |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } |  |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } |  |
| [Item](../../aspose.pdf.forms/field/item) { get; } |  (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } |  |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } |  |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } |  |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect) { get; set; } |  |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } |  |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } |  |
| override [Options](../../aspose.pdf.forms/radiobuttonfield/options) { get; } |  |
| override [PageIndex](../../aspose.pdf.forms/radiobuttonfield/pageindex) { get; } |  |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } |  |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } |  |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } |  |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } |  |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } |  |
| override [Selected](../../aspose.pdf.forms/radiobuttonfield/selected) { get; set; } |  |
| virtual [SelectedItems](../../aspose.pdf.forms/choicefield/selecteditems) { get; set; } |  |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } |  |
| [Style](../../aspose.pdf.forms/radiobuttonfield/style) { get; set; } |  |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } |  |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } |  |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } |  |
| override [Value](../../aspose.pdf.forms/radiobuttonfield/value) { get; set; } |  |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } |  |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } |  |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) |  |
| [Add](../../aspose.pdf.forms/radiobuttonfield/add)(RadioButtonOptionField) |  |
| override [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption#addoption)(string) |  |
| [AddOption](../../aspose.pdf.forms/radiobuttonfield/addoption#addoption_1)(string, Rectangle) |  |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string, string) |  |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) |  |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() |  |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) |  |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption)(string) |  |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() |  |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() |  |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) |  |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() |  |
| override [SetPosition](../../aspose.pdf.forms/radiobuttonfield/setposition)(Point) |  |

### See Also

* class [ChoiceField](../choicefield)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
