# pm21-fire-horse

Course material for **PM-21: Python für die Biowissenschaften** (Python for the
Life Sciences), Winter Semester 2026/27 (year of the fire horse), Faculty of
Biology, University of Freiburg.

- Responsible for the module: Prof. Dr. Andrew Straw (he/him)
- Tutor: Dr. Michael Harrap (she/her)

Links:

- Course repository (this one): https://github.com/strawlab/pm21-fire-horse
- [ILIAS](https://ilias.uni-freiburg.de/goto.php/crs/4388458): exercise
  submission, forum, announcements
- [HISinOne](https://campus.uni-freiburg.de:443/qisserver/pages/startFlow.xhtml?_flowId=detailView-flow&unitId=45291&periodId=4788&navigationPosition=hisinoneLehrorganisation,examEventOverviewOwn):
  dates and rooms

No prior programming experience is assumed.

## Getting started

You will do this together with Dr. Harrap in the first Monday session. If
something does not work, bring your laptop anyway and we will help. You can
also use a PC in the Computerpool.

### 1. Install Sunbeam (Python and Jupyter Lab)

[Sunbeam](https://github.com/strawlab/sunbeam) installs and runs Python and
Jupyter Lab on your own computer.

1. Download the latest version of Sunbeam from
   [releases](https://github.com/strawlab/sunbeam/releases) and install it as a
   normal app. On macOS, there are a couple of extra steps because the app is
   not signed: see
   [here](https://github.com/strawlab/sunbeam#macos-allowing-an-unsigned-app-to-run).
2. Start Sunbeam and click "Launch Jupyter Lab". The first launch may take
   several minutes while Python and the required packages are downloaded. A
   browser window then opens with Jupyter Lab running on your computer.

**Alternative: the course JupyterHub server.** If you cannot install Sunbeam,
or it does not work on your computer, you can use Jupyter Lab in your browser
on the course server instead:
https://strawlab-rp2.zoologie.uni-freiburg.de/hub/ . Log in with the username
and password from the email of 23 October 2026. Your files are then stored on
the server, not on your computer, so make your course folder (step 2) there,
in Jupyter Lab's file browser. Use Jupyter Lab's upload button to
add course files to it, and download your finished notebook (right-click it in
the file browser, then "Download") before you upload it to ILIAS.

### 2. Make a folder for the course

Make a folder for the course on your computer, for example `Documents/PM-21`.
In Sunbeam, set the working directory to this folder before you click "Launch
Jupyter Lab". Jupyter Lab's file browser then shows the files in this folder.

### 3. Download the course material from GitHub

All course material is on the GitHub website at
https://github.com/strawlab/pm21-fire-horse. You do not need a GitHub account.

- **View:** click through the folders. GitHub shows notebooks (`.ipynb` files)
  directly in your browser, so you can read them there.
- **Download one file:** open the file on GitHub and click the "Download raw
  file" button (the arrow pointing down, at the top right of the file). Your
  browser saves it in your Downloads folder.
- **Download everything:** on the main page, click the green "<> Code" button,
  then "Download ZIP". Unzip it and copy the folders you need.

Move the downloaded files into your course folder. Keep all files of one week
together in one folder (for example `PM-21/exercise-01/`), because notebooks
often load data files or images from their own folder. Do not rename the
exercise notebooks. Be careful not to overwrite files you have already worked
on.

Later in the course (week 6), after you have learned to use the command line,
you will learn git, which can download the course material for you.

### 4. Submit your exercise

Upload your completed `.ipynb` file(s) to the exercise's folder in
[ILIAS](https://ilias.uni-freiburg.de/goto.php/crs/4388458) by Sunday 23:55. Do
not change the file names.

## How the course runs


### The format in one paragraph

This course is *flipped*. You learn the basic material for each week **before**
Friday by working through the week's **lessons**. **Monday afternoon** is
your preparation time for Friday: Dr. Harrap is there to help you work through
the lessons, start the exercise, and find the questions you want to bring to
Friday. **Friday
morning** with Prof. Straw is not a lecture. It is a discussion: we work on what
you found difficult, look at different solutions, and go deeper. The weekly
exercise is due on Sunday, after the discussion. To pass, you must attend
regularly and complete at least 12 of the 14 exercises. "Complete" includes
being able to explain your own solution when asked.

Each week has **lessons** (Jupyter notebooks that you learn from before Friday)
and one **exercise** (a Jupyter notebook that you complete and submit).

### Weekly rhythm

| When | What | Who |
| ---- | ---- | --- |
| Friday after class (week N−1) | Week N materials and exercise N are released in the course repository on GitHub | — |
| **Monday 14:15–18:00**, Computerpool (Biologie II/III)* (week N) | Preparation session: work through week N lessons, start exercise N, collect questions for Friday. Besprechungen of exercise N−1 | Dr. Harrap |
| Thursday 18:00 (week N) | Post your questions about week N in the ILIAS forum (optional, but it shapes Friday) | You |
| **Friday 10:15–11:45**, SR 1048 (Biologie I, Zoologie) (week N) | Discussion session on week N | Prof. Straw |
| Friday 11:45–12:00 (week N) | Individual Besprechungen in German, and retries (only for students who have one scheduled) | Prof. Straw |
| **Sunday 23:55** (week N) | Exercise N due: upload to ILIAS | You |

\* Exceptions: on **14 December** and **25 January** the Monday session is in
room R -100 (UG), Universitätsrechenzentrum.

**Course material:** download the lessons and exercises from this course
repository on GitHub (see [Getting started](#getting-started)). From week 6
on, you can also use git for this. **Submission:**
upload your completed exercise notebook(s) to the exercise's folder in
[ILIAS](https://ilias.uni-freiburg.de/goto.php/crs/4388458). Do not change the
file names.

You will need about 7–8 hours of self-study per week outside the sessions.

The teaching language is English. You may always ask questions in German and
submit exercises in German.

### What you need to pass

The module is pass/fail (no grade). There are two requirements (Studienleistungen):

1. **Regular attendance** at the sessions, and
2. **Completion and submission of at least 80% of the programming exercises**,
   which means at least **12 of the 14** exercises.

#### 1. Attendance

- The Monday sessions (14:15–18:00) and the Friday sessions (10:15–11:45)
  together form one course (Übung). Attendance is counted over the total
  session time of the semester. **A Monday session counts twice as much as a
  Friday session.**
- You may miss **up to 15%** of the session time, which is the equivalent of
  **6¾ Friday sessions**, for any reason without telling us. For example:
  - three Monday sessions: OK
  - two Monday and two Friday sessions: OK
  - one Monday and four Friday sessions: OK
  - three Monday sessions and one Friday session: **too much**
  - seven Friday sessions: **too much**
- Arriving late or leaving early counts as partial absence, except when you
  check out on Monday (see below).
- Attendance is recorded with a sign-in list at every session. It is your
  responsibility to sign in.
- If you miss **between 15% and 30%** for an important reason (e.g. illness), you
  can apply to Prof. Straw for a substitute task (*Ersatzleistung*). Apply by
  e-mail with evidence (e.g. a medical certificate) within one week of the last
  missed session. The substitute task is a short individual meeting with Prof.
  Straw on the material of the missed sessions, plus the lessons for those
  weeks.
- If you miss **more than 30%**, or more than 15% without an approved
  substitute task, you have not attended regularly. You then have to take the
  course again in a later year.

##### Leaving a Monday session early: check-out

Monday is for getting ready for Friday. Once you are ready, you may leave
**from 16:15 onwards without losing attendance time**, after checking out with
Dr. Harrap. You are ready when:

1. your Besprechung is done, if you were drawn that day;
2. you have worked through the week's lessons and can answer one or two of
   their "check yourself" questions; and
3. you have started the exercise and can say what you plan to do, or where you
   are stuck. Being stuck is fine: that is a question to bring to Friday.

You do **not** need to have finished the exercise. It is due on Sunday, after
the Friday discussion.

If Dr. Harrap is satisfied, she signs you out and the whole session counts as
attended. If not, you stay and keep working, and you can ask to check out again
later in the session. Good uses of the time after 16:15 are the optional
extension task for the week, or pairing up with a student who is stuck:
explaining your code to someone else is the best preparation for a Besprechung.

The check-out is informal. It has no effect on whether an exercise counts; only
the Besprechung does.

#### 2. Exercises

There is one exercise per week (14 in total; see the schedule below). An
exercise counts as **completed** (*bearbeitet*) only if all three of the
following are true:

1. **Uploaded to ILIAS on time**, by Sunday 23:55 of its week. Late submissions
   are not counted. The 80% rule already allows you to miss two exercises for
   whatever reason.
2. **A serious attempt at every task.** Your solution does not have to be
   perfect or fully correct.
3. **Your own work that you can explain.** If you are selected for a
   Besprechung (see below), you must be able to explain your submission.

#### The Besprechung (discussion of your exercise)

- **Who and when:** Every Monday, about 7 students are drawn at random for a
  Besprechung of the exercise they submitted the day before. Anyone who has not
  been drawn for three weeks in a row is added automatically. You will
  therefore be drawn several times during the semester, and you can be drawn
  in any week.
- **How long:** about 5–10 minutes, one-to-one, with your submitted notebook
  open on screen.
- **What we ask:** for example, walk us through what a part of your code does,
  predict what happens if we change something small, explain an error message,
  or make a small change live. We are checking that you understand your own
  solution, not that it is perfect.
- **Allowed:** your own submitted notebook and the course materials. **Not
  allowed:** AI tools or help from others during the Besprechung.
- **Language:** Dr. Harrap holds Besprechungen in English. If you prefer to
  explain in German, write "Besprechung auf Deutsch" in the first cell of your
  notebook. Prof. Straw will then hold your Besprechung on Friday 11:45–12:00,
  or at an agreed time.
- **Outcome:** "explained", and the exercise counts; or "not yet". After a "not
  yet", you get **one retry with Prof. Straw**, usually Friday 11:45–12:00 the
  same week. If you can explain it then, the exercise counts. If not, it does
  not count. Only Prof. Straw decides that an exercise does not count.
- **If you are absent** on the Monday you are drawn, your Besprechung moves to
  the retry slot.

#### AI tools and working together

- **AI assistants are allowed** for the exercises, as are discussing exercises
  with other students, the tutor, and web searches. AI-assisted programming is a
  topic of the course (week 6).
- **Declare what you used.** Start every notebook with a short Markdown cell
  saying which tools or people helped you and for what (e.g. "Used ChatGPT to
  explain the error in task 3"). Declaring AI use never counts against you.
- **You must understand what you submit.** This is what the Besprechung checks.
  If you submit code you cannot explain, the exercise simply does not count.
- Submitting another student's work as your own can be treated as cheating
  (*Täuschung*).

#### Nachteilsausgleich (compensation for disadvantages)

If a chronic illness or disability makes attendance or the Besprechungen harder
for you, talk to Prof. Straw early. Formal applications go to the
Prüfungsausschuss.

### Schedule

| Week | Monday | Friday | Topic | Exercise due (Sun 23:55) |
| ---- | ------ | ------ | ----- | ------------------------ |
| 1 | 19 Oct | 23 Oct | Course introduction, setup (Sunbeam, Python, Jupyter Lab, ILIAS), Python basics | Ex 1: 25 Oct |
| 2 | 26 Oct | 30 Oct | Types, lists and indexing, first plots | Ex 2: 1 Nov |
| 3 | 2 Nov | 6 Nov | Slicing, decisions with `if`, `while` loops, user input | Ex 3: 8 Nov |
| 4 | 9 Nov | 13 Nov | `for` loops, strings, dictionaries | Ex 4: 15 Nov |
| 5 | 16 Nov | 20 Nov | The command line and SSH | Ex 5: 22 Nov |
| 6 | 23 Nov | 27 Nov | Programming with AI assistants; version control with git | Ex 6: 29 Nov |
| 7 | 30 Nov | 4 Dec | pandas, reading and writing data files, matplotlib | Ex 7: 6 Dec |
| 8 | 7 Dec | 11 Dec | NumPy and optimization | Ex 8: 13 Dec |
| 9 | 14 Dec* | 18 Dec | Image analysis | Ex 9: 20 Dec |
| 10 | 21 Dec | 8 Jan | Clustering and principal component analysis (spans the Christmas break) | Ex 10: 10 Jan |
| 11 | 11 Jan | 15 Jan | Online bioinformatics and web APIs | Ex 11: 17 Jan |
| 12 | 18 Jan | 22 Jan | Probability, simulation, and Bayes' theorem | Ex 12: 24 Jan |
| 13 | 25 Jan* | 29 Jan | Bayesian inference with MCMC; Kalman filters | Ex 13: 31 Jan |
| 14 | 1 Feb | 5 Feb | Deep learning and pretrained AI models | Ex 14: 7 Feb |
| 15 | 8 Feb | 12 Feb | Review and wrap-up; final retries | — |

Christmas break: no sessions on 25 Dec, 28 Dec, 1 Jan, 4 Jan.
\* Monday session in R -100 (UG), Universitätsrechenzentrum.

Week 1 is an exception: there is nothing to prepare. On Monday, Prof. Straw
introduces the course and its format, and Dr. Harrap gets everyone set up:
Python and Jupyter Lab on your laptop, downloading the course material from
GitHub, and uploading to ILIAS.

## Repository layout

```
lessons/
    week-01/         lessons for week 1 (learn from these before Friday)
    week-02/         ...
exercises/
    release/
        exercise-01/ the exercise for week 1 (work on this)
    source/
        exercise-01/ the solution, posted after the deadline
README.md            this file
pyproject.toml       the Python packages used in the course
```

## Useful resources

Python

- [The Python Tutor](https://pythontutor.com/): step through small programs
  and see what they do. Extremely highly recommended.
- [Ten simple rules for biologists learning to program](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005871)

AI assistants

- [openwebui.uni-freiburg.de](https://openwebui.uni-freiburg.de)
- [claude.ai](https://claude.ai)
- [ChatGPT](https://chatgpt.com)

## About this material

The course content (lessons, exercises and examples) was developed 
by Andrew Straw. AI assistants (especially Claude Opus 5.5) were
used to help restructure and reorganize the course, including individual
notebooks in both the lessons and the exercises.
