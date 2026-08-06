---
title: "set_license"
second_title: "Aspose.PDF para Rust vía C++"
description: "Establece la licencia usando el nombre de archivo."
type: docs
url: /es/rust-cpp/core/set_license/
---

_Establece la licencia usando el nombre de archivo._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Establecer licencia con nombre de archivo
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Ahora puedes trabajar con el documento PDF con licencia
    // ...

    Ok(())
}

```