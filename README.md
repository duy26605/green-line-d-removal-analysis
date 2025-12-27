\section{Project Overview}

This project evaluates the impacts of removing the \textbf{MBTA Green Line D Branch} on travel behavior and roadway network performance in the Boston metropolitan area. The analysis focuses on how transit service removal affects \textbf{mode choice, traffic demand allocation, and congestion patterns} within a dense urban transportation network.

The study was completed as part of \textbf{CIVE 7381 -- Transportation Demand Models} at Northeastern University.

\section{Study Objectives}

The primary objectives of this project are to:
\begin{itemize}
    \item Evaluate changes in traffic volumes, congestion, and travel times resulting from removal of the Green Line D Branch;
    \item Examine reallocation of \textbf{home-based work (HBW)} trips between auto and transit modes;
    \item Compare base case conditions with a no--D branch scenario;
    \item Provide insights into transit system resilience and transportation planning implications.
\end{itemize}

\section{Methodology}

A four-step travel demand modeling framework was applied using \textbf{TransCAD}, consisting of the following components:

\begin{enumerate}
    \item \textbf{Trip Generation and Distribution}: Fixed HBW origin--destination (OD) matrices were held constant across scenarios.
    \item \textbf{Mode Choice Modeling}: A nested logit model was used to allocate trips between auto and transit based on generalized travel cost, including travel time, monetary cost, parking cost, and income.
    \item \textbf{Traffic Assignment}: Auto trips were assigned using a user-equilibrium (UE) approach with congestion represented through volume--delay functions.
    \item \textbf{Scenario Analysis}: Results from a base case network were compared with an alternative scenario in which the Green Line D Branch was removed from the transit network.
\end{enumerate}

This modeling approach isolates the effects of transit network modification on demand allocation and roadway performance.

\section{Key Findings}

Key findings from the analysis include:
\begin{itemize}
    \item Removal of the Green Line D Branch results in \textbf{modest increases in vehicular congestion}, vehicle miles traveled (VMT), and vehicle hours traveled (VHT);
    \item Congestion impacts are \textbf{spatially concentrated} along corridors parallel to the former D Branch;
    \item Mode choice results show a redistribution of HBW trips driven by relative changes in generalized travel cost;
    \item Increased auto congestion reduces the attractiveness of driving, leading to non-intuitive mode choice responses.
\end{itemize}

\section{Data Sources}

The analysis integrates multiple regional transportation datasets, including:
\begin{itemize}
    \item MBTA General Transit Feed Specification (GTFS) data for transit service attributes;
    \item Boston Metropolitan Planning Organization (MPO) roadway network and zonal data;
    \item Transportation Analysis Zones (TAZs) for regional travel demand representation.
\end{itemize}

\section{Academic Context}

\begin{itemize}
    \item \textbf{Course}: CIVE 7381 -- Transportation Demand Models
    \item \textbf{Institution}: Northeastern University
    \item \textbf{Instructor}: Prof. Haris Koutsopoulos
    \item \textbf{Authors}: Duy Nguyen, Vishnu Sreekumar
    \item \textbf{Date}: December 2025
\end{itemize}

\section{Notes}

This project focuses on redistribution of existing travel demand rather than induced or suppressed demand. Results should be interpreted as relative behavioral and network performance responses rather than absolute ridership forecasts.
