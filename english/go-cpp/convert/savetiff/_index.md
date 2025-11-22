---
title: "SaveTiff"
second_title: Aspose.PDF for Go via C++
description: "Convert and save the previously opened PDF-document as Tiff-document."
type: docs
url: /go-cpp/convert/savetiff/
---

_Convert and save the previously opened PDF-document as Tiff-document._

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
        // Open(filename string) opens a PDF-document with filename
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() releases allocated resources for PDF-document
        defer pdf.Close()
        // SaveTiff(filename string) saves previously opened PDF-document as Tiff-document with filename
        err = pdf.SaveTiff("sample.tiff")
        if err != nil {
                log.Fatal(err)
        }
}
```
