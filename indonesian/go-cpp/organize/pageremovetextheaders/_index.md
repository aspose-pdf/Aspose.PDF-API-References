---
title: "PageRemoveTextHeaders"
second_title: "Aspose.PDF untuk Go via C++"
description: "Hapus header teks di halaman."
type: docs
url: /id/go-cpp/organize/pageremovetextheaders/
---

_Hapus header teks di halaman._

```go
func (document *Document) PageRemoveTextHeaders(num int32) error
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
        // PageRemoveTextHeaders(num int32) menghapus header teks di halaman
        err = pdf.PageRemoveTextHeaders(1)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
        err = pdf.SaveAs("sample_page1_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
