# Verifying ISO Files

ISO files for ***Umix*** are provided along with MD5 and SHA2-512 hashes. You can use the hashes to verify if the ISO files are intact or corrupted.

## Mini ISO

Open a command window and type:

```bash
sha256sum umix-bionic-mini-2018.11-desktop-amd64.iso
```

Compare the displayed hash with hash in file `umix-bionic-mini-2018.11-desktop-amd64.sha512`

Hashes should match if the file is not corrupted.

## Standard ISO

Open a command window and type:

```bash
sha256sum umix-bionic-std-2018.11-desktop-amd64.iso
```

Compare the displayed hash with hash in file `umix-bionic-std-2018.11-desktop-amd64.sha512`

Hashes should match if the file is not corrupted.