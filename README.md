# treble.ai-data-engineer-test
Technical test for data engineer role at Treble.ai

#### Create a virtual enviroment

Create a virtual enviroment for development, then activate it

Windows:
```shell
python -m venv venv
venv\Scripts\Activate.ps1
```

Linux & MacOS
```shell
python3 -m venv venv
source venv/bin/activate 
```

#### Install external packadges

Install all external packadges needed specified in `requirements.txt`

```shell
pip install -r requirements.txt
```

When adding new external packadges to project, always update this file.


#### Running the Jupyter Notebook
Start Jupyter Notebook

```shell
jupyter notebook
```
Navigate to the notebook you want to run in the Jupyter interface via your browser.

Before executing any code, ensure you load the environment variables (if your notebook uses them). You can do this at the top cell of your Jupyter Notebook with:

python
Copy code
```shell
import dotenv
dotenv.load_dotenv()
```
Execute your notebook as usual.