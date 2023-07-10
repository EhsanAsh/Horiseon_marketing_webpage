# User Story:

### AS A marketing agency:
*I WANT a codebase that follows accessibility standards, SO THAT our own site is optimized for search engines.*

# Acceptance Criteria:
*GIVEN a webpage meets accessibility standards:*
1. WHEN I view the source code
    THEN I find semantic HTML elements
2. WHEN I view the structure of the HTML elements
    THEN I find that the elements follow a logical structure independent of styling and positioning
3. WHEN I view the image elements
    THEN I find accessible alt attributes
4. WHEN I view the heading attributes
    THEN they fall in sequential order
5. WHEN I view the title element
    THEN I find a concise, descriptive title

# Algorithm:
**Modify given webpage to meet accessibility standards in order to optimize the webpage for search engines.**

## Tasks:
1. Use semantic HTML elements to modify the file.
2. Modify the structure of the HTML file so that the elements follow a logical structure without any styling and positiong attributes.
3. use accessibility attributes for image elements.
4. Check and modify the sequance of heading elements.
5. Modify the title attribute to find a concise, descriptive title

## Pattern Recognition:
1. inspect issues line by line
2. modify issues related to structure, logic and accessibility
3. every element should be clear to read and whole HTML file should follow a logical flow.

## Abstraction:
**ignore styling and positioning (Not asked for)**

## sequence:

**Event1:**
If (an element is not semantic){
    change it to proper, related semantic element
}
else{
    leave it
}

**Event2:**
for (every element in the html structure){
    modify elements and indentation to reach the logical and readable structure 
}

**Event3:**
for(every image element){
    if(the element doesn't meet accessibility standards) {
        modify the element 
        add related accessibility elements
    }
    else{
        leave it
    }
}

**Event4:**
for(every heading elements in the structure){
    Check and modify the sequance of heading elements.
}

**Event5:**
if(the title is not descriptive){
    modify the title to address a proper title
}
else{
    leave it!
}

## Debug:
**N/A**
