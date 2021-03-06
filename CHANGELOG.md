# Change Log

All notable changes to the "license-inserter" extension will be documented in this file.

## [1.0.0]

- Initial release

## [1.0.1]

- Fix adding the license and copyright header to files which already have it
- Fix adding the header to the end of the line instead of new line when a file has only one line

## [1.0.2]

- Fix not honoring the extension settings
- Format languages with /**/ block comment to prefix all lines in the header with *

## [1.0.3]

- Fix a bug that caused to fail if vscode language configuration is JSON with comments
- Change invocation command from `Copyright: insert.header` to `Copyright: Insert Header`

## [1.0.4]

- Update Apache license URL schema from `http://` to `https://`

## [1.0.5]

- Fix ([#3](https://github.com/minherz/copyright-inserter/issues/3)) by configuring extension to run on local host.

## [1.0.6]

- Add option always select one line comment.
- Support languages without comments.
