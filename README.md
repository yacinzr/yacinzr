%-------------------------
% CV en LaTeX
% Auteur : Jake Gutierrez
% Modifié pour Yacine ZERIKAT
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
\usepackage[french]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

% [Le reste des configurations reste inchangé]

\begin{document}

%----------EN-TÊTE----------
\begin{center}
    {\Huge \scshape Yacine ZERIKAT} \\ \vspace{1pt}
    Paris, France \\ \vspace{1pt}
    \small\href{tel:+33.755.276.928}{\raisebox{-0.05\height}\faMobile \ +33.755.276.928} ~ \href{mailto:zerikatyacine@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{zerikatyacine@gmail.com}} ~ 
    \href{https://linkedin.com/in/yacine-zerikat-b0256a188}{\raisebox{-0.2\height}\faLinkedin\ \underline{Yacine-ZERIKAT}}  ~
    \href{https://github.com/yacinzr}{\raisebox{-0.2\height}\faGithub\ \underline{github.com/yacinzr}} ~
    \href{https://yacinzr.github.io/Portfolio-/}{\raisebox{-0.2\height}\faGlobe\ \underline{yacinzr-Portfolio}}
    \vspace{-8pt}
\end{center}

%-----------FORMATION-----------
\section{Formation}
  \resumeSubHeadingListStart
    \resumeSubheading
      {CY Tech (Ex EISTI)}{2021 - 2024}
      {Diplôme d'Ingénieur en Informatique - Spécialisation IA}{Paris, France}
        \resumeSubheading
      {Université des sciences et de la technologie}{2016 - 2019}
      {Licence en Systèmes d'Information et Données}{Oran, Algérie}
  \resumeSubHeadingListEnd

\section{Expérience Professionnelle}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Eli Lilly and Company}{Sept 2022 -- Oct 2023}
      {Data Scientist}{Strasbourg, France}
      \resumeItemListStart
        \resumeItem{J'ai contribué à un projet visant à développer un chatbot pour répondre aux questions des utilisateurs au sein de l'entreprise. Dans ce contexte, mes responsabilités comprenaient :
        \begin{itemize}
            \item Identification de différentes sources de données pertinentes pour le projet.
            \item Préparation et génération des données nécessaires à l'entraînement du modèle.
            \item Conception du modèle NLP pour comprendre les intentions des utilisateurs.
            \item Entraînement du modèle et évaluation de ses performances.
            \item Construction de la logique de l'agent conversationnel basée sur le modèle NLP.
            \item Collaboration avec des équipes externes pour déployer le modèle en production.
        \end{itemize}}
      \resumeItemListEnd

    \resumeSubheading
      {Moody's Analytics}{Avr 2022 -- Sept 2022}
      {Ingénieur de Données}{Grenoble, France}
      \resumeItemListStart
        \resumeItem{J'ai participé à l'incorporation d'un module de traçabilité des données dans une solution SaaS hébergée sur AWS. Parmi les tâches qui m'ont été confiées figuraient :
        \begin{itemize}
            \item Développement et intégration du module de traçabilité des données.
            \item Implémentation du module de traçabilité des données en utilisant les services AWS appropriés et les outils Kubernetes.
            \item Intégration du module dans la solution SaaS existante pour permettre la collecte et la visualisation des métadonnées de traçabilité des données.
        \end{itemize}}
      \resumeItemListEnd

   \resumeSubheading
  {Sonatrach}{Sept 2019 -- Août 2019}
  {Ingénieur de Données \& Data Scientist}{Oran, Algérie}
  \resumeItemListStart
    \resumeItem{Travail sur diverses tâches d'ingénierie de données incluant la collecte, le nettoyage et le prétraitement des données. Mes responsabilités comprenaient :
    \begin{itemize}
        \item Collecte, nettoyage et prétraitement des données pour assurer leur qualité et leur pertinence pour l'analyse.
        \item Développement de pipelines de données utilisant des procédures stockées et des processus ETL pour automatiser les flux de travail de données.
        \item Création de tableaux de bord interactifs et de rapports analytiques pour fournir des insights et soutenir la prise de décision.
        \item Réalisation de modélisations prédictives utilisant des algorithmes d'apprentissage automatique pour anticiper les pannes d'équipement et améliorer les stratégies de maintenance.
    \end{itemize}}
  \resumeItemListEnd

\vspace{-15pt}
%-----------CERTIFICATIONS-----------
\section{Certifications}

\begin{itemize}[left=0pt, label=--]
    \item AZ-900 : Microsoft Azure Fundamentals
    \item Databricks Generative AI Fundamentals
    \item Dataiku ML Practitioner
    \item IBM - Bases de données et SQL pour la Data Science avec Python
\end{itemize}
 \vspace{-16pt}

%-----------COMPÉTENCES TECHNIQUES-----------
\section{Compétences Techniques}

\begin{itemize}[leftmargin=0.20in, label={}]
    \small{\item{
        \textbf{Langages de Programmation}{: Python, R, Scala, Java, C, HTML/CSS, JavaScript, SQL} \\ 
        \textbf{Data Science/IA}{: Scikit-learn, TensorFlow, Keras, PyTorch, OpenAI LLM} \\
        \textbf{Ingénierie des Données}{: Spark, Databricks, Talend, Alteryx, Dataiku, Hadoop} \\
        \textbf{Cloud/DevOps}{: Azure, AWS, Docker, CI/CD, GIT} \\
        \textbf{Outils de Développement}{: VS Code, Eclipse, Android Studio, GitHub} \\
        \textbf{Technologies/Frameworks}{: Linux, Jenkins, JUnit, WordPress, NoSQL, Power BI, Agile} \\
    }}
\end{itemize}
 \vspace{-16pt}

\end{document}
