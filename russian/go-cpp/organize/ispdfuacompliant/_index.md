---
title: "IsPdfUaCompliant"
second_title: "Aspose.PDF для Go через C++"
description: "Определить, соответствует ли PDF-документ PDF/UA."
type: docs
url: /ru/go-cpp/organize/ispdfuacompliant/
---

_Получить, является ли PDF-документ совместимым с PDF/UA._

```go
func (document *Document) IsPdfUaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/UA compliant
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// IsPdfUaCompliant() получает статус совместимости PDF/UA PDF-документа
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
