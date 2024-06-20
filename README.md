# game_dev

Download and install [Miniconda](https://docs.anaconda.com/free/miniconda/miniconda-install/) to begin.

After installing Miniconda, install required libraries to run our application with the following command in the terminal ```conda env create -f environment.yml```. Then, activate the installed enviroment. Please note that this enviroment file works on M1 Mac, and it should work on other platform. If there is a problem installing necessary libraries from the environment file, please look at ```app.py``` to manually install all the libraries imported at the top of the file.

Run the following command in the terminal to export your OpenAI API key as an environment variable with the following command ```export OPENAI_API_KEY=xxx``` and replace ```xxx``` with your own API key.

Then, run the following command in the terminal to launch our application ```python -m flask run```. The terminal should show the following message: ```* Running on http://127.0.0.1:5000```. It is possible that the port number may be different. Expose necessary ports or close other applications
