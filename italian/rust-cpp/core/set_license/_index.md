---
title: "set_license"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Imposta la licenza usando il nome file."
type: docs
url: /it/rust-cpp/core/set_license/
---

_Imposta la licenza usando il nome file._

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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Imposta la licenza con il nome file
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Ora puoi lavorare con il documento PDF con licenza
    // ...

    Ok(())
}

```