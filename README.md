# AlgoInvestAndTrade

AlgoInvest is a training project part of "Python Application Developper" training of OpenClassrooms. It's program that can determine which share is best to buy thanks to three different algorithm. 

Each algorithm have different Time and space complexity and I recommend using optimized for huged amount of data as it's the fastest and most accurate of the three.

##  Download & Create virtual env

For this software you will need Python 3 (made on Python 3.9.6 as Numpy isn't yet realeased on 3.10)

Open a terminal and navigate into the folder you want AlgoInvest to be downloaded. Then run the following commands: 

* From repository download files and clone the folder.
    ```
    $ git clone https://github.com/AatroXissTV/AlgoInvestAndTrade.git AlgoInvest
    $ cd AlgoInvest
    ```
* Create a Python environment named "env".
    ```
    $ python -m venv env
    ```
* Activate the environment.
    ```
    $ source/env/bin/activate #MacOS & linux
    $ source/env/Scripts/activate # Windows
    ```
* Install packages from **requirements.txt**.
    ```
    $ pip install -r requirements.txt
    ```

## How to Use the software

* Once you have created the environment and the requirements.txt you can execute the script that way :
    ```
    $ python scripts.py scripts.py -h
    ```
* You have 1 positionnal arguments that you MUST input. Choose between bruteforce, greedy & optimized: 
    ```
    $ python scripts.py optimized
    ```

You have the possibility to add optional arguments.

* If you want to input file you can do it with absolute & relative path that way:
    ```
    $ python scripts.py -f databases/dataset.csv optimized
    ```
* If you want ot change the budget of a wallet you can with the following optional argument:
    ```
    $ python scripts.py -f databases/dataset.csv -b 500 optimized
    ```


## Updates

Hi everyone, 
I  finished this OpenClassrooms project! Everything works according to the specifications 

## TO DO

**


## Author

This software was made by Antoine "AatroXiss" Beaudesson with :heart: and :coffee:

## Support

Contributions, issues and features requests are welcome ! 
Feel free to give a ⭐️ if you liked this project. 