\documentclass[11pt]{article}

\usepackage[margin=1in]{geometry}
\usepackage{hyperref}
\usepackage{enumitem}
\usepackage{parskip}
\usepackage{titlesec}

% Reduce spacing around section headers
\titleformat{\section}{\large\bfseries}{}{0em}{}
\titleformat{\subsection}{\normalsize\bfseries}{}{0em}{}

\setlist[itemize]{leftmargin=1.2em}
\setlist[enumerate]{leftmargin=1.5em}

\begin{document}

\begin{center}
    {\Large \textbf{Green Line D Branch Removal Analysis}}\\[6pt]
    \small Transportation Demand Modeling \& Network Performance Evaluation
\end{center}

\vspace{1em}

\section*{Overview}
This repository evaluates the impacts of removing the \textbf{MBTA Green Line D Branch} on
travel behavior and roadway network performance in the Boston metropolitan area. The
analysis focuses on changes in \textbf{mode choice, traffic demand allocation, and congestion}
using a four-step travel demand modeling framework.

\vspace{0.5em}

\section*{Study Objectives}
\begin{itemize}
    \item Assess changes in traffic volumes, congestion, and travel times
    \item Examine reallocation of home-based work (HBW) trips between auto and transit
    \item Compare base case and no--D branch scenarios
    \item Provide insights into transit system resilience and planning
\end{itemize}

\section*{Methodology}
\begin{enumerate}
    \item \textbf{Trip Generation \& Distribution} \\
    Fixed HBW OD matrices held constant across scenarios
    \item \textbf{Mode Choice} \\
    Nested logit model based on generalized travel cost
    \item \textbf{Traffic Assignment} \\
    User-equilibrium auto assignment with congestion effects
    \item \textbf{Scenario Analysis} \\
    Base case vs.\ network without the Green Line D Branch
\end{enumerate}

\section*{Key Findings}
\begin{itemize}
    \item Modest increases in vehicular congestion, VMT, and VHT
    \item Congestion impacts concentrated along parallel corridors
    \item Mode choice shifts driven by relative generalized travel cost
    \item Increased auto congestion reduces driving attractiveness
\end{itemize}

\section*{Data Sources}
\begin{itemize}
    \item MBTA General Transit Feed Specification (GTFS)
    \item Boston Metropolitan Planning Organization (MPO) network data
    \item Transportation Analysis Zones (TAZs)
\end{itemize}

\section*{Academic Context}
\begin{itemize}
    \item \textbf{Course}: CIVE 7381 -- Transportation Demand Models
    \item \textbf{Institution}: Northeastern University
    \item \textbf{Instructor}: Prof.\ Haris Koutsopoulos
    \item \textbf{Authors}: Duy Nguyen, Vishnu Sreekumar
    \item \textbf{Date}: December 2025
\end{itemize}

\section*{Notes}
This project analyzes redistribution of existing travel demand rather than induced demand.
Results represent relative behavioral and network performance responses rather than
absolute ridership forecasts.

\end{document}
