# Best compiled languages
A very biased list of compiled programming languages that I consider to be the best.

There are some question marks because I'm not sure about that criteria for that particular language. I haven't tried Odin or DLang yet.
Here is a very biased comparison table:

|Criteria|C|C++|Golang|Rust|Zig|Odin|Nim|Crystal|Vlang|Dlang
|:-|:-|:-|:-|:-|:-|:-|:-|:-|:-|:-|
|Compiled|✅|✅|✅|✅|✅|✅|✅|✅|✅|✅|
|Multiplatform|✅|✅|✅|✅|✅|✅|✅|✅|✅|✅|
|Small compiler|tcc \~620KB|\~200MB g++|142MB|414.1 MB|42.3MB tar.xz|44 MB zip|11.4MB tar.xz|\~40MB tar.gz|6.6MB zip (uses tcc)|\~50MB tar.xz|
|Compiler speed|Fast|Slow|Fast|Slow|Medium|???|Medium|???|Fast (uses tcc)|???|
|Maturity|High|High|High|High|Medium|???|High?|High?|Low? Lots of leaks|High?|
|Binary size|Small|Small|Medium|Small|Small|???|Medium/Low?|Medium|Medium?|Small?|
|System libraries dependencies|Low|Low|Low|Low|Low, small std lib|???|OpenSSL|OpenSSL|OpenSSL or MbedTLS|Libcurl|
|Manual Memory management|Yes|Yes|Yes, but good GC|Yes|Yes|Yes|Yes, stdlib needs GC|???|Buggy|Yes, stdlib needs GC|
|Syntax Modernity|Low|Medium|Medium|Medium|Medium|High|High|High|Medium|Medium?|
|Syntax Familiarity|C (easy, macros make it hard)|C-like (medium?, templates can be hard)|C-like (easy)|C-like (steep learning curve)|C-like (medium learning curve)|C-like (easy?)|Python-Pascal-like? (easy?)|Ruby-like (medium?)|Go-like (easy)|C-like (easy?)|
