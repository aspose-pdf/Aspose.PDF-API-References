---
title: "export_fdf"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengekspor dari dokumen PDF yang sebelumnya dibuka dengan AcroForm ke dokumen FDF dengan nama file."
type: docs
url: /id/rust-cpp/convert/export_fdf/
---

_Mengekspor dari dokumen PDF yang sebelumnya dibuka dengan AcroForm ke dokumen FDF dengan nama file._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Ekspor dari dokumen PDF yang sebelumnya dibuka dengan AcroForm ke dokumen FDF
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```