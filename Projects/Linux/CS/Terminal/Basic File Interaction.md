
| rm           |                                           |
| ------------ | ----------------------------------------- |
| rm *file*... | deletes file                              |
| rm -r        | recursive delete (needed for directories) |
| rm -i        | interactive (asks for confirmation)       |
| rm -v        | verbose                                   |

| mv                  |                                                                    |
| ------------------- | ------------------------------------------------------------------ |
| mv *file1* *file2*  | moves file1 into file2 (creates file2 if missing) **Also renames** |
| mv *files*... *dir* | moves multiple files into directory                                |
| mv -r               | recursive (needed for directories)                                 |
| mv -i               | interactive                                                        |
| mv -u               | update (only new or newer file versions)                           |
| mv -v               | verbose                                                            |

| cp                  |                                                                     |
| ------------------- | ------------------------------------------------------------------- |
| cp *file1* *file2*  | copies file1 into file2 (creates file2 if missing) **Also renames** |
| cp *files*... *dir* | copies multiple files into directory                                |
| cp -r               | recursive (needed for directories)                                  |
| cp -i               | interactive                                                         |
| cp -u               | update (only new or newer file versions)                            |
| cp -v               | verbose                                                             |

| mkdir                |                  |
| -------------------- | ---------------- |
| mkdir *directory*... | create directory |

| links                 |                                 |
| --------------------- | ------------------------------- |
| ln *file* *link-file* | create hard link                |
| ln -s                 | create symbolic link (sym-link) |

| wildcards     |                                            |
| ------------- | ------------------------------------------ |
| .             | current dir <br>                           |
| ..            | previous directory                         |
| ../../        | previous previous directory                |
| *             | all characters (hidden files not included) |
| [characters]  | any of characters                          |
| [!characters] | any not characters                         |
| [ [:class:] ] | any of class                               |
| ?             | any single character                       |

| classes |                    |
| ------- | ------------------ |
| alnum   | alphabet + numeric |
| alpa    | alphabet           |
| digit   | numeric            |
| lower   | lower case         |
| upper   | upper case         |
