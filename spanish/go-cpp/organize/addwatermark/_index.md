---
title: "AddWatermark"
second_title: "Aspose.PDF para Go vía C++"
description: "Agregar marca de agua a PDF-document."
type: docs
url: /es/go-cpp/organize/addwatermark/
---

_Agregar marca de agua a PDF-document._

```go
func (document *Document) AddWatermark(text string, fontName string, fontSize float64, foregroundColor string, xPosition int32, yPosition int32, rotation int32, isBackground bool, opacity float64) error
```

**Parameters**: 
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
        // Open(filename string) abre un PDF-documento con el nombre de archivo
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libera los recursos asignados para el PDF-documento
        defer pdf.Close()
        // AddWatermark(text string, fontName string, fontSize float64, foregroundColor string, xPosition int32, yPosition int32, rotation int32, isBackground bool, opacity float64) agrega marca de agua a PDF-document
        err = pdf.AddWatermark("Watermark", "Arial", 16, "#010101", 100, 100, 45, true, 0.5)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) guarda el PDF-documento previamente abierto con un nuevo nombre de archivo
        err = pdf.SaveAs("sample_AddWatermark.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
