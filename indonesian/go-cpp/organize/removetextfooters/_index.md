---
title: "RemoveTextFooters"
second_title: "Aspose.PDF untuk Go via C++"
description: "Hapus footer teks dari PDF-document."
type: docs
url: /id/go-cpp/organize/removetextfooters/
---

_Hapus footer teks dari PDF-document._

```go
func (document *Document) RemoveTextFooters() error
```

**Parameters**: 

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
        // RemoveTextFooters() menghapus footer teks dari PDF-document
        err = pdf.RemoveTextFooters()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
        err = pdf.SaveAs("sample_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
