
## **CS599 Graph Analytics** by  **Dr. Charalampos Tsourkakis** at Boston University 

Clone the repository and follow the below given instructions to run the codes


An example format of command you need to run is like the one below

```python3.9 cs599.py <dataset.txt> <operation>```

We basically do two operations 
- find_triangles
- triangle_packing

Then you will come across this text when you select find_triangles

Methods available 
1) Chiba_nishizeki
2) leapfrog trijoin

Select the method index : 

Based on the index you select, one of the methods will be executed and you will see the output in the terminal 

A **Flame Graph** will appear on firefox browser and **memory profile** will pop up after a while as a pop up




The code will run twice, first time to check the duration of execution and the second time to check how much memory the code is occupying during the execution of the code 


## To find triangle packing for a data 

#### Try Executing the following codes mentioned
- For grqc dataset
``` python3.9 cs599.py grqc.txt triangle_packing ```

- For github social
``` python3.9 cs599.py musae_git_edges.csv triangle_packing```

- For web berkstan dataset
```python3.9 cs599.py web-BerkStan.txt triangle_packing```

## To find Triangles in a given dataset

After you execute one of the below commands in terminal, you will be prompted to select one of the two methods specified 

1) **Chiba Nishizeki** 
2) **Leapfrog trijoin** 

- For grqc dataset
``` python3.9 cs599.py grqc.txt find_triangles ```

- For github social
``` python3.9 cs599.py musae_git_edges.csv find_triangles```

- For web berkstan dataset
```python3.9 cs599.py web-BerkStan.txt find_triangles```



