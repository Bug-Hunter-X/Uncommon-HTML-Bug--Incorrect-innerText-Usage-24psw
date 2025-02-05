# Uncommon HTML Bug: Incorrect innerText Usage

This repository demonstrates an uncommon bug related to the `innerText` property in HTML.  The bug arises from attempting to append HTML content using `innerText`, which is designed for plain text.

## Bug Description:

The provided HTML attempts to add a paragraph element to the content of a div using `innerText`.  This leads to the paragraph tags being treated as literal text rather than rendered HTML.

## Solution:

The solution uses `innerHTML` instead of `innerText` to correctly append the HTML content to the div. `innerHTML` handles HTML tags properly.
