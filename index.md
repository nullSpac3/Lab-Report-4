Commands will styled as inline code, while the keys pressed will be shown in angled brackets.

* `ssh cs15lsp23rp@ieng6.ucsd.edu` -> `<enter>`
    * Logs onto a remote server `ieng6`

![Image](sc1.png)

<br>

* `git clone` -> `Ctrl-V` -> `git clone https://github.com/nullSpac3/lab7.git` -> `<enter>`
     * Clones my fork of the lab7 repository from my github account

![Image](sc2.png)

<br>

* `cd lab7` -> `<enter>` -> `bash test.sh` -> `<enter>`
     * Switches to lab7 directory, then runs the bash script file `test.sh`

![Image](sc3.png)

<br>

* `vim` -> `<space>` -> `L` -> `<tab>` -> `vim ListExamples` -> `vim ListExamples.java` -> `<enter>`
     * Opens `ListExamples.java` in a vim editor in the bash terminal
     
![Image](sc5.png)
![Image](sc4.png)

<br>

* `<left>` -> `<x>` -> `<a>` -> `<2>` -> `<esc>` -> `:wq` -> `<enter>`
     * Edits file as required, then saves the file and closes the vim editor

![Image](sc6.png)

<br>

* `<up>` -> `<enter>`
     *  Goes through command history to run `bash test.sh`

![Image](sc7.png)

<br>

* `git add ListExamples.java` -> `<enter>` 
     * Adds modified files to be committed

* `git commit -m "fixed"` -> `<enter>`
     * Commits modified files
<br>

![Image](sc9.png)

* `git push origin main` -> `<enter>` 
     * Pushes committed changes to my `lab7` remote repository's main branch
