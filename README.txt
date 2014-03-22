This is an automated version for daily journal. Modified from codes on
http://tex.stackexchange.com/questions/68525/using-latex-to-keep-a-diary
and added CJK support. It assumes your directory to be of the form /Year/Month/Day.tex, formatted as e.g. 2012/Aug/24.tex, so the month is just the first three letters. The individual .tex files have only the requirement to have the first line as \mytitle{<The actual title here>}.

Compile note:
Must use xelatex, and install CJK packages (can be installed from the settings of miktex on windows) to support Chinese.