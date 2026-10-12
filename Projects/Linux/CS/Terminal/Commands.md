
| type           |                                                    |
| -------------- | -------------------------------------------------- |
| type *command* | output: shell builtin / alias / exec file location |

| which                |                            |
| -------------------- | -------------------------- |
| which *exec command* | all exec command locations |

| help                 |               |
| -------------------- | ------------- |
| help *shell builtin* | provides info |

| info           |                            |
| -------------- | -------------------------- |
| info *command* | wiki like page for command |

| --help                |                                |
| --------------------- | ------------------------------ |
| *exec command* --help | help equivalent for exec files |

| man                            |                                       |
| ------------------------------ | ------------------------------------- |
| man *command*                  | manual page for command (first entry) |
| man *section number* *command* | manual page for command in section    |

| alias                   |                                |
| ----------------------- | ------------------------------ |
| alias name='*command*'  | create temporary alias command |
| unalias *alias command* | remove temporary alias command |

| Command formating                   |                                     |
| ----------------------------------- | ----------------------------------- |
| command *options* *arguments*       |                                     |
| [*option*]                          | [] means optional                   |
| option1 \| option2                  | \| mutually exclusive items         |
| *command1*; *command2*; *command3*; | chain commands with ;               |
| *command* > *file*                  | write output to file (creates file) |
| *command* 2> *file*                 | write error to file                 |
| *command* &> *file*                 | write error & output to file        |
| command >> *file*                   | appends output to file              |
| { command; command; command; }      | groups commands                     |
| *command1* \| *command2*            | sends output as input               |

| cat        |                       |
| ---------- | --------------------- |
| cat *file* | outputs file contents |

| sort        |                     |
| ----------- | ------------------- |
| sort *text* | sorts lines of text |

| uniq        |                        |
| ----------- | ---------------------- |
| uniq *text* | filters out duplicates |

| grep        |                               |
| ----------- | ----------------------------- |
| grep *term* | outputs files containing term |

| wc             |                             |
| -------------- | --------------------------- |
| wc *file/text* | outputs lines, words, bytes |

| head & tail      |                    |
| ---------------- | ------------------ |
| head *file/text* | outputs top 10<br> |
| tail *file/text* | outputs bottom 10  |
| head -n *number* | outputs top number |

| tee              |                                                         |
| ---------------- | ------------------------------------------------------- |
| tee *files/text* | write to stdout and files (can save and pass on output) |

