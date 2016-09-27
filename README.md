# CitrusFramework
A simple web framework to aid in web development with a responsive approach.


###Basic Column Sizes
The classes for this grid system are pretty simple. Citrus has 2 different breakpoints which occur at 600px and 900px. To change the grid at <600px, use the prefix ".d" for diminuitive. For 600px-900px, use ".s" for small. Anything over 900px will use the ".l" prefix for large. The grid is percentage based with the allowed percentages being 10, 20, 25, 30, 33, 40, 50, 60, 66, 70, 75, 80, 90, and 100. Below are examples of the classes along with the action they would perform.

| Class | Effect|
|-------|-------|
|.d-10|Creates a column with a width of 10% of its parent on screens below 600px.|
|.s-33|Creates a column with a width of 33.3333333333% (or 1/3) of its parent on screens between 600px and 900px.|
|.l-100|Creates a column with a width of 100% of its parent on screens greater than 900px.|

Note: For grid to work correctly, columns must have "column" class in addition to the desired size. By default a column is 100% width.


###Offset Columns
Sometimes it may be necessary to move a column over. This is easily done by adding an "o" to the beginning of the class name for offset.
This could be used to center an element or just create a margin.

|Class|Effect|
|-----|------|
|.od-10 .d-20|Creates a column with a width of 20% and offsets it by 10% on screens that are less than 600px.|
|.os-25 .s-50|Creates a column with a width of 50% and offsets it by 25% on screens between 600px and 900px.|
|.ol-66 .l-33|Creates a column with a width of 1/3 and offsets it by 2/3 on screens larger than 900px.|


###Height Classes
The Citrus Framework also includes preset height classes for ease of development. Height classes use "h" as a prefix and have the following options: 250, 500, 750, or 1000. There is also a "responsive" class, which does not require the "h" prefix and makes the items size responsive.

|Class|Effect|
|-----|------|
|.h-250|Sets element height to 250px.|
|.h-750|Sets element height to 750px.|
|.responsive|Sets element to become responsive (grows and shrinks according to width of element).|


###Max Width
Dont want your design to grow past a certain width? There are classes for that too. The two default max widths are easy to remember since they match the breakpoints. The prefix for this is "max" followed by the size of the breakpoint you want to use. The two classes are listed below.

|Class|Effect|
|-----|------|
|.max-s|Element has a maximum width of 600px.|
|.max-l|Element has a maximum width of 900px.|

Note: For this rule to work, element must have column class.

###Utility Classes
Included with Citrus Framework are some simple utility classes. These are just some extras to help get your site up and running even faster. The utility classes included with the Citrus Framework are listed below.

|Class|Effect|
|-----|------|
|.left|Floats element to the left.|
|.right|Floats element to the right.|
|.align-left|Aligns text to the left.|
|.align-right|Aligns text to the right.|
|.h-center|Horizontally center aligns text.|
|.v-center|Vertically centers everything within element.|
|.circle|Makes element into a circle.|
