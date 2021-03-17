# IaC-core

### Help page:

```bash
$  make -f Makefile-IaC-core help

 Choose a command run:

var                                      Show all defined variables
install-csv2md                           Install Python csvtomd
extract-help                             Extract help section
add-help                                 Extract and output help section in $(TESTFILE)
sha256sum                                Generate SHA checksum of Makefile
validate-sha256sum                       Validate SHA checksum of Makefile

$  make -f Makefile-devops-venv help

 Choose a command run:

var                                      Show all defined variables
pre-commit-hooks                         Howto - Pre-commit hooks
fetch-github                             Git clone to $(REPO) - DevOps Tool codes
pip-install-choice                       Pick requirements.txt to PIP install
pip-install                              PIP install $(PIP) in virtual environment
pip-install-requirements                 PIP install $(PIP) in virtual environment
pre-commit                               Setup pre-commit
hello-venv                               Python run src/main.py in virtual environment
devops-venv                              Python run devops.py in virtual environment
branch2main                              Merge branch to main

```

