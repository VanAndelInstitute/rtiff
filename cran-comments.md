## Test environments
* ubuntu 18.04 R 3.5.3
* win-builder (devel and release)

## R CMD check results

0 errors ✔ | 1 warning ✖ | 0 notes ✔

  Compilation used the following non-portable flag(s):
    ‘-Wdate-time’ ‘-Werror=format-security’ ‘-Wformat’

It is my understanding that only related to how R was built on 
my machine and can be ignored.
    
* This is a bug fix to address build warnings related to not registering native routines
* Also changed configure.in to configure.ac
