# C Standards: Part of the CEPHYR-cc Compiler

CEPHYR-cc is this small compiler I am authoring for the ISO/ANSI C language. This repository contains all the ISO C standards so it can be added to the main repository of CEPHYR-cc (linked [here](https://github.com/Chubek/cephyr-cc)) as a submodule. I plan on formally verifying CEPHYR-cc, borrowing from CompCert (ironically one of the authors of CompCert is Xavier LeRoy, author of OCaml, which I *might* write CEPHYR-cc in. I still have not decided, I am planning things. I may write it in Haskell! That's why the link to repository does not work yet).

The standard PDF files for C99 and C11 are the official ones by ISO/IEC, not the slop fed to the masses by open-std.org! So keep that in mind going forward. C17 is something inbetween the open-std slop and final version. C23 is still being drafted so it's not final.

The following table is derived from 'Modern C Programming', a recent book by Orhan Gazi. If you are writing a C compiler, it's the book for you because it's not a nasty cashgrab like "Understanding and Using C Pointers" (don't buy this book, just don't. C pointers are easy. Self-taught programmers make a big deal of pointers for some reason, and it is understandable --- however, in reality, that's because self-taught programmers often think in terms of safe languages like Python, I recommend reading these standards instead of that garbage book if you are a beginner and have problem grokking pointers!) and it's more of a "C Canon" book. I highly recommend it. It's a catalogue of C. And for the love of God, K&R book is a collectible item, not an educational book! Also, I am __technically__ a self-taught programmer myself (I dropped out of Scientific-Vocational college after just 3 semesters, one semester short of getting my Associate's) so don't take my remark about self-taught programmers not understanding pointers and making a big deal about it out of context. I myself "learned" C when I was 17, and I had a lot of issues with pointers. I still do! CEPHYR-cc is an educational project.


So enough yapping, here's the table:

|Informal name|Introduction year|Forman name|File name|
|-------------|-----------------|-----------|---------|
|C99	      | 1999            | ISO/IEC 9899:1999|N1256.pdf|
|C11          | 2011            | ISO/IEC 9899:2011|N1570.pdf|
|C17          | 2018            | ISO/IEC 9899:2018|N2310.pdf|
|C23          | 2023            | ISO/IEC 9899:2023|N3096.pdf|


The file names should direct you to the open-std.org versions of the standards of Captain Hook stuff does not fly with you!


\- Chubak


