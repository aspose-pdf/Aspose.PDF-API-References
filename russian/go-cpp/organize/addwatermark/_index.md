---
title: "AddWatermark"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить водяной знак в PDF-документ."
type: docs
url: /ru/go-cpp/organize/addwatermark/
---

_Добавить водяной знак к PDF-документу._

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
        // Open(filename string) открывает PDF-документ с именем файла
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() освобождает выделенные ресурсы для PDF-документа
        defer pdf.Close()
        // AddWatermark(text string, fontName string, fontSize float64, foregroundColor string, xPosition int32, yPosition int32, rotation int32, isBackground bool, opacity float64) добавляет водяной знак к PDF-документу
        err = pdf.AddWatermark("Watermark", "Arial", 16, "#010101", 100, 100, 45, true, 0.5)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
        err = pdf.SaveAs("sample_AddWatermark.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
