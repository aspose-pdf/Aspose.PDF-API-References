---
title: "SaveTiff"
second_title: "Aspose.PDF per Go via C++"
description: "Converti e salva il PDF-document precedentemente aperto come Tiff-document."
type: docs
url: /it/go-cpp/convert/savetiff/
---

_Converti e salva il PDF-document precedentemente aperto come Tiff-document._

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
        // Open(filename string) apre un PDF-document con filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() rilascia le risorse allocate per il PDF-document
        defer pdf.Close()
        // SaveTiff(filename string) salva il PDF-document precedentemente aperto come Tiff-document con nome file
        err = pdf.SaveTiff("sample.tiff")
        if err != nil {
                log.Fatal(err)
        }
}
```
