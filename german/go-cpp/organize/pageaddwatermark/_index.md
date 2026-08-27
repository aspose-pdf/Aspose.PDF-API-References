---
title: "PageAddWatermark"
second_title: "Aspose.PDF für Go über C++"
description: "Wasserzeichen auf der Seite hinzufügen."
type: docs
url: /de/go-cpp/organize/pageaddwatermark/
---

_Fügt ein Wasserzeichen auf der Seite hinzu._

```go
func (document *Document) PageAddWatermark(num int32, text string, fontName string, fontSize float64, foregroundColor string, xPosition int32, yPosition int32, rotation int32, isBackground bool, opacity float64) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **text** - watermark text
  * **fontName** - font name
  * **fontSize** - font size
  * **foregroundColor** - text color (hexadecimal format "#RRGGBB", where RR-red, GG-green and BB-blue hexadecimal integers)
  * **xPosition** - x watermark position
  * **yPosition** - y watermark position
  * **rotation** - watermark rotation (0-360)
  * **isBackground** - background
  * **opacity** - opacity (decimal)

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
        // Open(filename string) öffnet ein PDF-document mit Dateiname
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() gibt zugewiesene Ressourcen für PDF-document frei
        defer pdf.Close()
        // PageAddWatermark(num int32, text string, fontName string, fontSize float64, foregroundColor string, xPosition int32, yPosition int32, rotation int32, isBackground bool, opacity float64) fügt ein Wasserzeichen auf der Seite hinzu
        err = pdf.PageAddWatermark(1, "Watermark", "Arial", 16, "#010101", 100, 100, 45, true, 0.5)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
        err = pdf.SaveAs("sample_PageAddWatermark.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
