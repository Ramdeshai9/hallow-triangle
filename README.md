# hollow-Triangle

Creation of hollow triangle Here we have created a 6 row hollow triangle with * symbol with the for loop
The first for loop is for row creation

 for(int i=1;i<=n;i++)

The second for loop is for column

for(int j=1;j<=m-1;j++)

The third for loop is for display of *

 for(int k=1;k<=2*i-1;k++)

Since we are creating a hollow pyramid we take onlt first column and last column into consideration
And also the last row.

if(k==1 || (k==2*i-1 || i==n))
             
             System.out.print("*");
All the remaining elements of the rows and columns are left empty

else
            
            System.out.print(" ");

A new line is started after every row

 
 System.out.print("\n");

OUTPUT

<img width="674" alt="118581528-69602300-b7af-11eb-9b64-453a18570e3c" src="https://user-images.githubusercontent.com/84003554/124378935-d7b26380-dcd1-11eb-918a-1e44a3ee3d37.png">

