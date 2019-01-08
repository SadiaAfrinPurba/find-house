About grid layout:

1. min-content -> create line breaks of the content and grows by vertically

2. max-content -> does not create line breaks and grows by horizontally

3. minmax() -> pass 2 values and the tracks will occupy between these two numbers

4. auto-fill -> auto-fill FILLS the row with as many columns as it can fit. So it creates implicit columns         whenever a new column can fit, because it's trying to FILL the row with as many columns as it can.

5. auto-fit -> auto-fit FITS the CURRENTLY AVAILABLE columns into the space by expanding them so that they take    up any available space and collapse the empty space by 0px.

6. 1fr means one fractional unit that represents a fraction of available space.
   For example: grid-template-columns: 1fr 2fr 1fr; 
   Here, 2nd column would take 2 times bigger space than rest of the columns.

7. **Responsive trick without media queries: 
   grid-template-columns: repeat(auto-fit, minmax(200px,1fr));

8. column/row-end: 1 -> only works when rows are declared explicitly.

9. text,before and after pseudo elements can be grid items

10. align-items--> row axis , justify-items-->column

