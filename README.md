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

%----------HEADER----------
\begin{center}
    \textbf{\Huge \scshape Adarsh Raj} \\ \vspace{1pt}
    \small +91-9155023324 $|$ \href{mailto:adarshraj9155@gmail.com}{\underline{adarshraj9155@gmail.com}} $|$ 
    \href{https://linkedin.com}{\underline{linkedin.com}} $|$
    \href{https://github.com}{\underline{github.com}} \\
    \small Patna, Bihar
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Indian Institute of Technology Patna}{Patna, Bihar}
      {Bachelor of Technology in Mechanical Engineering (CPI: 8.06/10)}{2022 -- 2026 (Expected)}
    \resumeSubheading
      {ABR Foundation School}{Sasaram, Bihar}
      {CBSE Class XII (Percentage: 90.8\%)}{Apr 2019 -- July 2021}
    \resumeSubheading
      {DAV Public School}{Sasaram, Bihar}
      {CBSE Class X (Percentage: 95.4\%)}{March 2019}
  \resumeSubHeadingListEnd


%-----------SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: C++, Python, HTML/CSS, JavaScript, SQL} \\
     \textbf{Frameworks/Libraries}{: React.js, Express.js, Node.js, NumPy, Pandas, Mongoose} \\
     \textbf{Databases}{: MongoDB} \\
     \textbf{Relevant Coursework}{: Data Structures, Algorithms Analysis, Operating Systems, OOP, Artificial Intelligence, Data Analytics, Machine Learning.}
    }}
 \end{itemize}


%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Real Time Chat App} $|$ \emph{React.js, Node.js, WebSocket, HTML, CSS}}{April 2025}
          \resumeItemListStart
            \resumeItem{Developed a real-time chat system to facilitate instant and seamless communication between users using WebSocket technology.}
            \resumeItem{Implemented secure User Authentication and Authorization using JWT (JSON Web Tokens) to ensure protected access.}
            \resumeItem{Designed an interactive and highly responsive User Interface (UI) using ReactJS for an enhanced user experience.}
          \resumeItemListEnd

      \resumeProjectHeading
          {\textbf{\href{https://github.com/Adarshraj27/Employee-Management-Portal}{Employee Management System}} $|$ \emph{Node.js, Express.js, MongoDB}}{November 2024}
          \resumeItemListStart
            \resumeItem{Architected a RESTful API using Node.js and Express.js to facilitate seamless CRUD operations for managing employee records.}
            \resumeItem{Integrated MongoDB with Mongoose ODM to enforce robust data schemas, validation rules, and efficient data retrieval.}
            \resumeItem{Implemented advanced search capabilities allowing retrieval of employees by first name and specific ID lookup.}
            \resumeItem{Built a modular backend structure ensuring scalability, featuring specific routes for updates, deletions, and record creation.}
          \resumeItemListEnd
    \resumeSubHeadingListEnd


%-----------ACCOMPLISHMENTS-----------
\section{Accomplishments}
 \resumeItemListStart
    \resumeItem{Ranked among the \textbf{top 1 percent} in JEE Advanced 2022.}
    \resumeItem{Ranked in the \textbf{top 3 percentile} out of 0.9 million candidates in JEE Mains 2022.}
    \resumeItem{Graded in the \textbf{top 10\%} by academic performance in the Mechanical Engineering Department of IIT Patna.}
    \resumeItem{Solved \textbf{200+} coding questions on platforms like LeetCode and GeeksforGeeks.}
 \resumeItemListEnd


%-----------LEADERSHIP & EXTRACURRICULAR-----------
\section{Leadership \& Extracurricular}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Celesta Tech Fest}{IIT Patna}
      {Core Team Volunteer}{2024 -- Present}
      \resumeItemListStart
        \resumeItem{Participated in coding competitions and Robowar events during the fest.}
      \resumeItemListEnd

    \resumeSubheading
      {Training and Placement Cell (TPC)}{IIT Patna}
      {Volunteer}{November 2023}
      \resumeItemListStart
        \resumeItem{Assisted in coordinating placement activities and logistical support for recruiting companies.}
      \resumeItemListEnd

    \resumeSubheading
      {Yavanika Drama Club}{IIT Patna}
      {Member}{December 2022}
      \resumeItemListStart
        \resumeItem{Active participant in stage dramas and Nukkad Natak (street plays), contributing to cultural events.}
      \resumeItemListEnd

  \resumeSubHeadingListEnd

\end{document}
