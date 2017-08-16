Test repository to check Git's vulnerability [CVE-2017-1000117](https://access.redhat.com/security/cve/cve-2017-1000117)

## How it works?

Clone this repository recursively.
The sentence 「うんこもりもり」(which means like "Lots of shit.") will be shown on your terminal.

```
$ git clone --recursive https://github.com/greymd/CVE-2017-1000117.git
Cloning into 'CVE-2017-1000117'...
remote: Counting objects: 5, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 5 (delta 0), pack-reused 0

...

    "mm
    mmmm          "m           "mmmmm
  ""    #         m"               "
        #        m#m          m
       #        m"  #   m     "m     m
     m"        m"   "mm"        """""
   m            m   m          m            m   m
  mm#            # # "m       mm#            # # "m
   m"#"          ##   #        m"#"          ##   #
 ""#mm "m        #    #      ""#mm "m        #    #
   #    #            #         #    #            #
    "mm"           m"           "mm"           m"

...

```

## Tested on:

* Linux (Ubuntu 16.04)
* macOS Sierra
* Windows 64bit -- Cygwin
* Windows 64bit -- Git Bash (MinGW-w64)
