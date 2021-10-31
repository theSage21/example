Trying to run example from [actix-web-static-files](https://github.com/kilork/actix-web-static-files#use-case-1-static-resources-folder)

## Error traceback

```
   Compiling xmpl v0.1.0 (/home/arjoonn/temp/xmpl)
error[E0308]: mismatched types
  --> src/main.rs:11:52
   |
11 |         App::new().service(ResourceFiles::new("/", generated))
   |                                                    ^^^^^^^^^ expected struct `actix_web_static_files::Resource`, found struct `static_files::Resource`
   |
   = note: expected struct `std::collections::HashMap<&'static str, actix_web_static_files::Resource>`
              found struct `std::collections::HashMap<&str, static_files::Resource>`

For more information about this error, try `rustc --explain E0308`.
error: could not compile `xmpl` due to previous error
```
