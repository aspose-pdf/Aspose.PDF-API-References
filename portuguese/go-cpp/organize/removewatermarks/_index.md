---
title: "RemoveWatermarks"
second_title: "Aspose.PDF para Go via C++"
description: "Remover marcas d'água do documento PDF."
type: docs
url: /pt/go-cpp/organize/removewatermarks/
---

_Remova marcas d'água do documento PDF._

```go
func (document *Document) RemoveWatermarks() error
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
        // RemoveWatermarks() remove marcas d'água do documento PDF
        err = pdf.RemoveWatermarks()
        if err != nil {
                log.Fatal(err)
        }
        // SaveAs(filename string) salva o PDF-document aberto anteriormente com um novo nome de arquivo
        err = pdf.SaveAs("sample_RemoveWatermarks.pdf")
        if err != nil {
                log.Fatal(err)
        }
}
```
