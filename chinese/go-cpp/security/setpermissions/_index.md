---
title: "SetPermissions"
second_title: "Aspose.PDF for Go via C++"
description: "设置 PDF-document 的权限。"
type: docs
url: /zh/go-cpp/security/setpermissions/
---

_设置 PDF-document 的权限._

```go
func (document *Document) SetPermissions(userPassword string, ownerPassword string, permissions Permissions) error
```

**Parameters**: 
  * **userPassword** - user password
  * **ownerPassword** - owner password
  * **permissions** - bitmask of allowed PDF permissions (combine flags using `|`):
```go
type Permissions int32
const (
    PrintDocument                  Permissions = 1 << 2  // 4
    ModifyContent                  Permissions = 1 << 3  // 8
    ExtractContent                 Permissions = 1 << 4  // 16
    ModifyTextAnnotations          Permissions = 1 << 5  // 32
    FillForm                       Permissions = 1 << 8  // 256
    ExtractContentWithDisabilities Permissions = 1 << 9  // 512
    AssembleDocument               Permissions = 1 << 10 // 1024
    PrintingQuality                Permissions = 1 << 11 // 2048
)
```

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New 创建一个新的 PDF-document
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() 释放为 PDF-document 分配的资源
	defer pdf.Close()

	// SetPermissions(userPassword, ownerPassword, permissions) 设置 PDF-document 的权限
	err = pdf.SetPermissions(
		"userpass",
		"ownerpass",
		asposepdf.PrintDocument|
			asposepdf.ModifyContent|
			asposepdf.FillForm,
	)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) 将先前打开的 PDF-document 保存为新文件名
	err = pdf.SaveAs("sample_with_permissions.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
