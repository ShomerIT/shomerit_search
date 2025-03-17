# Search syntax

ShomerIT comes with a search syntax by with you can modify the search engines used.

## `!` select engine and category

To set category and/or engine names use a `!` prefix.  To give a few examples:

- search in Google for **paris**

  - {{search('!go paris')}}
  - {{search('!google paris')}}

- search in Brave for **london**

  - {{search('!br paris')}}
  - {{search('!brave paris')}}

## `:` select language

To select language filter use a `:` prefix.  To give an example:

- search Google by a custom language

  - {{search(':fr !go ShomerIT')}}