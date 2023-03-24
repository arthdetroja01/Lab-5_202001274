# Lab-5_202001274

## Name: Arth Detroja
## Student ID: 202001274
## IT314: Software Engineering

## Lab: 05 Static Analysis

### Theory

**Static Analysis:**
_Static analysis is a method of examining the source code of a software program without
executing it. Static analysis can help detect errors, bugs, vulnerabilities, and other quality issues
in the code. Static analysis tools can perform various tasks such as checking syntax, style,
logic, data flow, control flow, and security. Static analysis can improve the reliability,
performance, and maintainability of software by identifying and correcting defects early in the
development process._

**Static Analysis Tools:**
_Static analysis tools are software tools that analyze the source code of a program without
executing it. They can help developers find and fix errors, bugs, vulnerabilities, code smells, and
other quality issues in their code. Static analysis tools can also measure various metrics of the
code, such as complexity, readability, maintainability, test coverage, and documentation. Static
analysis tools can be integrated into the development process as part of the code editor, the
version control system, or the continuous integration pipeline. Some examples of static analysis
tools are SonarQube, PMD, ESLint, and Pylint._

### Link of github repository taken: https://github.com/jazzband/website.git

### Tool used for Static Analysis: Pylint

#### Task 1: Analyzing error in the file db.py in: https://github.com/jazzband/website/tree/main/jazzband

![image](https://user-images.githubusercontent.com/84059984/227477533-0547f139-e851-4d4b-bbf3-8818819cb356.png)


### Error Analysis:

* C0114: Missing module docstring (missing-module-docstring)
* E0401: Unable to import 'flask_redis' (import-error)
* E0401: Unable to import 'walrus' (import-error)
* E0402: Attempted relative import beyond top-level package (relative-beyond-top-level)
* C0115: Missing class docstring (missing-class-docstring)
* C0116: Missing function or method docstring (missing-function-docstring)
* R1705: Unnecessary "else" after "return" (no-else-return)
* C0116: Missing function or method docstring (missing-function-docstring)
* C0116: Missing function or method docstring (missing-function-docstring)
* C0115: Missing class docstring (missing-class-docstring)
* W0611: Unused deque imported from collections (unused-import)
* W0611: Unused contextmanager imported from contextlib (unused-import)
* W0611: Unused Rollback imported from exceptions (unused-import)


#### Task 2: Analyzing errors in the file config.py in: https://github.com/jazzband/website/tree/main/jazzband

![image](https://user-images.githubusercontent.com/84059984/227478255-55938633-11e0-4ec2-bb11-9f6866f79a3b.png)

### Error Analysis

* C0114: Missing module docstring (missing-module-docstring)
* E0401: Unable to import 'decouple' (import-error)
* E0401: Unable to import 'markdown.extensions.toc' (import-error)
* E0401: Unable to import 'markdown.extensions.wikilinks' (import-error)
* E0402: Attempted relative import beyond top-level package (relative-beyond-top-level)

#### Task 3: Analyzing error in the file mixins.py in: https://github.com/jazzband/website/tree/main/jazzband

![image](https://user-images.githubusercontent.com/84059984/227478705-06586e8f-55dc-4269-bbf8-6f4b9a36e97e.png)

### Error Analysis:

* C0114: Missing module docstring (missing-module-docstring)
* E0402: Attempted relative import beyond top-level package (relative-beyond-top-level)
* E0402: Attempted relative import beyond top-level package (relative-beyond-top-level)
* C0115: Missing class docstring (missing-class-docstring)
* C0116: Missing function or method docstring (missing-function-docstring)
* E1101: Class 'Syncable' has no '__table__' member (no-member)
* E1101: Class 'Syncable' has no 'update_or_create' member (no-member)
* R0903: Too few public methods (1/2) (too-few-public-methods)
* C0116: Missing function or method docstring (missing-function-docstring)
* W0613: Unused argument 'mapper' (unused-argument)
* W0613: Unused argument 'connection' (unused-argument)

#### Task 4: Analyzing error in the file test_login.py in: https://github.com/jazzband/tests

![image](https://user-images.githubusercontent.com/84059984/227480022-deb17722-078e-4b3e-8a20-d5afa1334ab6.png)

### Error Analysis:

* C0114: Missing module docstring (missing-module-docstring)
* C0116: Missing function or method docstring (missing-function-docstring)

#### Task 5: Analyzing error in the file env.py in: https://github.com/jazzband/migrations

![image](https://user-images.githubusercontent.com/84059984/227480650-6754a3ef-0627-4ba8-a100-f8542a745622.png)

* C0114: Missing module docstring (missing-module-docstring)
* E0401: Unable to import 'alembic' (import-error)
* W0621: Redefining name 'context' from outer scope (line 6) (redefined-outer-name)
* W0613: Unused argument 'context' (unused-argument)
* W0613: Unused argument 'revision' (unused-argument)
