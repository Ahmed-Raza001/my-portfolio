%-------------------------
% ATS-Friendly Resume - Ahmed Raza Harsoliya
% LaTeX Template
%-------------------------

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

\pagestyle{fancy}
\fancyhf{}
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

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-5pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-5pt}
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
\begin{center}
    \textbf{\Huge \scshape Ahmed Raza Harsoliya} \\ \vspace{1pt}
    \small Himatnagar, Gujarat, India \\
    \small \href{mailto:ahmadrazaharsoliya67@gmail.com}{ahmadrazaharsoliya67@gmail.com} $|$ 
    \href{https://www.linkedin.com/in/ahmed-raza-harsoliya-495b42352/}{linkedin.com/in/ahmed-razaharsoliya} $|$
    \href{https://github.com/Ahmed-Raza001}
    {GitHub.com/Ahmed-Raza001}
\end{center}

%-----------SUMMARY-----------
\section{Professional Summary}
\small{Skilled and creative web developer specializing in building responsive, user-friendly web applications. Proficient in modern web technologies with demonstrated experience across diverse projects from personal blogs to e-commerce platforms. Strong problem-solving abilities with a focus on writing clean, maintainable code and delivering scalable solutions.}

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Languages}{: HTML5, CSS3, Bootstrap, Tailwind, JavaScript, React.js, Node.js} \\
     \textbf{Frameworks \& Libraries}{: Node.js (learning), React (learning), Bootstrap, Tailwind CSS} \\
     \textbf{Tools \& Technologies}{: Git, GitHub, VS Code, REST APIs, Chrome DevTools} \\
     \textbf{Web Development}{: Responsive Design, Cross-browser Compatibility, Web Performance Optimization} \\
     \textbf{Soft Skills}{: Problem Solving, Debugging, Code Review, Team Collaboration}
    }}
 \end{itemize}

%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Online Bus Ticket Booking Web Application} $|$ \emph{HTML, CSS, Tailwind, JavaScript, React.js}}{2024 -- 2025}
          \resumeItemListStart
            \resumeItem{Designed and developed a modern bus ticket booking platform using React.js, JavaScript, and Tailwind CSS.}
            \resumeItem{Implemented features such as bus search, route details, seat selection, and responsive user interface.}
            \resumeItem{The project highlights skills in frontend development, reusable React components, responsive design, and interactive UI development.}
            \resumeItem{Optimized page load times by 40\% through code splitting and lazy loading techniques}
          \resumeItemListEnd
      \resumeProjectHeading
          {\textbf{Shopping Cart System} $|$ \emph{HTML5, CSS3, JavaScript, React, Git, GitHub}}{2025}
          \resumeItemListStart
            \resumeItem{Built an interactive shopping cart application using React.js for component-based development, JavaScript for functionality, and CSS3 for responsive UI design.}
            \resumeItem{Implemented features such as product listing, add-to-cart functionality, quantity updates, and real-time price calculation to enhance the user shopping experience.}
            \resumeItem{Implemented smooth animations and transitions using CSS3}
          \resumeItemListEnd
    \resumeSubHeadingListEnd

%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {GROW MORE Institute of Commerce and Arts College}{Himatnagar, Gujarat}
      {Bachelor of Science in Computer Applications \& Information Technology (B.Sc CA \& IT)}{Graduated:2026}
      \resumeItemListStart
        \resumeItem{Relevant Coursework: Data Structures, Algorithms, Database Management, Web Technologies, Software Engineering}
        \resumeItem{Academic Projects: Developed multiple web applications demonstrating proficiency in full-stack development}
      \resumeItemListEnd
  \resumeSubHeadingListEnd

%-----------ACHIEVEMENTS & CERTIFICATIONS-----------
\section{Achievements \& Additional Information}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Code Quality}{: Consistently write clean, well-documented code following industry best practices and coding standards} \\
     \textbf{Self-Learner}{: Actively expanding skillset through online courses and documentation in React, and cloud technologies} \\
     \textbf{Problem Solver}{: Strong analytical and debugging skills with experience in error handling and performance optimization} \\
     \textbf{Open Source}{: Active GitHub contributor with multiple repositories demonstrating version control proficiency}
    }}
 \end{itemize}

%-------------------------------------------
\end{document}
