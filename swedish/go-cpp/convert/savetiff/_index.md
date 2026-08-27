---
title: "SaveTiff"
second_title: "Aspose.PDF för Go via C++"
description: "Konvertera och spara det tidigare öppnade PDF-dokumentet som Tiff-dokument."
type: docs
url: /sv/go-cpp/convert/savetiff/
---

_Konvertera och spara det tidigare öppnade PDF-dokumentet som Tiff-dokument._

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
        // Open(filename string) öppnar ett PDF-dokument med filnamn
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() frigör allokerade resurser för PDF-dokument
        defer pdf.Close()
        // SaveTiff(filename string) sparar tidigare öppnat PDF-dokument som Tiff-dokument med filnamn
        err = pdf.SaveTiff("sample.tiff")
        if err != nil {
                log.Fatal(err)
        }
}
```
