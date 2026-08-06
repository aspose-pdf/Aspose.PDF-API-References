---
title: "export_xfdf"
second_title: "Aspose.PDF für Rust über C++"
description: "Exportiert aus zuvor geöffnetem PDF-Dokument mit AcroForm zu XFDF-Dokument mit Dateiname."
type: docs
url: /de/rust-cpp/convert/export_xfdf/
---

_Exportiert aus zuvor geöffnetem PDF-Dokument mit AcroForm zu XFDF-Dokument mit Dateiname._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Export aus dem zuvor geöffneten PDF-Dokument mit AcroForm zu XFDF-Dokument
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```