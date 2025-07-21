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
[![OpenAI Logo]([https://via.placeholder.com/100](https://media.discordapp.net/attachments/1230712447300669522/1396821894522470441/5A557332-2C11-4564-8658-A016B646BD80.jpg?ex=687f7b43&is=687e29c3&hm=ba3ead3c6f67cb413114c3757e974feabf89d450d9e2a378c53166df46ef8e87&=&format=webp&width=239&height=438))]([https://www.openai.com](https://github.com/rizzhubkr))

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

