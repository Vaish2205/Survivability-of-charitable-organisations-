# Survivability of charitable organisations – What factors influence whether a charity survives?

This ongoing project investigates **what factors influence the survival** of charitable organisations in the UK by analyzing comprehensive administrative data from the UK Charity Commission.

## Project Goal
To explore and identify key variables — such as financial health, age, legal structure, governance quality, and operational characteristics — that contribute to whether a charity continues operating or ceases operations.

## Datasets Explored

### 1. UK Charity Commission Dataset (Selected)
- **Source**: Charity Commission for England and Wales full register download
- **Scale**: 392,350 registered charities across 13 interconnected tables
- **Coverage**: 1960s - 2024
- **Total Records**: 8+ million across all tables
- **Includes**:
  - Core organizational information (registration, legal structure, contact details)
  - Financial data (income, expenditure, reserves)
  - Governance information (trustees, policies)
  - Operational details (activities, beneficiaries, geographic scope)
  - Regulatory history and compliance records

### 2. Companies House Dataset (Explored but not used)
- **Scale**: 5.66 million UK companies
- **Reason for exclusion**: Focus on charity-specific factors rather than general business patterns
- **Decision rationale**: Charity Commission data provides sector-specific variables more relevant to charitable organization survival

## Research Questions

### Main Research Question
**Survivability of charitable organisations – What factors influence whether a charity survives?**

### Sub-Research Questions
- **RQ1:** What organizational demographics and structural characteristics differentiate surviving charities from those that cease operations?
- **RQ2:** How do financial characteristics and resource patterns influence survival probability across charity income segments?
- **RQ3:** Which governance and operational factors exhibit the strongest association with charity survival outcomes?
- **RQ4:** How can advanced feature engineering extract predictive signals from charity administrative data to improve survival prediction accuracy?
- **RQ5:** What modeling approach and validation framework optimizes both predictive performance and interpretability for charity sector decision-making applications?

## Project Phases

- **Phase 1**: Data acquisition & cleaning from 13 tables
- **Phase 2**: Exploratory data analysis (EDA) for charity survival trends
- **Phase 3**: Data integration & master dataset creation
- **Phase 4**: Advanced feature engineering (organizational, financial, governance)
- **Phase 5**: Feature selection and validation
- **Phase 6**: Logistic regression modeling and evaluation

## Project Status
- [x] Research questions defined  
- [x] Datasets loaded and explored
- [x] Data integration and cleaning completed
- [x] Feature engineering completed  
- [x] Exploratory analysis completed
- [x] Modeling and evaluation completed
- [ ] **Phase 7**: Writing dissertation report (Current)


## Note
This is an ongoing project and changes can be made as the research progresses. This README provides an overview of the project structure and methodology. The research contributes to understanding charity sector sustainability through comprehensive data science analysis of UK administrative data.





\documentclass[11pt,a4paper]{article}
\usepackage[a4paper,margin=1in]{geometry}
\usepackage{hyperref}
\usepackage{enumitem}

\begin{document}

\title{Survivability of Charitable Organisations \\ \large What factors influence whether a charity survives?}
\author{Vaishnavi Patil \\ MSc Data Science and Analytics, University of Leeds}
\date{August 2025}
\maketitle

\section*{Project Overview}
This repository contains the analysis, models, and report for a dissertation project conducted as part of the MSc Data Science and Analytics programme at the University of Leeds, in collaboration with the Social Investment Business (SIB).

The project investigates the determinants of survival among charitable organisations in the UK. Using comprehensive administrative records from the UK Charity Commission, this study applies advanced data science techniques to explore which factors most strongly influence whether a charity continues operating or ceases operations.

\section*{Project Goal}
To identify organisational, financial, governance, and operational factors that influence the survival of UK charities, and to build interpretable predictive models that support the sector’s sustainability.

\section*{Datasets}
\begin{enumerate}
  \item \textbf{UK Charity Commission Dataset (Primary)}  
  \begin{itemize}[leftmargin=2em]
    \item Source: \href{https://register-of-charities.charitycommission.gov.uk/en/}{Charity Commission for England and Wales}
    \item Coverage: 1960s--2024
    \item Scale: 392,350 registered charities across 13 tables
    \item Total Records: 8+ million
    \item Includes: organisational info, financial data, governance, operations, compliance
  \end{itemize}
  \item \textbf{Companies House Dataset (Explored, not used)}  
  \begin{itemize}[leftmargin=2em]
    \item Scale: 5.66 million UK companies
    \item Reason for exclusion: lacks charity-specific governance and compliance data
  \end{itemize}
\end{enumerate}

\section*{Research Questions}
\textbf{Main Question:} What factors influence whether a charity survives?  

\textbf{Sub-Questions:}
\begin{enumerate}
  \item What organisational demographics and structures differentiate surviving charities from those that cease operations?
  \item How do financial characteristics and resource patterns influence survival probability across charity income segments?
  \item Which governance and operational factors show the strongest association with survival outcomes?
  \item How can feature engineering extract predictive signals from administrative data?
  \item Which modelling approach best balances predictive performance and interpretability?
\end{enumerate}

\section*{Project Phases}
\begin{enumerate}
  \item Data acquisition \& cleaning
  \item Exploratory Data Analysis (EDA)
  \item Feature Engineering
  \item Feature Selection
  \item Modelling
  \item Evaluation \& Validation
  \item Reporting (dissertation and prototype dashboard)
\end{enumerate}

\section*{Key Findings}
\begin{itemize}[leftmargin=2em]
  \item \textbf{Top predictors of survival:} governance quality, younger organisational age, income above £10,000, recent operational activity, modern legal forms (CIOs).
  \item \textbf{Model Performance (Logistic Regression):} Accuracy = 81.6\%, Recall = 99.0\%.
  \item \textbf{Implications:} Younger charities can be more resilient; governance is the strongest determinant; prototype web tool supports risk assessment.
\end{itemize}

\section*{Technical Details}
\begin{itemize}[leftmargin=2em]
  \item \textbf{Language:} Python
  \item \textbf{Libraries:} pandas, numpy, scikit-learn, matplotlib, seaborn
  \item \textbf{Files:} \texttt{Project Analysis.ipynb} (notebook), \texttt{Vaishnavi\_201896641.pdf} (full dissertation), \texttt{README.md}
\end{itemize}

\section*{Status}
\begin{itemize}[leftmargin=2em]
  \item Research completed: data wrangling, analysis, modelling, validation
  \item Dissertation written and submitted (August 2025)
  \item Future work: dynamic survival analysis, causal inference
\end{itemize}

\section*{Author}
\textbf{Vaishnavi Patil} \\
MSc Data Science and Analytics, University of Leeds \\
Conducted under the CDRC Masters Dissertation Scheme \\
Supervisors: Dr.\ Luissa Cutillo (University of Leeds), Christopher Davy and Alannah Keogh (Social Investment Business)

\end{document}

