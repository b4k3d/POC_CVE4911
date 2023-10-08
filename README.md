# PoC of CVE-2023-4911 "Looney Tunables"

This is a PoC of CVE-2023-4911 (a.k.a. "Looney Tunables") exploiting a bug in glibc dynamic loader's `GLIBC_TUNABLES` environment variable parsing function `parse_tunables()`.

Code has been tested on Ubuntu 22.04.3 with glibc version `2.35-0ubuntu3.3`. No attempts have been made to generalize the PoC (read: "Works On My Machine"), so your mileage may vary.

big kudos to [Qualys Threat Research Unit] 


-----

Written by [b4k3d](https://twitter.com/0xb4k3d)

  ___ _ _  _   _______  
 | _ ) | || |_|__ /   \ 
 | _ \_  _| / /|_ \ |) |
 |___/ |_||_\_\___/___/ 
                        