---
title: "export_fdf"
second_title: "Aspose.PDF für Rust über C++"
description: "Exportiert das zuvor geöffnete PDF-Dokument mit AcroForm zu einem FDF-Dokument mit Dateiname."
type: docs
url: /de/rust-cpp/convert/export_fdf/
---

_Exportiert das zuvor geöffnete PDF-Dokument mit AcroForm zu einem FDF-Dokument mit Dateiname._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Exportiere das zuvor geöffnete PDF-Dokument mit AcroForm zu einem FDF-Dokument
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```