- 👋 Hi, I’m @patrcoff
- 👀 I’m interested in open source software, IT tools, and am currently pivoting from IT Support to DevOps so anything in that realm is of great interest to me.
- 🌱 I’m currently learning python, sql, software development practices, linux administration.
- 💞️ I’m looking to collaborate on: ISECAPIPY*, and any public projects (mainly in Python) who would be willing to have me work with them. I am new to contributing and am keen to learn more about best practices for working on Open Source.
- 📫 How to reach me - for now, the best way would be to reach out on LinkedIn, if you don't already have another contact method for me. https://www.linkedin.com/in/patrick-coffey-b7a748b0

<br></br>
<br></br>

<h1>Projects</h1>

<br></br>

<h2>ISECAPIPY</h2>

I am developing a Python package which is a wrapper for the Ivanti Security Controls Console REST API. This is my first 'real world' project so to speak, and though I am proud of how the project is going, I'm sure there are many improvements to be made in it. I was previously employed at Ivanti as a TSE supporting ISEC and it's due to my knowledge of this product that I have chosen to focus on this project at this point in my personal development. However, it should be noted that the project is fully Open Source and is based fully on publically available information about the ISEC product and its REST API. It is in no way affiliated with Ivanti itself and receives no support or funding from them. I would be keen to collaborate on this project with any actual customers of ISEC in order to get insights to desired functionality and real-world use cases.

<br></br>

<h2>TaskQueue / Clippy2000</h2>

I began developing clippy2000 around the end of last year when I was beginning to find momentum with my learning of Python. I have since grown further however and intend to revisit this project soon with a complete overhaul, separating TaskQueue into its own discrete package and completing Clippy2000 (working title) as an application based on the TaskQueue module. The gist of the project(s) is an API for defining tasks (functions which meet a defined specification) which can then be ordered by the end user of a piece of software, optionally taking a limited range of datatypes as input along with similarly limited arguments for directing behaviour of each 'task'. An example usage of this is simple text processing sequences which takes a blob of text as input, processes it based on pre-defined functions (tasks) and returns the processed text. I.E. you might take in a list of email addresses in a given format (say ; separated) which has been copied from a source and process it using a pre-defined sequence of tasks which changes the format of the list (say csv, email per newline etc) as appropriate for some other application which requires said format. The idea is to assist repetative copy/paste tasks in the users workflows which are common enought to be annoying, but not common enough to warrant the time to develop a single standalone app or cli to resolve/automtate, or where the user does not posses strong scripting/coding skills. This is where clippy2000 comes in - it is a task menu application which allows the creationg of tast sequences (based on available pre-defined 'tasks') and a simply drop down menu to run a given sequence, which will modify the contents of the clipboard in place; turning workflows normally requiring multiple copy/paste steps into a coupld of mouse clicks. I shall provide further details on this soon.



<!---
patrcoff/patrcoff is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
