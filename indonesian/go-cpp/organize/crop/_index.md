---
title: "Crop"
second_title: "Aspose.PDF untuk Go via C++"
description: "Pangkas halaman PDF-document."
type: docs
url: /id/go-cpp/organize/crop/
---

_Potong halaman dari dokumen PDF._

```go
func (document *Document) Crop(margin float64) error
```

**Parameters**: 
  * **margin** - page margin

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
        // Crop(margin float64) memotong halaman dari dokumen PDF
        err = pdf.Crop(0)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
        err = pdf.SaveAs("sample_Crop.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
