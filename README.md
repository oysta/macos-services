# oysta's macOS automator services

This is a collection of automator services I've written to help me day to day. Copy the workflows you want to your `~/Library/Services` directory to make them available in the the `Services` context menu.

## Services

### <a name="align-code"></a>Align Code

Knocks out leading indentation from a block of text. Useful when copying code from an indented context but you want to refer to it in isolation in a code review comment or similar without the leading the indentation.

### Strip Diff Hunk Leading

Knocks out the the `+` or `-` from a diff (or anything in the first column) and then aligns the block like the [Align Code](#align-code) workflow. Use this when copying code out of a diff context that includes the `+` or `-` in the selection.
