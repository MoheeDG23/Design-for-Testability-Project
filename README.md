# Time Frame Expansion using Extended D-Algorithm

### D-Algorithm

The flow of the algo:
![image](https://user-images.githubusercontent.com/66485507/125675418-0cc0f7ce-2a91-4098-9c92-474976e6a411.png)

We convert a given circuit to a graph maintained by a Adjacency List:
The various gates, PIs, POs and branches are assigned unique vertices and various nets are represented by weighted edges joining the different vertices.
 
For example: 
![image](https://user-images.githubusercontent.com/66485507/125675956-8997cd38-1b3b-48c6-9663-9475e5b3affa.png)
![image](https://user-images.githubusercontent.com/66485507/125676017-d1123371-b179-4579-97ae-072919471e25.png)

### Extended D-Algorithm

Now for sequential circuits we divide each instance (state) of the circuit into time frames and convert it into a bigger combinational circuit as D-Algorith works only for Combinational circuits. This neat little trick helps us solve for sequential circuits. Our algo works for upto 4-timeframes before declaring the fault as untestable.

An Example:
![image](https://user-images.githubusercontent.com/66485507/125676554-f3793896-877c-4921-913b-c68d222579b4.png)
![image](https://user-images.githubusercontent.com/66485507/125676571-17ef0eb9-2870-4461-86ce-3ba0f5fef094.png)
![image](https://user-images.githubusercontent.com/66485507/125676594-864e1685-11ab-43f4-ab7d-0e2b77b0de1e.png)


Find more about Time Frame Expansion in the paper provided in the repo. Happy Learning!!

PS: The cpp files contain the code for the D-Algorithm for combinational circuits. The Jupyter Notebook contains the examples for Time Frame expansion written in Python. 
