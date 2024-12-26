# portfolio

Bewcause only a **complete fool** trust's the word of a person without any concreate evidence, here is some stuff **I** have made.

This is the repository of my personal programming textbook and other material summaries, random design or programming experiments. Expect the unexpected. If you see the signature **TH** in the credits, that is me. :)

## Directory Outline ##

Here is a simple outline how the portfolio could be appified with automatic visualization.

1. repo root directory's sub-directory with a same name (basically **portfolio/portfolio**, with a simple text listing python script that shows all projects ordered by last modifications, lines of code counts and what else and it would a brief description from the local README.md files or something) ->
2. project directories (most likely grouped by the used tech stack, can contain multiple sub-projects sharing the same assets for experimenting purposes) ->
3. asset directories named after the technologies or the asset types (you want to avoid putting different stuff together to keep things simple, for example 'c' for .c and .h files) ->
4. possible sub-directories for keeping things looking simple and minimal

It is a bit unclear where stuff like tests and main procedures are stored, though the practices tend to vary wildly in a multi-language collections like this one. Also, there are some differences in how local scope works in them and how they handle parent and child directories. For example, Python does not expect you to run any code from the repo root drectory (read: you cannot access that root directory from the sub-directories) and that is why you have these strange, seeemingly redundant program-project/program-project structures. the first one is the repo root and the second one is the project root and apparently the repo seems to be isolated from what they Python app can see. In contrast, the C and C++ conventions seem to be about dumping all of the source files into the same directory and only separating the header files (.h/.hh/.hpp).

This outline is a subject to change. It is also an experiment to see how different kind of project assets can be stored toghether. Integration is a big thing these days, so there is no escaping the need to know how to store and organize things in the most intuitive and self-explanatory way possible.
