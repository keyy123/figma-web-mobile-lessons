# Auto Layout Properties

### Individual Auto-Layout Properties

- Direction = How to auto-frame will flow
    - Horizontal 
    - Vertical 
- Spacing Between Item
    - PX, %, etc
    - Manually change it using your mouse, or;
    - Change the amount in the right sidebar
- Padding = Empty whitespace between parent and child frames
    - Horizontal Padding 
    - Vertical Padding 
        - Manually dragging it on the canvas
        - Or Input it directly in right sidebar
        - [In rare cases, Input padding for each side individually](../assets/custom-padding.png)
- Alignment 
    - How to align child objects in an auto-frame?
        - Parent frame direction and distribution determine our alignment options we can use
        - [where to find alignment?](../assets/alignment-location.png)
- Distribution 
    - Where to find distribution options for a parent frame?
        - [Distribution Menu Location](../assets/distribution-menu.png)
        - [Distribution Menu Options](../assets/distribution-options.png)
    - How does distribution work?
        - It tells us how the child objects in a parent frame are spaced out
            - Spacing Mode
                - `Packed` = packed based on `spacing between items` unit value in `Auto Layout` section
                - `Space Between` = Evenly space items in frame away from each other evenly and automatically
        - Resizing
            - In auto-layout frames, we can say how big or small an object in the parent frame are (really important)
            <br/>
             - [Resizing Properties in Right Sidebar](../assets/resizing-location.png) 
            <br/>
            - NOTE: These are properties for the child objects within an parent auto-layout   frame (Like flex item properties for flexbox)
            <br/>
             - Resizing Properties (For Horizontal and Vertical)
                - Fixed = layer's dimensions (width or height depending on which resizing is set) is fixed to the value set in the width or height input
                    - [This layer is fixed at 218 pixels](../assets/fixed-option.png)
                - Hug = Set the frame size to be the size of the content (child objects) within it 
                - Fill = the object will fill that dimension (width or height) based on the parent frame's size (if parent is the autoframe) 
                
                - The dimension that is set to fill will be locked since it will automatically be computed based on parent frame size

                - [Width is set to fill but height is fixed to 67 pixels](../assets/fill-option.png)
### Constraints on auto-layout frames
- If an auto layout frame is nested in a normal frame, It will be able to use constraints and resizing on it

- NOTE: If you use distributions options that are not `fixed`, The constraints for that dimension (width or height) will be disabled. 

- Example: If my auto-layout frame has hugging horizontal distribution then, left and right constraints will be disabled

- [Horizontal Hug Blocks Horizontal Constraints](../assets/horizontal-hug-disables-horizontal-constraints.png)

- [Horizontal Fixed Width Enables Horizontal Constraints](../assets/Fixed-Width-Enables-Horizontal-Constraints.png)

#### Exercise #1:

Nest a auto layout frame within a regular frame and add items to it and explore properties to better understand this lesson