# Introduction to Python for Chemists

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/niburk/IAC-MAS-Python-Hands-On/blob/main/IAC%20Hands%20on%20Python%20workshop.ipynb)

A hands-on, 60-minute introduction to Python for chemistry students with no prior programming experience. The course is an interactive Jupyter notebook with short explanations, runnable examples, small exercises with instant feedback, and a research-related final project.

## Contents

| Chapter | Topic |
|---|---|
| 0 | How a Jupyter notebook works |
| 1 | Variables and data types |
| 2 | Decisions with `if` |
| 3 | Lists and `for` loops |
| 4 | Functions |
| 5 | Packages (`datetime`, `matplotlib`) |
| 6 | Final project: furnace program calculator |

In the final project, everything comes together in a tool you can actually use in the lab: it calculates how long a furnace program with several heating ramps and holding times takes, tells you when your sample will be ready, warns you if the program ends at night or on a weekend, and plots the temperature profile.

## Getting started

**Option 1: Google Colab (recommended, no installation needed)**

1. Click the **Open in Colab** button above.
2. Run the setup cell at the top of the notebook.
3. To keep your changes, go to **File → Save a copy in Drive**. Changes are *not* saved back to this repository.

You need a Google account for Colab.

**Option 2: bwJupyter (no Google account needed)**

[bwJupyter](https://hub.bwjupyter.de) is a JupyterHub for teaching, run as a state service in Baden-Württemberg.

1. Go to [hub.bwjupyter.de](https://hub.bwjupyter.de) and click **Login with bwIDM**. Choose your university and log in with your university account.
2. In JupyterLab, click **Clone a Repository** on the left icon menu and paste this link:

   ```
   https://github.com/niburk/IAC-MAS-Python-Hands-On.git
   ```

3. Open the folder `REPO` in the file browser on the left and double-click `Python_Einfuehrung.ipynb`.

Your files are stored in your bwJupyter account, so your changes are kept between sessions.


## Tips

- Cells run in the order you click them, not in the order they appear on the page. If something behaves strangely: **Runtime → Restart session**, then run all cells from the top.
- Cells with `___` will raise an error until you fill them in. That's intended.
- Error messages are best read from the bottom up: the last line tells you what went wrong.
