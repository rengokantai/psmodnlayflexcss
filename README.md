#### psmodnlayflexcss

#####2
######3
```
.container{
  display:flex (inline-flex)
}
```
for inline-flex, the parent will shrink to the width to child width
######4

use in parent:
```
flex-direction: row-reverse
```

######5
use in parent:
```
flex-wrap: wrap-reverse
```
by default, it will occupy all height  

shorthand: flex-flow: flex-direction flex-wrap

######6 
use in child
```
order:2
```
######7
```
flex: flex-grow flex-shrink flex-basis
```

######8
justify-content(parent):along main axis  
flex-start/flex-end/space-between/sapace-around/center/

align-items(parent) along cross axis.
flex-start/flex-end/center/baseline/stretch(entire height)

align-self(child)

align-content(multiple line flex)
param same as justify-content(default:stretch)
######9

three columns, if want to set one column 50%, other two 25% respectively,
then
item1{flex: 0 0 50%}
item1{flex: 1 1 25%}
item1{flex: 1 1 25%}
