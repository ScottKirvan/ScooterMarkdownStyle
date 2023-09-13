WHITEBOARD
=========
> **Note**
>  A **Whiteboard** is a temporary spot that notes are jotted down and then
> erased.  Use it for things like brainstorming, ideation, offloading, etc.
> These notes are ***not*** important and can be erased at any time.


I'm finding some elements that don't deploy/publish properly.  I'll have to find out where to
report these.

# Alternate Headers
Underlined H2 Headers don't format properly 

Raw:
```
H2 Header
---------
```
On GitHub.com:

![](../assets/media/Pasted%20image%2020230913102738.png)

On Deployed Page:

![](../assets/media/Pasted%20image%2020230913102806.png)

For Preview Testing:

H2 Header
---------


# Github style Note/Warning callouts

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


# Tables
Table formatting breaks when preceded by a paragraph without a break.

Raw:
```
Alignment (possible bug):
| Item              | In Stock |  Price |
| :---------------- | :------: | -----: |
| Python Hat        |   True   |  23.99 |
| SQL Hat           |   True   |  23.99 |
| Codecademy Tee    |  False   |   9.99 |
| Codecademy Hoodie |   n/a    | 142.99 |
```

On GitHub.com:

![](../assets/media/Pasted%20image%2020230913102242.png)

On Deployed Page:

![](../assets/media/Pasted%20image%2020230913102305.png)

For Preview Testing:

Alignment (possible bug):
| Item              | In Stock |  Price |
| :---------------- | :------: | -----: |
| Python Hat        |   True   |  23.99 |
| SQL Hat           |   True   |  23.99 |
| Codecademy Tee    |  False   |   9.99 |
| Codecademy Hoodie |   n/a    | 142.99 |




