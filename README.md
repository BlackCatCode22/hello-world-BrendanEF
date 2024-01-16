[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/yh68FUSU)
# tPythonHelloWorld
tPythonHelloWorld

Post your hello world program here as well as any code your created from the videos with the (code these up) tag.

# Video 3
print('hello world')

nzt = input('Enter your name: ')
print("Hello",nzt)

## Windows PowerShell terminal

hello world
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py pythonhelloworld.py
hello world
Enter your name: Brendan
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py pythonhelloworld.py
hello world
Enter your name: Brendan
Hello Brendan
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py pythonhelloworld.py
hello world
Enter your name: Chuck
Hello Chuck

# Video 4
xh = input("Enter Hours: ")
xr = input("Enter Rate: ")
xp = float(xh) * float(xr)
print("Pay:",xp)

## Windows PowerShell terminal

Enter Hours: 10
Enter Rate: 5
Traceback (most recent call last):
  File "C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python\pythonhelloworld.py", line 3, in <module>
    xp = xh * xr
         ~~~^~~~
TypeError: can't multiply sequence by non-int of type 'str'
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py pythonhelloworld.py
Enter Hours: 10
Enter Rate: 10
Pay: 100.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py pythonhelloworld.py
Enter Hours: 35
Enter Rate: 2.75
Pay: 96.25
