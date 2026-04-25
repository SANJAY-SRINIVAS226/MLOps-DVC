
 📌 Project Overview
- Initialize DVC in a Git repository
- Track datasets with `.dvc` files
- Save multiple versions of data
- Push and pull data between local and remote storage
- Integrate dataset versioning with Git commits

 🛠️ Tech Stack
- **Python** (for ML scripts)
- **DVC** (Data Version Control)
- **Git & GitHub** (version control & collaboration)

⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/SANJAY-SRINIVAS226/MLOps-DVC.git
   cd MLOps-DVC

Initialize DVC (if not already):
dvc init

Add dataset to DVC:
dvc add data/


Commit changes:
git add data.dvc .gitignore
git commit -m "Track dataset with DVC"


Push dataset to remote (if configured):
dvc push
