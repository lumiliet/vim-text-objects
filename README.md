# vim-text-objects

Vim plugin that adds some new text objects I felt was missing. Two for working with the entire buffer and two for the last visual selection. `if` and `af` (mnemonic: file) both operate on the entire buffer. `iv` and `av` both represent the last visual selection.

## Examples

* `div` delete the last visual selection.
* `>av.` indent the last visual selection twice.
* `=af` auto indent the entire buffer.
* `vif` select entire buffer in visual mode.

## Notes

`if` and `af` work in visual mode. `iv` and `av` make no sense in visual mode so they do nothing.
