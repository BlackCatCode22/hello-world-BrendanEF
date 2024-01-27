# Video 03

`sh = input("Enter Hours: ")`
`sr = input("Enter Rate: ")`
`fh = float(sh)`
`fr = float(sr)`
`# print(fh, fr)`
`if fh > 40 :`
    `# print("Overtime")`
    `reg = fr * fh`
    `otp = (fh - 40.0) * (fr * 0.5)`
    `# print(reg,otp)`
    `xp = reg + otp`
`else:`
    `# print("Regular")`
    `xp = fh * fr`
`print("Pay:",xp)`

## Windows PowerShell Terminal

(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Pay: 500.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Enter Rate: 10
Pay: 100.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 50
Enter Rate: 10
Pay: 500.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Enter Rate: 10
Pay: 100.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 50
Enter Rate: 10
Pay: 500.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 50
Enter Rate: 10
Overtime
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Enter Rate: 10
Pay: 100.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 50
Enter Rate: 10
Overtime
500.0 50.0
Pay: 550.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Enter Rate: 10
Pay: 100.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 50
Enter Rate: 10
Pay: 550.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python>

---

# Video 04

`sh = input("Enter Hours: ")`
`sr = input("Enter Rate: ")`
`try:`
    `fh = float(sh)`
    `fr = float(sr)`
`except:`
    `print("Error, please enter numeric input")`
    `quit()`

`print(fh, fr)`
`if fh > 40 :`
    `reg = fr * fh`
    `otp = (fh - 40.0) * (fr * 0.5)`
    `xp = reg + otp`
`else:`
    `xp = fh * fr`
`print("Pay:",xp)`

## Windows PowerShell Terminal

Enter Hours: 10
Enter Rate: ten
Traceback (most recent call last):
    fr = float(sr)
         ^^^^^^^^^
ValueError: could not convert string to float: 'ten'
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Enter Rate: 10
Pay: 100.0
Enter Hours: 10
Enter Rate: 10
XYZ Pay: 100.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Enter Rate: ten
Traceback (most recent call last):
  File "C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python\conditionalModule2.py", line 20, in <module>
         ^^^^^^^^^
ValueError: could not convert string to float: 'ten'
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Error, please enter numeric input
Traceback (most recent call last):
  File "C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python\conditionalModule2.py", line 25, in <module>
    print(fh, fr)
              ^^
NameError: name 'fr' is not defined. Did you mean: 'sr'?
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Enter Rate: 10
10.0 10.0
Pay: 100.0
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py conditionalModule2.py
Enter Hours: 10
Enter Rate: ten
Error, please enter numeric input
(.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python>
