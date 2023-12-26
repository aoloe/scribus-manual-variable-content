# Variable content in Scribus

## Page numbers

- In the master page, add a text frame in the header or footer area
- In the text frame "Insert > Character > Page Number".

## The _current_ date

Scribus does not offer a way to insert date fields in the document. The reason for this, for layout it is not clear what is the meaning of updating a date field.  
Most of the time, the date corresponds to the issue date and, for archived document, you normally don't want it to change when you open it.  
Also, very often you will want to use the date when the printed result will be first distributed, not the the one from the time when you finished (or started) the layout.

There are two main ways to insert the _current_ date:
 
- If you want to display the date on each (even / odd) page, you can type it in a text frame in the header / footer area of (each affected) master page.
- If you want to display the date in the same way in its own text frame, you can use a pattern / symbol (linked scrapbook elements).
- If you want to display the date in multiple different places, you can create a _Variable text_.

TODO: describe in details how to do the above listed operations.

## Heading numbering

- Define a paragraph style for each heading
- In the "Paragraph Effects", activate the "Numbered List" section and define the numbering as needed.
