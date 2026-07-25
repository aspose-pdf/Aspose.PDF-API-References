---
title: "SaveTiff"
second_title: "Aspose.PDF untuk Go via C++"
description: "Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Tiff-document."
type: docs
url: /id/go-cpp/convert/savetiff/
---

_Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai Tiff-document._

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
        // Open(filename string) membuka PDF-dokumen dengan nama file
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
        defer pdf.Close()
        // SaveTiff(filename string) menyimpan PDF-document yang sebelumnya dibuka sebagai Tiff-document dengan nama file
        err = pdf.SaveTiff("sample.tiff")
        if err != nil {
                log.Fatal(err)
        }
}
```
