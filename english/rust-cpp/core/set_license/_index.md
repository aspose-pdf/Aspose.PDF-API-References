---
title: "set_license"
second_title: Aspose.PDF for Rust via C++
description: "Sets license using filename."
type: docs
url: /rust-cpp/core/set_license/
---

_Sets license using filename._

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** – the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Set license with filename
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Now you can work with the licensed PDF document
    // ...

    Ok(())
}

```