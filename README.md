# Markdown features test file

This is a test file for
[Markdown](https://daringfireball.net/projects/markdown/) rendering on
[GitHub](https://github.com/miccoli/markdown-test) and
[Bitbucket](https://bitbucket.org/miccoli/markdown-test).

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-generate-toc again -->
**Table of Contents**

- [Extensions](#extensions)
    - [Footnotes](#footnotes)
- [Quirks](#quirks)

<!-- markdown-toc end -->

# Extensions #

## Footnotes ##

Test of [Pandoc's footnote
syntax](https://pandoc.org/MANUAL.html#footnotes).
Footnotes can be defined inline^[I'm an inline footnote, see
<https://pandoc.org/MANUAL.html#extension-inline_notes>] or with a
regular reference[^1],

[^1]: I'm a regular footnote, see
    <https://pandoc.org/MANUAL.html#extension-footnotes>

## Code blocks ##

1. fenced and 4 space indent

    ```
	function test() {
		console.log("notice the blank line before this function?");
	}
	```

1. fenced and 6 space indent

      ```
      function test() {
	      console.log("notice the blank line before this function?");
     }
     ```

1. 8-space indent

	   function test() {
		   console.log("notice the blank line before this function?");
	   }

# Quirks

Literal &lt;i&gt;

- \<i\>
- \<i>
