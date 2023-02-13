# CSS Units are of Two types:
## Absolute
- These are not scalable(Not Responsive) can't adjust itself based on device
- Consists of: <b>px</b>

## Relative
- These are scalable(Responsive) can adjust itself based on device.
- Relative means the size of the current ele is dependent on the value of some base(parent) element and according to the base element it will keep changing itself.
- Consists of:
    - <b>rem</b>: Relative to the Root HTML element (Most of the Browser: 16px and changes based on font size)::     1 rem = 1 * 16px,  2 rem = 2 * 16px
    
    - <b>em</b>: Relative to itself i.e it's default value(if default not there it will go to parent) Ex if we have HTML [ DIV1 [ DIV2 ]] -> em for Div2 will take value from DIV1 if present or else HTML

    - <b>vh</b>: Relative to ViewPort Height. Ex 10vh => 10% of the ViewPort Height
    
    - <b>vw</b>: Relative to ViewPort Width. Ex 10vw => 10% of the ViewPort Width

        - <b>%</b>: Percentage is relative to its parent element. Ex HTML [ DIV1 [ DIV2 ]] :: Div2 is dependent on Div1
    
