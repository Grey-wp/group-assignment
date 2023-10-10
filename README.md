# group-assignment
This is our Lab Assignment

The program first asks for the users name, storing it as a String variable. The program then asks the user how many times they would like their name to be printed, storing that value as an integer. a loop is run the amount of times the user specifies, printing their name each time. The code then finishes by stating how many times the name was printed. 



What the code looks like:

name = input('Enter your first name here please: ') //assigns user input to the variable name
iterations = int(input('Enter the amount of times you want this program to run: ')) //asks the user the number of times they want to print the name
count = 0
name = name.capitalize() //sets the first letter to capital 
for i in range(iterations): //amount of times it will run from car iterations
    print(name)//prints name
    count += 1
print('I just printed', name, count, 'time(s)!')//prints name and shows amount of times printed 

out put:

Antonio
Antonio
Antonio
Antonio

I just printed, Antonio, 4 time(s)!

Installation:
If you use conda, mamba, or pip, you can install JupyterLab with one of the following commands:

If you use conda:
conda install -c conda-forge jupyterlab
If you use mamba:
mamba install -c conda-forge jupyterlab
If you use pip:
pip install jupyterlab
If installing using pip install --user, you must add the user-level bin directory to your PATH environment variable in order to launch jupyter lab. If you are using a Unix derivative (e.g., FreeBSD, GNU/Linux, macOS), you can do this by running export PATH="$HOME/.local/bin:$PATH". If you are using a macOS version that comes with Python 2, run pip3 instead of pip.
For more detailed instructions, consult the installation guide. Project installation instructions from the git sources are available in the contributor documentation.

Installing with Previous Versions of Jupyter Notebook
When using a version of Jupyter Notebook earlier than 5.3, the following command must be run after installing JupyterLab to enable the JupyterLab server extension:

jupyter serverextension enable --py jupyterlab --sys-prefix

License:
JupyterLab uses a shared copyright model that enables all contributors to maintain the copyright on their contributions. All code is licensed under the terms of the revised version; you can find a copy right here in the project files.

Code of conduct:

The code of conduct can be found in the project files.

We as members, contributors, and leaders pledge to make participation in our community a harassment-free experience for everyone, regardless of age, body size, visible or invisible disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, caste, color, religion, or sexual identity and orientation.

We pledge to act and interact in ways that contribute to an open, welcoming, diverse, inclusive, and healthy community.

Our Standards
Examples of behavior that contributes to a positive environment for our community include:

Demonstrating empathy and kindness toward other people
Being respectful of differing opinions, viewpoints, and experiences
Giving and gracefully accepting constructive feedback
Accepting responsibility, apologizing to those affected by our mistakes, and learning from the experience
Focusing on what is best, not just for us as individuals, but for the overall community

We chose the "Contributor Covenant" as our code of conduct becasue it is one of the simplist and easiest to understand. It is important for a CoC to be able to skimmed over but completely understood, which this one does very well.


Group members:

Antonio
Jack
Grey

