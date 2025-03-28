# QnA-Model
Welcome to the QnA-Model repository!!!<br></br>
This project aims to build an AI-powered system that can extract questions and answers from any PDF document using Large Language Models (LLMs) like ChatGPT ! 

## Getting Started

### Prerequisites
1. Create a virtual python environment in your local directory.
```bash
python -m venv .venv
```
2. Activate the virtual python environment.

Windows
```bash
.venv\Scripts\Activate.ps1
```

Linux / macOS
```bash
source .venv/bin/activate
```



### Installation 
1. Clone this repository to your local machine.
```bash
git clone https://github.com/SulagnaKundu/QnA-Model.git
cd QnA-Model
```
2. Upgrade pip.
   
   ```bash
   python -m pip install --upgrade pip
   ```
3. Install the required modules with the requirements.txt
   ```bash
   pip install -r requirements.txt
   ```



## Usage
### Starting the server 
```bash
uvicorn main:app --reload
```

