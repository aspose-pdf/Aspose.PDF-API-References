---
title: "حول"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يعيد معلومات البيانات الوصفية حول Aspose.PDF للـ Rust عبر C++."
type: docs
url: /ar/rust-cpp/miscellaneous/about/
---

_يعيد معلومات البيانات الوصفية حول Aspose.PDF للـ Rust عبر C++._

```rust
pub fn about(&self) -> Result<ProductInfo, PdfError>
```

**Arguments**


**Returns**
  * **Ok(ProductInfo)** - if the operation succeeds
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // إنشاء مستند PDF-document جديد
    let pdf = Document::new()?;

    // يعيد معلومات البيانات الوصفية حول Aspose.PDF للـ Go عبر C++.
    let info = pdf.about()?;

    // طباعة حقول البيانات الوصفية
    println!("Product Info:");
    println!("  Product:      {}", info.product);
    println!("  Family:       {}", info.family);
    println!("  Version:      {}", info.version);
    println!("  ReleaseDate:  {}", info.release_date);
    println!("  Producer:     {}", info.producer);
    println!("  IsLicensed:   {}", info.is_licensed);

    Ok(())
}

```