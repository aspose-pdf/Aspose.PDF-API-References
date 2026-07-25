---
title: "RemoveTextHeaders"
second_title: "Aspose.PDF for Go via C++"
description: "PDF-document'tan metin başlıklarını kaldır."
type: docs
url: /tr/go-cpp/organize/removetextheaders/
---

_PDF belgesinden metin başlıklarını kaldır._

```go
func (document *Document) RemoveTextHeaders() error
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
        // Open(filename string) dosya adıyla bir PDF-belgesi açar
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
        defer pdf.Close()
        // RemoveTextHeaders() PDF belgesinden metin başlıklarını kaldırır
        err = pdf.RemoveTextHeaders()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
        err = pdf.SaveAs("sample_RemoveTextHeaders.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
