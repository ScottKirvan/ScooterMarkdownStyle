WHITEBOARD
=========
> **Note**
>  A **Whiteboard** is a temporary spot that notes are jotted down and then
> erased.  Use it for things like brainstorming, ideation, offloading, etc.
> These notes are ***not*** important and can be erased at any time.


I'm finding some elements that don't deploy/publish properly.  I'll have to find out where to
report these.

## Alternate Headers
```
H2 Header
---------
```

produces:

H2 Header
---------

should be same as:

## H2 Header

---

## Github style Note/Warning callouts

```
> **Note** 
> GitHub Note callout
```

> **Note** 
> GitHub Note callout

```
> **Warning** 
> GitHub Warning callout
```

> **Warning** 
> GitHub Warning callout

These are parsed as plain paragraph text.
They need a &lt;span&gt; or something so the css can style it.
