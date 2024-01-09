## Table of Content

**Table of content:**
 - [Hello World](#item-one)
 - [First Item](#item-two)
 - [Second Item](#item-three)
 
 <!-- headings -->
 <a id="item-one"></a>
 ### Hello World
 Hello world content goes here
 
 <a id="item-two"></a>
 ### First Item
 First item content goes here
 
 <a id="item-three"></a>
 ### Second Item
 Second item content goes here
 

## Admonitions (Signals)

> ⚠️ **Warning:** Do not push the big red button.

> 📝 **Note:** Sunrises are beautiful.

> 💡 **Tip:** Remember to appreciate the little things in life.

## Images

We will add images to github repo within the assets folder/directory. We will need to use a relative link so github will know we are referring to our repo!

![Alt text](URL "Title")

![Screenshot Picture](/assets/[screen-name].png "Photo title")

Equivalent to this in HTML:

```html
<img src="/repo/assets/pic.png" alt="Screenshot Picture" title="Photo title">
```

note: Use `mv` or `cp` command in bash shell to move screenshots from windows to WSL within the `/assets` directory

## How to resize images

1. Use html `img` tag with `height` and `width` attributes 

```html
<!-- img tag with percentages -->
<img src="http://url/image.png" height="60" width="60" >

<!-- img tag with pixels -->
<img src="http://url/image.png" style=" width:60px ; height:60px "  >
```

2. Use a div tag with css styles for height and width and wrap markdown

```html
<div style="width:60px ; height:60px">
![Employee data](/repository/assets/employee.png?raw=true "Employee Data title")
<div>
```

## Tables 

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph.|


### Tables with list within table cells

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |