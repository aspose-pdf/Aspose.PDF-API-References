---
title: "append"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menambahkan halaman dari PDF-document lain."
type: docs
url: /id/rust-cpp/core/append/
---

_Menambahkan halaman dari PDF-document lain._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka PDF-document utama
    let pdf = Document::open("sample.pdf")?;

    // Buka dokumen PDF lain untuk ditambahkan
    let another_pdf = Document::open("sample1page.pdf")?;

    // Tambahkan halaman dari dokumen PDF lain
    pdf.append(&another_pdf)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```