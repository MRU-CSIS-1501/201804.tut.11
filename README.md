# Tut-11

## WHAT WE'RE DOING

- Getting a quick walkthrough of FileZilla.
- Coding on INS involving file paths and reading files.

---

## FILEZILLA WALKTHROUGH

JP will show you FileZilla, how to use it, and how to export/import the settings in the labs so you can use FileZilla on your own computer if you wish.

## FILE PATHS AND READING FILES

Copy `/users/library/csis/comp1501/assignments/file.practice` over to your home directory.

Here's the structure inside:

<pre>
.
├── 0301-cave-dwellers.txt
├── 05
│   ├── 0511-mitchell.txt
│   └── 08
│       └── 0820-space-mutiny.txt
├── 12
└── src
    ├── 0425-manos:-the-hands-of-fate.txt
    └── 09
        ├── 03
        │   └── 0903-the-pumaman.txt
        └── 0910-the-final-sacrifice.txt

</pre>

Create `Mst3kQuoter.java` inside the `src` directory.

Edit that source file so that:

- in the `main`, it creates one of the Mst3kQuoter objects and then calls `run` on that object.
- in the `run`, you should:
  - prompt the user for a file path
  - if that file exists, echo out the file contents to the screen
  - if that file does not exist, let the user know it does not exist (you will use a try/catch/finally)

## YOUR SKILL DRILLS

The following drill is due this Thursday (Nov. 29):

- tut-11: filtered text file
