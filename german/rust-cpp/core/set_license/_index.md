---
title: "set_license"
second_title: "Aspose.PDF für Rust über C++"
description: "Setzt die Lizenz mit Dateinamen."
type: docs
url: /de/rust-cpp/core/set_license/
---

_Setzt die Lizenz mit Dateinamen._

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Lizenz mit Dateinamen setzen
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Jetzt können Sie mit dem lizenzierten PDF-Dokument arbeiten
    // ...

    Ok(())
}

```