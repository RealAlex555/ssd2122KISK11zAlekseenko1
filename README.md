# ssd2122KISK11zAlekseenko1
Tasks:
1. Each programming task requires using at least one new pattern.
2. Code should be well commented (method descriptions, hard reading and big
code…).
3. There should not be dead code.
4. All entities should have meaningful names.
Tool requirements
1. Command line with input parameters
a. -sf, --seqfile - SF location
b. -s, --sequence - sequence formula when file not provided
c. -n, --number - sequence elements quantity to generate
d. -h, --help - user help
e. -v, --version - tool version
Note: If Both parameters are present (-sf, --seqfile and -s, --sequence) then new SF
should be generated.
2. Can load file with sequence description from Table 1. Tasks by students
3. Can generate sequence into .csv file.
Required steps for all tasks except task# 1,4:
1. Add/modify UTs where applicable.
2. Create/Modify the ci script to build, test and run project.
3. Commit changes to feature/develop/<task number>.
4. Update README with details:
∙ how to build project;
∙ how to run project;
∙ Version number.
5. Create GIT TAG:
<PROJECT NAME>_<task number>_<VERSION>_ww<YYWWD>
∙ YY – current year;
∙ WW – work week;
∙ D – current day number of weak.
6. Create pull request with name <task number> and submit author as reviewer.
7. After the reviewer approved – merge into the develop branch.
Acceptance criteria:
Project in the develop branch.
Task 1. Initiate GIT repository (BEF):
1. Create a github repo with the name “ssd<YY1YY2><group><student's
name><student's number>”, main branch develop.
YY1 – Start studding year
YY2 – End studding year
For example: 2019-2020 -> 1920
Full example ssd2122ki47spitzeras03
2. Add access for the author.
3. Create a branch feature/develop/<task number>. For example
feature/develop/task1.
4. Create README file with:
a. details about repo;
b. task details;
c. student number.
5. Create GIT TAG: <PROJECT NAME>_<VERSION>_WW<YYWWD>
∙ YY – current year;
∙ WW – work week;
∙ D – current day number of weak.
6. Create pull request with name task1 and submit author as reviewer.
7. After the reviewer approved – merge request into develop branch.
Acceptance criteria:
The created repo link with the “develop” as default branch and README.ML file.
Task 2. Create a block-scheme and sequence (BEF):
1. Create a block-scheme of algorithms.
2. Create a class diagram.
3. Create an architecture scheme.
4. Create a flow diagram.
5. Create SF
6. Required steps.
Task 3. Load/Generate SF (BEF):
1. Implement SF load and parse from -sf, --seqfile.
2. Generate SF if present -sf, --seqfile and -s, --sequence parameters.
3. The tool should show the loaded sequence and elements quantity.
4. Required steps.
Task 4. Save sequence (BEF):
1. Implement sequence generation.
2. Implement saving.
3. Required steps
