---
title: "OptimizeFileSize"
second_title: "Aspose.PDF untuk Go via C++"
description: "Optimalkan ukuran PDF-document dengan kualitas kompresi gambar."
type: docs
url: /id/go-cpp/organize/optimizefilesize/
---

_Optimalkan ukuran PDF-document dengan kualitas kompresi gambar._

```go
func (document *Document) OptimizeFileSize(imageQuality int32) error
```

**Parameters**: 
  * **imageQuality** - image compression quality 

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
        // OptimizeFileSize(imageQuality int32) mengoptimalkan ukuran PDF-document dengan kualitas kompresi gambar
        err = pdf.OptimizeFileSize(20)
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) menyimpan PDF-document yang sebelumnya dibuka dengan nama file baru
        err = pdf.SaveAs("sample_OptimizeFileSize.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
