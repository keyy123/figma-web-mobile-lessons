# Basic Shapes and Boolean Operations

<a id="top"></a>
## Table of Content

**Table of content:**
- [Basic Shapes](#item-one)
- [Pen Tool](#item-two)
- [Exercise #1](#item-three)
- [Boolean Operators](#item-four)
- [Exercise #2](#item-five)


<a id="item-one"></a>
[Top](#top)
### Basic Shapes In Figma
- [Shapes Tool](./assets/shapes-in-toolbar.png)
<br/>
- Rectangle (tool) - `R` 
    - Draws rectangles and squares
    - `shift` allows us to create squares 
    <br/>
- Line - `L`
    - Draws lines 
    - Hold `shift` to make lines that are not simply vertical (0 or 180 degrees) or horizontal (90 or 270 degrees)
    <br/>
- Arrows - `Shift + L`
    - Also done within Right sidebar 
    <br/>
- Ellipses - `O` 
    - Creates Ovals naturally
    - Holding `shift` allows us to create circles
    - Ellipses also have `arcs`, `ratio`, and `start degree`that allow you make custom shapes like pie charts, spinners, etc.
    <br/>
- Polygon (no shortcut)
    - Make any custom shape with any number of lines
    - Change radius, count (sides)
    <br/>
- Star 
    - Radius
    - Count (sides)
    - Ratio

<a id="item-two"></a>
[Top](#top)
### Pen Tool 
- If you want to make custom shapes and/or vector art, You can use the pen tool 
<br/>
- Selected by pressing `P` or clicking on it
<br/>
- We can create lines and connect them to create new things

[custom shape using pen tool](./assets/custom-shape-from-pen.png)


<a id="item-three"></a>
[Top](#top)
#### Exercise 1
- Create a shape for each item within the shape tool (Rect, Ellipse, Star, Polygon, etc.)

<a id="item-four"></a>
[Top](#top)
### Boolean Operations

[Boolean Operators](./assets/boolean-operators-in-top-toolbar.png)

- After selecting elements, You can use boolean operators to...:
<br/>
- Merge them together (Union)
<br/>
    - [Union Operator](./assets/union-of-two-circles.png)
    <br/>
    - It will combine the selected elements into a new group called a `union`
    <br/>
    - Fun fact: The color from one of the elements will overlap to the other element(s) as well. *Insert Highlander Quote*
    <br/>
- **Subtract** 
    <br/>
    - Only the bottom layer shape in the subtraction is solid, all other shapes on upper layers are removed from the bottom shape.
    <br/> 
    - [Before](./assets/before-subtraction.png)
    <br/>
    - [After](./assets/after-subtraction.png)
    <br/>
- **Intersect** 
    <br/>
    - creates a group of only the overlapping parts of all layers in the selection
    <br/>
    -  [Before](./assets/before-subtraction.png)
    <br/>
    - [intersect](./assets/after-intersect.png)
    <br/>
- **Exclude**
    <br/>
    - The opposite of intersect
    <br/>
    - It creates a new group where the only parts that are visible are the parts that don't overlap
    <br/>
     -  [Before](./assets/before-subtraction.png)
     <br/>
     - [After Exclude](./assets/after-exclude.png)
    
<a id="item-five"></a>
[Top](#top)
#### Exercise 2
- Create 4 copies of 2 shapes and make sure they overlap
(total of 8 shapes)
<br/>
- Using the boolean operators, make sure complete 1 of each boolean operation
<br/>
[Top](#top)
