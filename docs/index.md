

wow perfect! 


## test 


### hello world 

> [!INFO]
> information block 


<mark style="background: #FFB86CA6;">TODO</mark> text with background, 

> [!WARNING]
> fdsfsdaffa


$\displaystyle f(x + h) = f(x) + f'(x)h + f''(x) \frac{h^{2}}{2!} + \dots$



1. 关于 $\displaystyle \overline{X}$
	- $\displaystyle \overline{X}=N\left( \mu,\frac{\sigma^{2}}{n} \right)$
	- $\displaystyle \textcolor{blue}{ \frac{\overline{X}-\mu}{\frac{\sigma}{\sqrt{ n }}} =\frac{\sqrt{ n }(\overline{X}-\mu)}{\sigma}\sim N(0,1) }$ 
2. 关于 $\displaystyle S^{2}$
	- $\displaystyle \textcolor{blue}{ \frac{(n-1)S^{2}}{\sigma^{2}}= }\textcolor{blue}{ \sum_{i=1}^{n}\left( \frac{X_{i}-\overline{X}}{\sigma} \right)\sim χ^{2}(n-1) }$  
	- $\displaystyle \frac{1}{\sigma^{2}} \sum_{i=1}^{n}(X_{i}-\mu)^{2}=\sum_{i=1}^{n}\left( \frac{X_{i}-\mu}{\sigma} \right)^{2} \simχ^{2}(n)$      
3. $\displaystyle \overline{X}$ 与 $\displaystyle S^{2}$ 相互独立，并且有 $\displaystyle \textcolor{blue}{ \frac{\overline{X}-\mu}{\frac{S}{\sqrt{ n }}}\sim t(n-1) }$ 
	- 进一步有 $\displaystyle \frac{n(\overline {X}-\mu)^{2}}{S^{2}}\sim F(1,n-1)$


$$
 χ ^{2} = X_{1}^{2} +X_{2}^{2}+\dots+X_{n}^{2}
$$

- $\displaystyle E(X_{i}^{2})= D(X_{i})=1$
- $\displaystyle D(X_{i}^{2})=E(X_{i}^{4})-[E(X_{i}^{2})]^{2})=3-1=2 \quad i=1,2,\dots, n$  
- $\displaystyle E(X_{i}^{4})=3 * E(X_{i}^{2})=3$  

    
$$
\lim_{ n \to \infty } P\left\{ \mid \frac{1}{n} \sum_{i=1}^{n}X_{i} - \frac{1}{n}\sum_{i=1}^{n}EX_{i} \mid < \varepsilon \right\}=1
$$

$$
\lim_{ n \to \infty } P\left\{ \mid \frac{1}{n} \sum_{i=1}^{n}X_{i} - \frac{1}{n}\sum_{i=1}^{n}EX_{i} \mid < \varepsilon \right\}=1
$$

$$
\lim_{ n \to \infty } P\left\{ \mid \frac{1}{n}\sum_{i=1}^{n}X_{i} - \mu \mid < \varepsilon \right\} = 1
$$




## Basic Elements

### Headers

# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header

### Emphasis

- *Italic*
- **Bold**
- ***Bold and Italic***
- ~~Strikethrough~~

### Lists

#### Unordered List

- Item 1
  - Subitem 1
  - Subitem 2
- Item 2
- Item 3

#### Ordered List

1. First item
2. Second item
   1. Nested item 1
   2. Nested item 2
3. Third item

### Links

- [Google](https://www.google.com)
- [GitHub](https://github.com)


## Code Blocks

### Inline Code

Here is an example of `inline code`.

### Block Code (various languages)

#### JavaScript

```js
function greet(name) {
    console.log("Hello, " + name + "!");
}
greet("Markdown Tester");
```

#### Python

```py
def greet(name):
    print(f"Hello, {name}!")

greet("Markdown Tester")
```

#### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Markdown Test</title>
</head>
<body>
    <h1>Hello, Markdown Tester!</h1>
</body>
</html>
```

## Blockquotes

> "This is a blockquote. You can use blockquotes to highlight important text or quotes."

## Tables

| Name          | Age | Occupation  |
|---------------|-----|-------------|
| Alice         | 25  | Developer   |
| Bob           | 30  | Designer    |
| Charlie       | 35  | Manager     |

## Horizontal Rule

---

## Task List

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

## Special Characters

HTML Entities: &copy; &reg; &hearts;  
Escaped Characters: \*literal asterisks\*, \#literal hash\#

## Math

You can include inline math like this: $E = mc^2$

You can also have block math:
$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$

## Custom HTML

<p>This is a custom HTML paragraph in markdown.</p>

