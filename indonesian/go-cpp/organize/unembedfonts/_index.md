---
title: "UnembedFonts"
second_title: "Aspose.PDF untuk Go via C++"
description: "Lepaskan font yang tersemat pada PDF-document."
type: docs
url: /id/go-cpp/organize/unembedfonts/
---

_Lepaskan embed font pada dokumen PDF._

```go
func (document *Document) UnembedFonts() error
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
        // UnembedFonts() melepaskan embed font pada dokumen PDF
        err = pdf.UnembedFonts()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
        err = pdf.SaveAs("sample_UnembedFonts.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
