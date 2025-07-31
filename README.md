This is a fork of [`chromium`] used to make merging changes into [`cronet`] easy.

[`2b1f7cc`] introduced `LICENSES` directory. AUR rejects commits containing directories with an error like this:

```
remote: error: The following error occurred when parsing commit
remote: error: 2b1f7cc9ea70119109e9ffd559c27b449ff83546:
remote: error: the repository must not contain subdirectories
remote: error: hook declined to update refs/heads/master
```

Hence, commits like that are omitted from this fork. Use `merge-upstream` script to merge changes from the upstream.

[`2b1f7cc`]: https://gitlab.archlinux.org/archlinux/packaging/packages/chromium/-/commit/2b1f7cc9ea70119109e9ffd559c27b449ff83546
[`chromium`]: https://gitlab.archlinux.org/archlinux/packaging/packages/chromium
[`cronet`]: https://aur.archlinux.org/packages/cronet
