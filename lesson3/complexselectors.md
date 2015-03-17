# Complex Selectors
## Common Selectors
* Type Selectors(h1)
* Class Selectors(.demo)
* Id Selectors(#demo)

## Child Selectors
* Descendant Selector(.demo p)
* Direct Child Selector(.demo > p)

## Sibling Selectors
* General Sibling Selector (h1 ~ p)
* Adjacent Sibling Selector (h1 + p)

## Attribute Selectors
* Attribute Present Selector(a[target])
* Attribute Equals Selector(a[target="http://google.com/"])
* Attribute Contains Selector(a[href*="login"])
* Attribute Begins With Selector(a[href^="https://"])
* Attribute Ends With Selector(a[href$="pdf"])
* Attribute Spaced Selector(a[rel~="tag"])
* Attribute Hyphenated Selector(a[lang|="en"])

## Pseudo-classes
* Link Pseudo-classes(a:link)
* User Action Pseudo-classes(a:hover)
* User Interface State Pseudo-classes(input:enabled)
* Structural & Position Pseudo-classes
    * :first-child
    * :last-child
    * :only-child
    * :first-of-type
    * :last-of-type
    * :only-of-type
    * :nth-child(n)
    * :nth-last-child(n)
    * :nth-of-type(n)
    * :nth-last-of-type(n)
* Target Pseudo-class(section:target)
* Empty Pseudo-class(div:empty)
* Negation Pseudo-class(:not(.intro))

## Pseudo-elements
* Textual Pseudo-elements
* Generated Content Pseudo-elements
* Fragment Pseudo-element(::selection)
