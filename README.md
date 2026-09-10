# yarngo studio — runtime repository

The signed repository installed copies of [yarngo studio](https://github.com/getlatentic/yarngo-studio) fetch speech runtimes from, served at
<https://getlatentic.github.io/yarngo-studio-artifacts/tuf/>.

Written by `scripts/tuf-repo.sh` in the application repository. Every file here
is public by design and verified by the client against a trust anchor compiled
into the application, so serving it from anywhere else changes nothing about
what it will accept.

This is not the source. The application lives at
<https://github.com/getlatentic/yarngo-studio>.
