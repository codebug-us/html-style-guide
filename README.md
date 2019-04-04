# HTML Spacing Style Guide
### Why indent at all? 
The goal of indenting your code is to make it easy to read. Code that is easy to read, is easier to debug. Many amateur developers decide that it's not necessary to worry about things like indentation early on, especially since their HTML pages are simple and bug-free. To them, it doesn't seem necessary. 

However, each time you code, you're building habits. These habits will stick with you, and building improper habits early on just means you'll have to unlearn those habits later, which is harder than just doing it right from the beginning. Plus, it's incredibly annoying to read someone's code who doesn't indent correctly. So if you want other developers to like working with you, **INDENT CORRECTLY!**

### So what are the indentation rules? 
The rules are somewhat flexible, and each developer has his/her own preferences. 
However, there are some hard rules that you must abide by: 

1. Put your opening and closing HTML tags on their own line.
    - Example: 
        ``` HTML
          <p>
            This is a good example of both putting your HTML elements on their own line. 
            Notice that the content inside the HTML element is indented.
            Also take note that the closing tag (</p>) is aligned perfectly with the opening tag (<p>). 
          </p>
        ```
    - Exceptions: 
        * If you are using a paragraph `<p>`, `<li>`, or any header `<h1>, <h2>, ...` tag, and there are very few words inside your element, it's okay to put them on one line. 
            - This is fine: 
              ``` HTML
                <h1>My Website</h1>
              ``` 
            - Bad: 
              ``` HTML
                <p>This is a paragraph containing a lot of text. There is so much text that it can be 
                  confusing to see where the paragraph starts and ends. So it's really best to indent 
                  this like you'll see below.</p>
              ``` 
            - Good:
              ``` HTML
                <p>
                  This is a paragraph containing a lot of text. There is so much text that 
                  it can be confusing to see where the paragraph starts and ends. 
                  But looking at it in this format makes it easy to understand!
                </p>
              ``` 

1. Nested HTML elements should be indented to the right of their "parent" element.
    - Good:
      ``` HTML
        <div id='parent'>
          <p id='child'>
            Note that the paragraph tag is indented once so it is inside both the opening and 
            closing tag of the div. In this scenario, the div is the "parent" element, 
            and the paragraph is the "child" element.
          </p>
        </div>
      ```
     - Base:
      ``` HTML
        <div id='parent'>
        <p id='child'>
          Note that the paragraph tag is indented once so it is inside both the opening and 
          closing tag of the div. In this scenario, the div is the "parent" element, 
          and the paragraph is the "child" element.
        </p>
        </div>
      ```

1. Remember the main objective: **make your code readable by others!** 
