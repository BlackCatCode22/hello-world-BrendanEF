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
