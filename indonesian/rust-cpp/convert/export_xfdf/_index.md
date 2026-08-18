---
title: "export_xfdf"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XFDF-document dengan nama file."
type: docs
url: /id/rust-cpp/convert/export_xfdf/
---

_Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XFDF-document dengan nama file._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Ekspor dari PDF-document yang sebelumnya dibuka dengan AcroForm ke XFDF-document
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```