![REDACTOR](https://github.com/NoDataFound/Redactor/assets/3261849/0900d75a-6749-4f94-a055-0e390d6c7270)

[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/PyGithub)](https://pypi.org/project/PyGithub/)
[![PyPI - License](https://img.shields.io/pypi/l/PyGithub)](https://github.com/PyGithub/PyGithub/blob/master/LICENSE)
[![PyPI - Version](https://img.shields.io/pypi/v/PyGithub)](https://pypi.org/project/PyGithub/)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/PyGithub)](https://pypi.org/project/PyGithub/)
<img width="1681" alt="Screenshot 2024-03-03 at 12 39 20 PM" src="https://github.com/NoDataFound/Redactor/assets/3261849/94c65b39-a3fb-47f0-b5cb-bed5df0defda">


# Features

- `GitHub Repository Search` Without using the github API, Clone all repositories of a specified GitHub user and search through their contents for specific terms.
- `Customizable Search Terms` Define custom search terms in a text file for flexible search criteria.
- `Report Generation` Automatically generates a report detailing the findings, including repository names, files where the terms were found, and the content where the terms matched.
- `Redaction of Findings` Option to redact findings in the report by replacing them with [REDACTED].


# Installation 

```
$ git clone https://github.com/NoDataFound/Redactor.git
$ cd Redactor
```

1. Install Virtualenv (if not already installed):
```
$ pip install virtualenv
```

2. Create a Virtual Environment:
```
$ virtualenv venv
```

3. Activate the Virtual Environment:

```
On Windows:
$ venv\Scripts\activate
```

On macOS and Linux:
```
$ source venv/bin/activate
```

4. Install Required Packages:
```
$ pip install -r requirements.txt
```

5. Run the Script:

```
$ python redactor.py
```

6. Follow the on-screen instructions to enter the GitHub username and proceed with the search.

7. Once the script completes, you can find the generated report in the `reports` directory.

8. Optionally, you can choose to redact findings by running the script again and selecting `Y` when prompted.

9. Deactivate the Virtual Environment:

```
$ deactivate
```
