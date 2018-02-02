# rotating_matrices
Archetype for function that rotate pictures

/* Editor programs will often take pictures and offer options to rotate them 90 degrees left or right. Pictures may
   be represented as matrices of pixel values from 0 to 255 if they are black and white. This program allows users to rotate
   pictures 90 degrees left or right by rearranging the pixel values to satisfy our conditions.

   To use the program:
   Enter the rows and then the columns for the matrix of pixel values (i.e 2 for rows and 3 for cols)

   enter rows: 2
   enter cols: 3

   then you'll be prompted to enter 2*3 = 6 pixel values
   0 255 255
   0 255  0     will be our desired matrix and will transform accordingly to the following:

   rotated left 90 degrees:
   255  0
   255 255
    0   0

   rotated right 90 degrees:
     0   0
    255 255
     0  255

*/
