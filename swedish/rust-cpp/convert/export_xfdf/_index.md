---
title: "export_xfdf"
second_title: "Aspose.PDF för Rust via C++"
description: "Exporterar från tidigare öppnad PDF-dokument med AcroForm till XFDF-dokument med filnamn."
type: docs
url: /sv/rust-cpp/convert/export_xfdf/
---

_Exporterar från tidigare öppnad PDF-dokument med AcroForm till XFDF-dokument med filnamn._

```rust
pub fn export_xfdf(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till XFDF-dokument
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```