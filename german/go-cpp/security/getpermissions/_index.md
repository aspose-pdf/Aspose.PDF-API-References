---
title: "GetPermissions"
second_title: "Aspose.PDF für Go über C++"
description: "Berechtigungen für PDF-Dokument abrufen."
type: docs
url: /de/go-cpp/security/getpermissions/
---

_Berechtigungen für PDF-Dokument abrufen._

```go
func (document *Document) GetPermissions() (Permissions, error)
```

**Parameters**: 

**Return**: 
  * **Permissions** - bitmask of PDF permission flags:
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
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import (
	"fmt"
	"log"
	"strings"
)

var permissionNames = map[asposepdf.Permissions]string{
	asposepdf.PrintDocument:                  "Allow printing",
	asposepdf.ModifyContent:                  "Allow modifying content (except forms/annotations)",
	asposepdf.ExtractContent:                 "Allow copying/extracting text and graphics",
	asposepdf.ModifyTextAnnotations:          "Allow adding/modifying text annotations",
	asposepdf.FillForm:                       "Allow filling interactive forms",
	asposepdf.ExtractContentWithDisabilities: "Allow content extraction for accessibility",
	asposepdf.AssembleDocument:               "Allow inserting/rotating/deleting pages or changing structure",
	asposepdf.PrintingQuality:                "Allow high-quality / faithful printing",
}

func PermissionsToString(p asposepdf.Permissions) string {
	var result []string
	for flag, name := range permissionNames {
		if p&flag != 0 {
			result = append(result, name)
		}
	}
	if len(result) == 0 {
		return "None"
	}
	return strings.Join(result, ", ")
}

func main() {
	// OpenWithPassword(filename string, password string) öffnet ein passwortgeschütztes PDF-Dokument
	pdf, err := asposepdf.OpenWithPassword("sample_with_permissions.pdf", "ownerpass")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// GetPermissions() ruft die aktuellen Berechtigungen des PDF-Dokuments ab
	permissions, err := pdf.GetPermissions()
	if err != nil {
		log.Fatal(err)
	}
	// Berechtigungen drucken
	fmt.Println("Permissions:", PermissionsToString(permissions))
}
```
