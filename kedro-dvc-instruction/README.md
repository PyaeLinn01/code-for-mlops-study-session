## To Following the steps below, you will need to have the following installed:

- [Python 3.11+](https://www.python.org/downloads/)
- [DVC](https://dvc.org/doc/install)
- [Kedro](https://docs.kedro.org/en/stable/get_started/install.html)
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

## Steps to reproduce the project:

### Step 1: Kedro Project Setup

1. Clone the project: `git clone https://github.com/alexsnowschool/code-for-mlops-study-session.git`
2. Change the directory: `cd kedro-dvc`
3. Create conda environment: `conda create --name kedro-dvc python=3.11 -y`
4. Activate the conda environment: `conda activate kedro-dvc`
5. Install the project dependencies: `pip install kedro`
6. Create new branch: `git checkout -b kedro-dvc-demo`
7. Run the project: `kedro new --starter=spaceflights-pandas`
8. Change the directory: `cd spaceflights-pandas`
9. Install the project dependencies: `pip install -r requirements.txt`

### Step 2: DVC Setup

1. Install DVC: `pip install dvc dvc[data]`
2. Initialize DVC: `dvc init --subdir`