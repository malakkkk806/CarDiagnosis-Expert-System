# 🧰 Car Diagnosis Expert System (Prolog)

*A rule-based expert system for diagnosing common car problems through interactive symptom-based questioning*

## 💡 Overview

This expert system helps users identify potential car issues by:
- Asking targeted questions about symptoms
- Applying logical reasoning through backward chaining
- Grouping diagnoses by car system (Electrical, Cooling, etc.)
- Providing human-readable explanations for each diagnosis

## 🔧 Technologies

- **Prolog** (SWI-Prolog recommended)
- Logical reasoning (Backward Chaining)
- Rule-based inference engine
- Dynamic fact assertion

## 🚀 Getting Started

### Prerequisites
- SWI-Prolog installed on your system

### Installation & Usage
1. Clone the repository
2. Run the system:
   ```prolog
   swipl 
   ?- [diagnosis]. 
   ?- run_diagnosis.
