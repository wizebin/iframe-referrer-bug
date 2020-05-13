## Intro


On iOS safari, the query parameters are stripped from document.referrer when the iframe is from a different origin


On every other browser these query parameters are not stripped

## Steps

1. Run this site (see [the example](http://iframe-referrer-bug.wizebin.com))
2. Add a query parameter (you can use the link on the page labeled `Click here to add param to this window` to add one)
3. Review the document.referrer value inside the iframe box, note the value should be **exactly** the same as the value in your url bar and the referenced `document.referrer Should Be` field
