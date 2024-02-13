# Constraints

<a id="top"></a>
## Table of Content

**Table of content:**
 - [](#item-one)
 - [](#item-two)
 - [](#item-three)
 - [](#item-four)

<a id="item-one"></a>
[Top](#top)
 ### What are constraints?
 - Constraints tell figma how layers work when you resize the frames they are nested within 
 - [Constraints (before changes)](../assets/constraints-before.png)
 - In short, They are media queries of figma layers. 
 - If you resize the frame that the layers are nested in, We see that the nested layers don't move. They look like they are clipped...
 - [Constraints-after](../assets/Constraints-(after).png)
 <br/>

 <a id="item-two"></a>
 [Top](#top)
 ### Constraint Types
 - There are 2 kinds of constraints:
    1. Horizontal Constraints

    2. Vertical Constraints
        - Center
        - Scale - grow or shrink layer based on resizing of parent frame

- [Constraints in the Right Sidebar](../assets/Constraints-in-the-right-sidebar.png)

- If constraint says top, It means if the parent frame is shrunken or expanded from the top then the nested frame will also stretch and shrink as well.

 <br/>

 <a id="item-three"></a>
 [Top](#top)
 ### Limitations to Constraints
 - Constraints only work on layers that are placed within an existing frame on the canvas

  If you select an element on canvas that is off of frame, You'll notice no constraint properties are available for that layer

  - [No Constraint for layers out of frame](../assets/out-of-frame.png)
 <br/>
 
 - To resize items with frme using `ctrl` to resize frame while ignoring constraints

 #### Exercise #1
 - Create a new frame 
 - Create elements/shapes and play with constraints as well
 [Top](#top)