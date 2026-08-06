---
title: "set_license"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Lisansı dosya adıyla ayarlar."
type: docs
url: /tr/rust-cpp/core/set_license/
---

_Lisansı dosya adıyla ayarlar._

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
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Dosya adıyla lisansı ayarla
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Artık lisanslı PDF belgesiyle çalışabilirsiniz
    // ...

    Ok(())
}

```