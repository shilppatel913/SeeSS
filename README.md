CSS is a styling language which is known as Cascading Style sheets.
The syntax of css is pretty straightforward
selector{
  property1:value1;
  property2:value2;
}

There are three types of selectors in css
1) Element selector - div,h1
2) Class selector - giving a class name to a particular element
    An element can have multiple classes
 3) Id selector - giving an id to particular element
    An element can have only one unique id
    
 Inline CSS has the highest preference over external or css used in the head tag
  
  Order of preference among elements,classes and id
      id>class>element
  
  You count the number of id's present if they are same then you count the number of classes present if they are also same then you count the number of elements present
  if they are also same then the selector which is present at the end will be counted in case of a conflict.
  
  Elaborating the color property
  1) We can simply mention the name of the color
        color : red;
  2)  We can use hexadecimal values 
      color : #FFFFFF    we have first two digits for red then for green and the last two digits for blue. The range is from 0 to 15(#F)
  3) We can use the rgb function and pass the values
        color : rgb(255,255,0)
        we can use rgba where a denotes degree of transparency from 0 to 1
        0 mean completely transparent and 1 means opaque.
  4) We can use hsl ans hsla function also to give the color property.
