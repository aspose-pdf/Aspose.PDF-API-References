---
title: "save_epub"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai EPUB-document."
type: docs
url: /id/rust-cpp/convert/save_epub/
---

_Mengonversi dan menyimpan PDF-document yang sebelumnya dibuka sebagai dokumen EPUB-document._

```rust
pub fn save_epub(&self, filename: &str) -> Result<(), PdfError>
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

    // Konversi dan simpan PDF-document yang sebelumnya dibuka sebagai dokumen Epub-document
    pdf.save_epub("sample.epub")?;

    Ok(())
}

```