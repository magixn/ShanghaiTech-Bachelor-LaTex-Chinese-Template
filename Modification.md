# Error

## ucasthesis.cls

renewcommand{\CJKunderlinecolor}->newcommand{\CJKunderlinecolor}
renewcommand{\uline}->newcommand{\uline}

## artratex.sty(_2, _3)

"../Img/ShanghaiTech_Logo.png"->"./Img/ShanghaiTech_Logo.png"

# Warning

## Thesis.tex

all "Style/*"->"*"

# Feature

## Biblio

update to gbt7714-2015

## ucasthesis.cls

\newcommand{\keywords}[1]{%
    \vspace{\baselineskip}
    \noindent {**\sffamily** \ucas@label@keywords} #1}

\setlength{\headheight}{15pt}

## artratex.sty(_2, _3)

gbt7714-unsrt->gbt7714-numerical

gpt7714-plain->gbt7714-author-year

urlcolor=red->black

comment \captionsetup[table][bi-first]&[bi-second] for longtable error

# Author

magixn