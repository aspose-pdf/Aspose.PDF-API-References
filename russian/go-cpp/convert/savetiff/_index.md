---
title: "SaveTiff"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить ранее открытый PDF-документ как Tiff-документ."
type: docs
url: /ru/go-cpp/convert/savetiff/
---

_Преобразовать и сохранить ранее открытый PDF-документ как Tiff-документ._

```go
func (document *Document) SaveTiff(filename string, resolution_dpi ...int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **resolution_dpi (optional)** - resolution in DPI of the resulting file, defaults to 100 DPI

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
        // SaveTiff(filename string) сохраняет ранее открытый PDF-документ как Tiff-документ с именем файла
        err = pdf.SaveTiff("sample.tiff")
        if err != nil {
                log.Fatal(err)
        }
}
```
