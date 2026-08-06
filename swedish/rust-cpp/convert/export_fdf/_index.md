---
title: "export_fdf"
second_title: "Aspose.PDF för Rust via C++"
description: "Exporterar från tidigare öppnat PDF-dokument med AcroForm till FDF-dokument med filnamn."
type: docs
url: /sv/rust-cpp/convert/export_fdf/
---

_Exporterar från tidigare öppnat PDF-dokument med AcroForm till FDF-dokument med filnamn._

```rust
pub fn export_fdf(&self, filename: &str) -> Result<(), PdfError>
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

    // Exportera från det tidigare öppnade PDF-dokumentet med AcroForm till FDF-dokument
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```