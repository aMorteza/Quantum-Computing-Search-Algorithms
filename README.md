# Quantum-Computing-Search-Algorithms in python:
Implementing the Grover and Deutsch_Jozsa quantum search algorithms, best in world! 

## This project implemented using python 3.9 in emulated Windows 10 Arm64-x86. 
## Following instructions are required to run the codes. 


* Create and Activate virtual environment:

```
	python -m venv ./venv

	./venv/Scripts/activate

```

* Install following packages:

```
	python -m pip install numpy 

	python -m pip install matplotlib

	python -m pip install absl-py

	python -m pip install scipy

```

* The Grover and Deutsh-Josa algorithms implemented in /src directory, you can run each one via:

```
 	python .\grover.py 
	
	python .\deutsch_jozsa.py 

```


* Good to mention helper functions implemented in /lib directory .
( There is also another Grover's algorithm using sympy which is not
  efficient for high numbers of Qubits, to run it need to add package:

	```
	python -m pip install sympy

	```
)


Any Question? 
-Feel free to feedback amh.morteza@gmail.com