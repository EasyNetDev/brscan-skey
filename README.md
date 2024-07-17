# brscan-skey
Brother Linux scanner S-KEY tool

This is original Brother Linux scanner S-KEY tool 3.2.0 repacket in 3 versions: `brscan-skey`, `brscan-skey-libsane1` and `brscan-skey-libsane1`. First is just a meta-package which depends on `brscan-skey-libsane1` or `brscan-skey-libsane1`.

Because Brother doesn't provide a new package, using the original package I have issues on Debian Trixie because the `libsane` was renamed to `libsane1` and the packet needs `libsane`.
So installing it will fail.
