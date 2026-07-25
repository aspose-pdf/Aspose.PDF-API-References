---
title: "PageRemoveWatermarks"
second_title: "Aspose.PDF untuk Go via C++"
description: "Hapus watermark di halaman."
type: docs
url: /id/go-cpp/organize/pageremovewatermarks/
---

_Hapus watermark pada halaman._

```go
func (document *Document) PageRemoveWatermarks(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
        // PageRemoveWatermarks(num int32) menghapus watermark pada halaman
        err = pdf.PageRemoveWatermarks(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
        err = pdf.SaveAs("sample_page1_RemoveWatermarks.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
