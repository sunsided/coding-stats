# Exploratory Analysis of my Coding Stats

A simple exploratory analysis of my coding stats. I use WakaTime since late 2016 to track my
use of programming languages and periodically fetch the daily stats from the WakaTime API. Since
recording only started in 2016, large chunks of C#, C/C++, Matlab and other languages are missing.

In this repo, I ran some trivial analytics from those JSON files. If for whatever reason you are
interested, the `redacted.csv` contains the language-specific information. I excluded other source
data from this repo since it can hypothetically contain mildly sensitive details such as project
and machine names.

I mainly wanted to see how my Rust journey went compared to other languages and at the very least
it's interesting to say that within the last two-ish years as of writing this, I spent as much time
writing Rust code as I spent time writing Python code since the recording started.

![](images/language_development.png)

The C# curve is pretty linear, which is not surprising since I have been working in .NET focused
companies since 2008 and therefore use C# a lot during my work life. What is interesting, however
is that for the last three years I have not actively assumed the role of a software developer
and _still_ maintained a linear progression there.
