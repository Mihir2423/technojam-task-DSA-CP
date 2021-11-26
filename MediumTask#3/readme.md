First input the the row, n and column, m of array then accept the value of the two d array.
Start the i loop from 0 to n and another j loop inside it from m-2 to 0.
Create an element to store the right value of the column i.e a[i][j+1].
Create another element to store the diagonally right up element of the array. Also check if the arr element is in 1st row or not . If it is in 1st row then store the value 0 in diagonally right_up variable.
Create another element to store the diagonally right down element of the array. Also check if the arr is in last row element or not .If it is in last column then store the value 0 in diagonally right_up variable.
Then add the element of a[i][j] with max of above three variables using math function. 
After the termination of both loop find the value of largest element in 1st column. Display the value.
