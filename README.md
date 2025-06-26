# PyCommandExecutor

## Commands

```plain
- Commands?
- CommandHistory        [(List) or (Delete)]
- Clear
- DeleteData
- RerunCode
- UpdateCode
- Exit                  [NA or (Imm)]
- ChangeUsername        [<<Username>>]
- Time
- DaysUntil             <<Year/Month/Day>> & NA or <<Year/Month/Day>>
- Calendar              [NA or <<Year>>]
- Timer                 [<<Time>>]
- Stopwatch             [(Start) or (Stop) or (Reset)]
- SelectRandomItem      [<<Items>>]
- SelectRandomNumber    [<<Number>>] & [<<Number>>]
- GeneratePassword      [<<Length>>] & [<<Quantity>>] & [NA or (Letters)] & [NA or (Numbers)] & [NA or (SpecialCharacters)]
- CheckPasswordStrength [<<Password>>]
- GenerateUsername      [<<Quantity>>]
- Matrix
- TimeToLoadUrl         [<<Url>>]
- CheckInternet
- CheckInternetSpeed
```

## Appearance

```plain
__   ___         ___                                    _  ___                      _               __
\ \ | _ \ _  _  / __| ___  _ __   _ __   __ _  _ _   __| || __|__ __ ___  __  _  _ | |_  ___  _ _  / /
 > >|  _/| || || (__ / _ \| '  \ | '  \ / _` || ' \ / _` || _| \ \ // -_)/ _|| || ||  _|/ _ \| '_|< <
/_/ |_|   \_, | \___|\___/|_|_|_||_|_|_|\__,_||_||_|\__,_||___|/_\_\\___|\__| \_,_| \__|\___/|_|   \_\
          |__/

Welcome to PyCommandExecutor, User 100!

Enter "Commands?" for commands, "Exit Imm" to exit.
Username: "User 100"
Date: 2025/06/27
Time: 12:02:36 AM

[ YYYY/MM/DD HH:MM:SS XM ] $ █
```

## Installation

```bash
pkg update && pkg upgrade
pkg install git python
git clone https://github.com/AnonymousUser12345-droid/PyCommandExecutor
cd PyCommandExecutor
pip install -r requirements.txt
python Main.py
```

## Dependencies

- [password-strength](https://pypi.org/project/password-strength/)
- [requests](https://pypi.org/project/requests/)
- [simpleeval](https://pypi.org/project/simpleeval/)
- [speedtest-cli](https://pypi.org/project/speedtest-cli/)
- [zxcvbn](https://pypi.org/project/zxcvbn/)
