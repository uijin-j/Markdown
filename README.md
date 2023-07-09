# Markdown
A lightweight markup language for formatted documents. 

It's a **concise**  and __Human-friendly__.
<br/><br/>

## Markdown Syntax
### 1. Headers  
    # This is an <h1> tag
    ## This is an <h2> tag  
    ###### This is an <h6> tag

### 2. Emphasis
    *This text will be italic*
    _This text will be italic_

    **This text will be bold**
    __This text will be bold__

💻 *This text will be italic*  
💻 **This text will be bold**
<br/><br/>

### 3. Strikethrough
    ~~This~~ will appear crossed out

💻 ~~This~~ will appear crossed out
<br/><br/>

### 4. List
    - Unordered
      * Item 1
      * Item 2
        * Item 2a
        * Item 2b

    - Ordered
        1. Item 1
        1. Item 2
            1. Item 2a
            1. Item 2b

    - Task Lists
        - [x] @mentions, #refs, [links] (), **formatting**, and <del>tags</del> suppored
        - [x] list syntax required (any unordered or ordered list supported)
        - [x] this is a complete item
        - [ ] this is an incomplete item

💻 Unordered
* Item 1  
* Item 2  
    * Item 2a  
    * Item 2b 

💻 Ordered
1. Item 1  
1. Item 2  
    1. Item 2a  
    1. Item 2b  

💻 Task Lists
- [x] @mentions, #refs, [links] (), **formatting**, and <del>tags</del> suppored
- [ ] this is an incomplete item
<br/><br/>

### 5. Links
    http://github.com - automatic!
    [GitHub](http://github.com)

💻 http://github.com
<br/><br/>

### 6. Images
    ![GitHub Logo](images/logo.png)
    Format: ![Alt Text](url)

    cf. Images with custom resizing and alignment
    <p align="center">
    <img src="images/logo.png" alt="Github Logo" width="50%" />
    </p>

💻 <img src="./images/logo.png" width="15" height="15">
<br/><br/>

### 7. Blockquotes
    As Kanye West said:
    > We're living the future so
    > the present is our past.

💻 As Kanye West said:
> We're living the future so  
> the present is our past.

<br/>

### 8. Inline code
    I think you should use an
    `<addr>` element here instead.

💻 I think you should use an `<addr>` element here instead.
<br/><br/>

### 9. Syntax highlighting
    ```javascript
    function fancyAlert(arg) {
        if(arg) {
            $.facebox({div:'#foo'})
        }
    }
    ```

💻  
```javascript
function fancyAlert(arg) {
    if(arg) {
        $.facebox({div:'#foo'})
    }
}
```
<br/>

### 10. Tables
    First Header | Second Header
    ------------ | -------------
    Content from cell 1 | Content from cell 2
    Content in the first column | Content in the second column

💻  
|First Header | Second Header|  
|------------ | -------------|  
|Content from cell 1 | Content from cell 2|  
|Content in the first column | Content in the second column|
<br/>

### 11. Emoji 😊
    :smile:
