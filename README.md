This repo contains information related to our created code clone oracle. There are several main components to this repository.

1) Data
There are two main data components

- The source code code of Apache, Python, and PostgreSQL which were used in the experiment.
- The discover clones from the previous experiments using both humans, and the results from numerous existing clone detection tools.


2)Tool
- A tool for comparing the source code from Apache, Python and PostgreSQL is included in the repo. This will allow the user to create their own oracle should they desire.
- This tool will load two methods from the source code and allow the user to decide if two methods are clones, and if so, what type of clone.
- Instructions for running this tool may be found in the tool directory.