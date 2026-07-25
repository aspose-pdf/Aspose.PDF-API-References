---
title: "RemoveTextFooters"
second_title: "Aspose.PDF para Go via C++"
description: "Remover rodapés de texto de PDF-documento."
type: docs
url: /pt/go-cpp/organize/removetextfooters/
---

_Remover rodapés de texto de PDF-document._

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
        // Open(filename string) abre um documento PDF com o nome de arquivo
        pdf, err := asposepdf.Open("sample.pdf")
        if err != nil {
                log.Fatal(err)
        }
        // Close() libera os recursos alocados para o documento PDF
        defer pdf.Close()
        // RemoveTextFooters() remove rodapés de texto de PDF-document
        err = pdf.RemoveTextFooters()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
        err = pdf.SaveAs("sample_RemoveTextFooters.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
