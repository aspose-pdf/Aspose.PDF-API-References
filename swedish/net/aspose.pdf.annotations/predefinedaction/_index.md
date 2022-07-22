---
title: PredefinedAction
second_title: Aspose.PDF för .NET API Referens
description: Definierar olika åtgärder som kan utlösas från en PDF-fil.
type: docs
weight: 950
url: /sv/net/aspose.pdf.annotations/predefinedaction/
---
## PredefinedAction enumeration

Definierar olika åtgärder som kan utlösas från en PDF-fil.

```csharp
public enum PredefinedAction
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| FirstPage | `0` | En namngiven åtgärd för att gå till första sidan. |
| LastPage | `1` | En namngiven åtgärd för att gå till sista sidan. |
| NextPage | `2` | En namngiven åtgärd för att gå till nästa sida. |
| PrevPage | `3` | En namngiven åtgärd för att gå till föregående sida. |
| PrintDialog | `4` | En namngiven åtgärd för att öppna en utskriftsdialogruta (JavaScript). |
| Print | `5` | En namngiven åtgärd för att öppna en utskriftsdialogruta. |
| Bookmarks_ExpanCurrentBookmark | `6` | En namngiven åtgärd för att hitta aktuellt bokmärke. |
| Bookmarks_HightlightCurrentBookmark | `7` | En namngiven åtgärd för att markera aktuellt bokmärke. |
| Document_AttachFile | `8` | En namngiven åtgärd för att lägga till filbilaga. |
| Document_CropPages | `9` | En namngiven åtgärd för att beskära dokumentsidor. |
| Document_DeletePages | `10` | En namngiven åtgärd för att radera dokumentsidor. |
| Document_ExtractPages | `11` | En namngiven åtgärd för att extrahera dokumentsidor. |
| Document_InsertPages | `12` | En namngiven åtgärd för att infoga sidor från ett dokument. |
| Document_ReplacePages | `13` | En namngiven åtgärd för att ersätta dokumentsidor. |
| Document_RotatePages | `14` | En namngiven åtgärd för att rotera dokumentsidor. |
| Edit_CheckSpelling_InComFieldEdit | `15` | En namngiven åtgärd för att kontrollera stavning i kommentarer. |
| Edit_Find | `16` | En namngiven åtgärd att hitta. |
| Edit_Preferences | `17` | En namngiven åtgärd för att redigera inställningar. |
| Edit_Search | `18` | En namngiven åtgärd för sökning. |
| File_AttachToEmail | `19` | En namngiven åtgärd för att bifoga aktuellt pdf-dokument till e-postmeddelande. |
| File_Close | `20` | En namngiven åtgärd för att stänga dokumentet. |
| File_CreatePDF_FromScanner | `21` | En namngiven åtgärd för att skapa pdf-dokument från scanner. |
| File_CreatePDF_FromWebPage | `22` | En namngiven åtgärd för att skapa pdf-dokument från webbsidan. |
| File_Exit | `23` | En namngiven åtgärd för att avsluta pdf-läsaren. |
| File_Organizer_OpenOrganizer | `24` | En namngiven åtgärd för att öppna organisatören. |
| File_Print | `25` | En namngiven åtgärd för att skriva ut dokumentet. |
| File_Properties | `26` | En namngiven åtgärd för att öppna dokumentegenskaperna. |
| File_SaveAs | `27` | En namngiven åtgärd för att spara dokumentet med ett annat namn. |
| Miscellaneous_ZoomIn | `28` | En namngiven åtgärd för att zooma in dokumentet. |
| Miscellaneous_ZoomOut | `29` | En namngiven åtgärd för att zooma ut dokumentet. |
| PageImages_PrintPages | `30` | En namngiven åtgärd för att skriva ut dokumentsidorna. |
| View_GoTo_NextView | `31` | En namngiven åtgärd för att gå till nästa vy. |
| View_GoTo_Page | `32` | En namngiven åtgärd för att gå till en viss sida. |
| View_GoTo_PreDocument | `33` | En namngiven åtgärd för att gå till föregående dokument. |
| View_GoTo_PreView | `34` | En namngiven åtgärd för att gå till föregående vy. |
| View_NavigationPanels_Articles | `35` | En namngiven åtgärd för att visa/dölja artikelpanelen. |
| View_NavigationPanels_Attachments | `36` | En namngiven åtgärd för att visa/dölja bilagapanel. |
| View_NavigationPanels_Boomarks | `37` | En namngiven åtgärd för att visa/dölja bokmärkespanelen. |
| View_NavigationPanels_Comments | `38` | En namngiven åtgärd för att visa/dölja kommentarspanelen. |
| View_NavigationPanels_Fields | `39` | En namngiven åtgärd för att visa/dölja fältpanelen. |
| View_NavigationPanels_Layers | `40` | En namngiven åtgärd för att visa/dölja lagerpanelen. |
| View_NavigationPanels_ModelTree | `41` | En namngiven åtgärd för att visa/dölja modellträdpanelen. |
| View_NavigationPanels_Pages | `42` | En namngiven åtgärd för att visa/dölja sidpanelen. |
| View_NavigationPanels_Signatures | `43` | En namngiven åtgärd för att visa/dölja signaturpanelen. |
| View_PageDisplay_SinglePage | `44` | En namngiven åtgärd för att visa en sida. |
| View_PageDisplay_SinglePageContinuous | `45` | En namngiven åtgärd för att visa en kontinuerlig sida. |
| View_PageDisplay_TwoUp | `46` | En namngiven åtgärd för att visa sidor som Two-Up. |
| View_PageDisplay_TwoUpContinuous | `47` | En namngiven åtgärd för att visa sidor som kontinuerliga sidor. |
| View_Toolbars_AdvanceEditing | `48` | En namngiven åtgärd för att visa/dölja verktygsfältet för avancerad redigering. |
| View_Toolbars_CommentMarkup | `49` | En namngiven åtgärd för att visa/dölja kommentarverktygsfältet. |
| View_Toolbars_Edit | `50` | En namngiven åtgärd för att visa/dölja redigeringsverktygsfältet. |
| View_Toolbars_File | `51` | En namngiven åtgärd för att visa/dölja filverktygsfältet. |
| View_Toolbars_Find | `52` | En namngiven åtgärd för att visa/dölja sökverktygsfältet. |
| View_Toolbars_Forms | `53` | En namngiven åtgärd för att visa/dölja formulärverktygsfält. |
| View_Toolbars_Measuring | `54` | En namngiven åtgärd för att visa/dölja mätverktygsfältet. |
| View_Toolbars_ObjectData | `55` | En namngiven åtgärd för att visa/dölja objektdataverktygsfältet. |
| View_Toolbars_PageDisplay | `56` | En namngiven åtgärd för att visa/dölja sidvisningsverktygsfältet. |
| View_Toolbars_PageNavigation | `57` | En namngiven åtgärd för att visa/dölja navigeringsverktygsfältet. |
| View_Toolbars_PrintProduction | `58` | En namngiven åtgärd för att visa/dölja verktygsfältet för utskriftsproduktion. |
| View_Toolbars_PropertiesBar | `59` | En namngiven åtgärd för att visa/dölja egenskapsverktygsfältet. |
| View_Toolbars_Redaction | `60` | En namngiven åtgärd för att visa/dölja redigeringsverktygsfältet. |
| View_Toolbars_SelectZoom | `61` | En namngiven åtgärd för att visa/dölja verktygsfältet Välj och zooma. |
| View_Toolbars_Tasks | `62` | En namngiven åtgärd för att visa/dölja uppgiftsverktygsfältet. |
| View_Toolbars_Typewriter | `63` | En namngiven åtgärd för att visa/dölja skrivmaskinens verktygsfält. |
| View_Zoom_ActualSize | `64` | En namngiven åtgärd för att visa sidor i verklig storlek. |
| View_Zoom_FitHeight | `65` | En namngiven åtgärd för att passa sidan på höjden. |
| View_Zoom_FitPage | `66` | En namngiven åtgärd för att passa sidan. |
| View_Zoom_FitVisible | `67` | En namngiven åtgärd för att passa sidans synlighet. |
| View_Zoom_FitWidth | `68` | En namngiven åtgärd för att passa sidan på bredd. |
| View_Zoom_ZoomTo | `69` | En namngiven åtgärd för att göra zoom. |
| Window_FullScreenMode | `70` | En namngiven åtgärd för att visa dokumentet i helskärmsläge. |

### Se även

* namnutrymme [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
