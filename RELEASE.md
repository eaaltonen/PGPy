# How to make a release

```
python3 -m build --wheel
```

This builds a wheel with `pgpym-...` in lower case and `Metadata-Version: 2.4`.
As of 2026-08-04, PyPI only accepts wheels in lower case.

Older versions of `twine` locally fail when encountering metadata version 2.4,
so use a virtualenv if necessary for uploading.
