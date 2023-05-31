
## Table of content
Make one page for every content

1. Workpsace
2. Coding guidelines
3. Code snippets
4. My learnings
5. What to do next ?


### Workpsace
Since I work on windows for development , I am more comfortable in using VSCODE editor like anz other realistic code nowadays and for running odoo environment , I use Docker rather than installing odoo on my machine which is faster but not so trendy.

There are some vscode and docker relavant settings which I use for development with odoo that I will elaborate here.

1. tasks.json
2. settings.json
3. docker-compose.yml (explain about entrypoint)
4.  

### Coding guidelines 
Here I will explain about coding guidelines being followed 

#### Python guidelines
1. Blackformatting with 79 line of characters per line ```ctrl + shift + i```
2. Add keywords for every attribute of the odoo field
3. Add commas between attribute of the odoo field
4. Add docstrings for every method
5. Add constants in one file and then import them before using them 
6. Alphabetically sort odo fields
7. Remove unused imports (there should be a shortcut to do this in vscode)
8. Take care of Code cognitivity,methods should not be too long
9. Write methods which are relevant to a model only within that model itself
10. Per python file there should be only one class or model
11. Name of the python file and the class or the model name should be the same 


#### git guidelines
Following are some of the git guidelines as per the odoo coding guidelines

Commit message : ```[commit_tag][branch_name] what was done```


| Tag   | Description |
| ------ | --- |
| FIX   | for bug fixes: mostly used in stable version but also valid if you are fixing a recent bug in development version;  |
| REF  | for refactoring: when a feature is heavily rewritten;  |
| ADD  | for adding new modules;  |
| REM  | for removing resources: removing dead code, removing views, removing modules, …;  |
| REV  | for reverting commits: if a commit causes issues or is not wanted reverting it is done using this tag;  |
| MOV  | for moving files: use git move and do not change content of moved file otherwise Git may loose track and history of the file; also used when moving code from one file to another;  |
| REL  | for release commits: new major or minor stable versions;  |
| IMP  | for improvements: most of the changes done in development version are incremental improvements not related to another tag;  |
| I18N  | for changes in translation files;  |

#### manifest.py guidelines
1. Blackformatting with 79 line of characters per line ```ctrl + shift + i```

#### XML guidelines
1. Shortcut to format the xml file  ```ctrl + shift + i```
2. Space at the end of every line



#### What to do next ?
In idle time work on resolving open-source issues of odoo 