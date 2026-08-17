# study-233 Homebrew Formula

Private source Formula for `zotero-pdf2zh-next`. GitHub SSH access to both
private repositories is required.

```bash
brew tap study-233/formula git@github.com:study-233/homebrew-formula.git
brew install --build-from-source study-233/formula/zotero-pdf2zh-next
brew services start zotero-pdf2zh-next
```

This tap intentionally does not publish bottles. The Formula is pinned to a
specific commit in `study-233/zotero-pdf2zh-next` and builds from source.
