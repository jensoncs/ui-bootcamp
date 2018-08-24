selector {
	property: value;
}

# Types of selector 

1. Elemement 

li {
	
}

2. Class

.class {
	
}

3. Id

#id {
	
}

4. * {
	
}

Select everything on the page.

5. Descendant Selector

li a {
	
}

Selector will select multiple tags

6. Adjcent Selector 

h4 + ul {
	
}

will select All uls after h4


7. Attribute selector

a[href="https://www.google.com/"] {
  background: blue;
}

input[type="checkbox"] {
	
}

Select dependings upon the attribute

This will select all the href=https://www.google.com and set the background as blue.
