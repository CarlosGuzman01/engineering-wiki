## setup jupyter notebook on vs code:


### Step 1. Create project folder

```bash
# syntax
mkdir [folder-name]

# example
mkdir myproject
```

### Step 2. Create, activate & select your virtual environment

Navigate to / open your project folder and create a virtual environment inside of it:

```bash
# syntax
python3 -m venv &lt;virtual environment name&gt;

# example
# that would create a virtual environment named 'myenv'
python3 -m venv myenv
```

Now activate the virtual environment and when VS CODE prompts you to set it as default for the project, hit yes.

```bash
# syntax
source &lt;virtual environment name&gt;/bin/activate

# example
source myenv/bin/activate
```

### Step 3. Install `ipykernel`

Now that your virtual environment is activated, install `ipykernel`

```bash
pip3 install ipykernel
```


### Step 4. Create new kernel

Now you can create a new kernel to be used for your project:

```bash
# syntax
python3 -m ipykernel install --user --name="[projectname]"

# example
# That would create a kernel named 'myproject'
python3 -m ipykernel install --user --name="myproject"
```


### Step 5. Install jupyter notebook


```bash
pip install notebook
```

### Step 6. Start jupyter

Now you can start Jupyter. I do it from the VS Code terminal.

```bash
jupyter notebook
```






---


