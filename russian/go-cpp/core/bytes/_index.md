---
title: "Bytes"
second_title: "Aspose.PDF для Go через C++"
description: "Вернуть содержимое PDF-document в виде среза байтов."
type: docs
url: /ru/go-cpp/core/bytes/
---

_Вернуть содержимое PDF-документа в виде байтового среза._

```go
func (document *Document) Bytes() ([]byte, error)
```

**Parameters**: 

**Return**:
  * **\[\]byte** - raw bytes of the PDF-document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
        "github.com/aspose-pdf/aspose-pdf-go-cpp"
        "log"
        "os"
)

func main() {
        // New создает новый PDF-документ
        pdf, err := asposepdf.New()
        if err != nil {
                log.Fatal(err)
        }
        defer pdf.Close()

        // Bytes возвращает содержимое PDF-документа в виде байтового среза
        bytes, err := pdf.Bytes()
        if err != nil {
                log.Fatal(err)
        }

        // Сохранить байтовый срез в файл.
        err = os.WriteFile("sample_Bytes.pdf", bytes, 0644)
        if err != nil {
                log.Fatal(err)
        }
}
```
