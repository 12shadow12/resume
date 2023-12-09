# resume
My resume

%-------------------------
% Resume in Latex
% Author : Rich Bui
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    \textbf{\Huge \scshape Rich Bui} \\ \vspace{1pt}
    \small 714-360-4381 $|$ \href{mailto:rbui12345@gmail.com}{\underline{rbui12345@gmail.com}} $|$ 
    \href{https://www.linkedin.com/in/rich-bui-18595524b/}{\underline{linkedin/in/rich-bui}} $|$
    \href{https://github.com/12shadow12}{\underline{github.com/12shadow12}}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {California State Fullerton University}{Fullerton, CA}
      {Bachelor's in Computer Science}{January 2021 -- December 2023}
    \resumeSubheading
      {Orange Coast College}{Costa Mesa, CA}
      {Associate's in Computer Science}{Sept. 2016 -- May 2021}
  \resumeSubHeadingListEnd


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Face Detection} $|$ \emph{Python, OpenCV, Tensorflow, Matplotlib, NumPy}}{December 2023}
          \resumeItemListStart
            \resumeItem{Developed a real-time face-detection application utilizing TensorFlow and OpenCV, showcasing advanced proficiency in computer vision.} 
            \resumeItem{Implemented augmentation pipeline to enhance generalization of data, contributing to the robustness of the model and ensuring superior performance across diverse scenarios.}
            \resumeItem{Leveraged expertise in data visualization to create insightful representations of image data, effectively communicating key metrics and performance indicators to stakeholders.}
            \resumeItem{Employed the powerful VGG16 model to successfully train a custom dataset comprising over 8,000 images, demonstrating a comprehensive understanding of neural architectures.}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Tuffy AI-Assistant} $|$ \emph{Python, Tkinter, Weather API, JokesOne API, Git, HTML/CSS}}{November 2022}
          \resumeItemListStart
            \resumeItem{Developed an interactive voice recognition AI assistant geared towards enhancing students' study experiences.}
            \resumeItem{Engineered modern functionalities, including speech detection, homework reminders, live weather forecasting, personalized user greetings, and a touch of humor through joke integration.}
            \resumeItem{Demonstrated effective leadership by organizing and facilitating regular meetings, guiding teammates, and actively participating in debugging sessions. Initiated and collaborated with a dynamic team of 4 to ensure seamless and on-time project development.}
            \resumeItem{Collaborated closely with team members to suggest innovative features, contributing to the continuous improvement of the AI assistant. Played a pivotal role in deploying the final product, ensuring its successful integration into the user interface and overall website functionality.}
          \resumeItemListEnd
          \resumeProjectHeading
          {\textbf{Lexer for Programming Language Syntax Analysis} $|$ \emph{C, Lex}}{September 2022}
          \resumeItemListStart
            \resumeItem{Designed and implemented a lexer utilizing Flex to analyze strings of data in a programming language context. The program effectively tokenizes and categorizes elements within the input source code, providing insights into the syntactical structure.}
            \resumeItem{Constructed new rules for tokenizing and parsing diverse data sets, enabling the conversion of multiple high-level inputs into a structured sequence of tokens.}
            \resumeItem{Implemented robust handling of keywords, identifiers, string literals, separators, operators, integers, real numbers, and punctuation in the source code.}
            \resumeItem{Created error handling mechanisms, identifying and flagging invalid characters within the input.}
          \resumeItemListEnd
          \resumeProjectHeading
            {\textbf{Job Hunter Website (Full Stack)} $|$ \emph{PHP, HTML/CSS, MySQL, Git}}{May 2022}
          \resumeItemListStart
            \resumeItem{Developed a dynamic and user-friendly job log-in website to streamline the job application process. This project showcases my proficiency in full-stack web development, incorporating robust user authentication, responsive design, and efficient database management.}
            \resumeItem{Worked with a team of 3 and implemented database management to organize and store user data and job applications efficiently.}
            \resumeItem{Implemented secure user authentication features, enabling users to create accounts, log in securely, and manage their job applications.}
         \resumeItemListEnd
    \resumeSubHeadingListEnd



%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: Java, Python, C/C++, SQL, JavaScript, HTML/CSS} \\
     \textbf{Frameworks}{: React, Node.js, Flask, JUnit, WordPress, Material-UI, FastAPI} \\
     \textbf{Developer Tools}{: Git, Docker, Heroku, Google Cloud Platform, VS Code, Visual Studio, PyCharm, IntelliJ, Eclipse} \\
     \textbf{Libraries}{: pandas, NumPy, Matplotlib, OpenCV, Tensorflow, Tkinter}
    }}
 \end{itemize}


%-------------------------------------------
\end{document}
