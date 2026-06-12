🎓 Campus Navigation System
🚀 Intelligent Campus Navigation AssistantAn AI-powered system that finds the optimal route inside a university campus using A Search Algorithm.*
📖 AbstractThe Campus Navigation System is an intelligent AI-based navigation assistant designed to help students, faculty, and visitors efficiently navigate a university campus. The system models the campus as a graph where locations such as classrooms, laboratories, libraries, cafeterias, and administrative offices are represented as nodes, while pathways connecting them are represented as edges.
Using Artificial Intelligence search techniques, the system computes optimal routes based on distance, travel time, and accessibility constraints. The project demonstrates graph-based knowledge representation, heuristic search, explainable reasoning, and performance evaluation.
🎯 Objectives✅ Model a campus as a graph
✅ Find shortest paths between locations
✅ Apply AI search algorithms
✅ Generate explainable route traces
✅ Analyze algorithm performance
🏫 Campus Mapundefined
Gate
├── Library
│   ├── Lab
│   └── Admin
│
└── Cafeteria
    └── Lab

Lab
└── Classroom

Admin
└── Classroom

🧠 AI Concepts UsedCO1PEAS ModelProblem FormulationState Space RepresentationGraph Knowledge RepresentationCO2BFSDFSUniform Cost SearchGreedy SearchA* Search AlgorithmCO3Constraint Satisfaction ConceptsAccessibility ConstraintsRoute RestrictionsCO4Utility-Based Decision MakingOptimal Route SelectionCO5Probabilistic ReasoningUncertainty HandlingCO6Hybrid AI SystemExplainable AIPerformance Analysis⚙️ Technologies UsedTechnologyPurposePythonProgramming LanguageHeap QueuePriority QueueGraphsCampus RepresentationA* SearchPath FindingGitHubVersion Control🔍 Algorithm UsedA* Search AlgorithmThe A* algorithm combines:
undefined
f(n) = g(n) + h(n)

Where:
g(n) = Actual path costh(n) = Heuristic estimatef(n) = Total estimated costThis helps find the shortest route efficiently.
▶️ Sample Outputundefined
===================================
AI CAMPUS NAVIGATION SYSTEM
===================================

Enter Starting Location: Gate
Enter Destination Location: Classroom

OPTIMAL PATH FOUND

Route:
Gate -> Library -> Lab -> Classroom

Total Distance:
9

Nodes Expanded:
4

📊 Features✨ Shortest Path Calculation
✨ Graph-Based Navigation
✨ Explainable Search Trace
✨ Heuristic Route Planning
✨ Performance Metrics
✨ User-Friendly Interface
📂 Project Structureundefined
Campus-Navigation-System
│
├── main.py
├── README.md
└── requirements.txt

🚀 How to RunClone Repositoryundefined
git clone https://github.com/yourusername/Campus-Navigation-System.git

Run Programundefined
python main.py

📸 ScreenshotsUpload screenshots into a folder named images.
undefined
Campus-Navigation-System
│
├── images
│   ├── output1.png
│   ├── output2.png
│
├── main.py
└── README.md

Display them using:
undefined
## Project Output

![Output 1](images/output1.png)

![Output 2](images/output2.png)


👩‍💻 Project TeamYerrolla EekshithaTeam Members📚 CourseCourse: CFAI (Computational Foundations of Artificial Intelligence)
Project Title: Campus Navigation System
Academic Year: 2025–26
🌟 Thank You 🌟⭐ If you like this project, give it a star on GitHub ⭐
⭐ If you like this project, give it a star on GitHub ⭐
