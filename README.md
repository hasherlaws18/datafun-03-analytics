# datafun-03-analytics

For Windows PowerShell (change if using Mac/Linux). 
Keep these notes in every project README.md.

```powershell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt
```

## CheatSheet: Commands to Run Python Scripts

Remember to activate your .venv (and install packages if they haven't been installed yet) before running files.
Verify that all external packages imported into a file are included in requirements.txt (and have NOT been commented out).

```shell
py demo_script.py
py do_stats.py
py draw_chart.py
py greet_user.py
```