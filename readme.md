# 📚 Markdown Demo Cheat Sheet

## 🏷️ Headings

# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading

---

## ✍️ Text Formatting

**Bold Text**  
*Italic Text*  
***Bold and Italic Text***  
~~Strikethrough Text~~  

> This is a blockquote  
>> Nested blockquote for deeper thoughts

Inline quote: `Use backticks for code-like text`

---

## 📋 Lists

### 🔸 Unordered List
- Item A
  - Subitem A.1
    - Sub-subitem A.1.a
- Item B
* Item C
+ Item D

### 🔢 Ordered List
1. First item
2. Second item
   1. Sub-item 2.1
   2. Sub-item 2.2
3. Third item

---

## 🔗 Links

[OpenAI Website](https://www.openai.com)  
<https://www.github.com> (Auto-linked)

Reference-style:  
[Google][1]  
[1]: https://www.google.com

---

## 🖼️ Images

Basic Image:  
![Placeholder](https://via.placeholder.com/150)

Image with Title Tooltip:  
![GitHub Demo](https://github.com/rizzhubkr/github-demo/blob/main/demo.png "Demo Image")

Image as a link:  
[![OpenAI Logo](https://via.placeholder.com/100)](https://www.openai.com)

---

## `Code` & Code Blocks

### Inline `code`

Use backticks `` ` `` for inline `code`.

### Multi-language Code Blocks

#### JavaScript
```js
// Greet function
function greet(name) {
  return `Hello, ${name}! 👋`;
}
console.log(greet("World"));

#### Python
```python
# Greet function
def greet(name):
    return f"Hello, {name}! 👋"

print(greet("World"))

