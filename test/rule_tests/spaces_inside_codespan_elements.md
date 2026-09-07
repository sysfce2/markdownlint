`normal codespan element`

Codespans require surrounding spaces when escaping backticks:
A triple backtick in a codespan: ` ``` `

These can also be surrounded by brackets or quotes:
A triple backtick in a codespan: (` ``` `)
A triple backtick in a codespan: [` ``` `]
A triple backtick in a codespan: "` ``` `"

`codespan element with space inside right ` {MD038}

We SHOULD have the following two tests marked with MD038 failurs
` codespan element with space inside left`
` codespan element with spaces inside ` but
kramdown doesn't see that as a codespans so we can't detect them anymore.
