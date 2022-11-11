# Best compiled languages
A very biased list of compiled programming languages that I consider to be the best.
There are some question marks because I'm not sure about that criteria for that particular language. I haven't tried Odin or DLang yet.
Here is a very biased comparison table:

|Criteria|C|C++|Golang|Rust|Zig|Odin|Nim|Crystal|Vlang|Dlang
|:-|:-|:-|:-|:-|:-|:-|:-|:-|:-|:-|
|Compiled|✅|✅|✅|✅|✅|✅|✅|✅|✅|✅|
|Multiplatform|✅|✅|✅|✅|✅|✅|✅|✅|✅|✅|
|Small compiler|infinite compilers. tcc is really tiny 620KB|around 200MB I'm guessing for g++|142MB|414.1 MB|42.3MB tar.xz|44 MB zip|11.4MB tar.xz|\~40MB tar.gz|6.6MB zip (uses tcc, so a bit of cheating)|Around 100MB I think, once installed. Probably around 50MB compressed|
|Compiler speed|Fast|Slow|Fast|Slow|Medium|???|Medium|???|Fast (uses tcc)|???|
|Maturity|High|High|High|High|Medium|???|High?|High?|Low? Lots of leaks|Medium/High?|
|Binary size|Small|Small|Medium|Small|Small|???|Medium/Low?|Medium|Medium?|Small/Medium?|
|Tighly coupled dependencies of binaries|Low|Low|Low|Low|Low but std lib is not so extensive|???|OpenSSL|OpenSSL|Used to be OpenSSL but that was changed recently.|Libcurl for web requests|
|Memory management possible|Yes|Yes|Yes, although the GC is quite good|Yes|Yes|Yes|In theory yes, but all the std lib depends on GC being available?|???|??? Suposedly yes, but when I tried to manually manage the memory it was buggy|Yes, but most of the std lib is made to be worked with GC?|
|Syntax Modernity|Low|Medium|Medium|Medium|Medium|High|High|High|Medium|Medium?|
