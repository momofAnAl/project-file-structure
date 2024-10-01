# Calculator 

## Skills Assessed

- Using addition to add the values of numbers
- Using subtraction to subtract values of numbers
- Using multiplication to multiply values of numbers
- Uisng division to divide values of numbers

## Set up environment 
1. Navigate to your projects folder which is named `projects`. 

```bash
$ cd ~/Developer/projects
```

2. "Clone" (download a copy of this project) into your projects folder. This command makes a new folder called `viewing-party`, and then puts the project into this new folder.  Make sure you are cloning from your copy of the project and not the class version (ada-cX).

```bash
$ git clone ...
```

Use `ls` to confirm there's a new project folder

3. Move your location into this project folder

```bash
$ cd viewing-party
```

4. Create a virtual environment named `venv` for this project:

```bash
$ python3 -m venv venv
```

5. Activate this environment:

```bash
$ source venv/bin/activate
```

Verify that you're in a python3 virtual environment by running:

- `$ python --version` should output a Python 3 version
- `$ pip --version` should output that it is working with Python 3

6. Install dependencies once at the beginning of this project with

```bash
# Must be in activated virtual environment
$ pip install -r requirements.txt
```
Summary of one-time project setup:
One person:
- [ ] Fork the project respository
- [ ] `cd` into your `projects` folder
- [ ] Clone the project onto your machine
- [ ] `cd` into the `viewing-party` folder
- [ ] Create the virtual environment `venv`
- [ ] Activate the virtual environment `venv`
- [ ] Install the dependencies with `pip`

7. Run the test(s)!
  
```bash
# Must be in activated virtual environment in the project-root directory
$ pytest
```

