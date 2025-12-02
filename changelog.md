## v0.2.8-r11-g86273c6

Changes since v0.2.8-r10:
* 	modified:   src/mount/magic.rs
* 	modified:   src/mount/magic.rs
* fix(mount): force partition nodes to directory type
* fix(mount): force root partitions to be directories to prevent system overlay
* fix(mount): allow tmpfs creation on existing system directories
* feat(webui):filte bot user in contributors list
* fix(mount): enforce system-only mount strategy
* fix(mount): improve root partition promotion logic
* fix(mount): fix tmpfs creation error on root symlinks
* fix(mount): update partition scanning logic
* [skip ci] Update KernelSU json and changelog for v0.2.8-r10