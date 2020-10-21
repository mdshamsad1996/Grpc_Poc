Make sure python is added to path.


python --version Install virtualenv using pip.
```
 pip install virtualenv 
 ```
 
First create a virtual environment for the project.

```virtualenv -p python3.7 venv or virtualenv venv
     . venv/bin/activate (Linux)
     . venv/Scripts/activate (windows using Gitbash)
 ```
#### Install dependencies
 ```
pip install -r requirements.txt
```
This will install all the dependencies (grpcio-tools) mentioned in the requirements 

PPT link: https://prezi.com/view/y3BOdiW2QP6JjHXS8Vd1/
