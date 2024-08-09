Welcome to the 
Incident Clustering Analysis Tool!
------------------------------------
------------------------------------

What's new?

With the development of a new front-end interface, 
users no longer have to directly interact with the codebase to run the model as the app now offers a more user-friendly interface, 
facilitating the transition from a technical notebook to a user-oriented experience.

------------------------------------
------------------------------------

Reminders for installation & running the model

1. Install the VSCode Python Extension 
2. Install C++ Builder Tools - https://visualstudio.microsoft.com/visual-cpp-build-tools/
3. Make sure to $ pip install -r requirements.txt
4. Once all of these are done, you can run the model $ streamlit run run_model.py

------------------------------------
------------------------------------

Common Issues & Watch-outs

1. Running the "train_model_ul.ipynb" Notebook and you get an SSL error, 
    - this may be a Network issue especially if you are working from home, 
        (a) you may want to run the Notebook in the office connected to P&G Network 
        (b) or disable Zscaler but this will need a code

2. 'Unpickling error' - This means that the pkl file for the model was corrupted options
    - retrain the model in 'train_model_ul.ipynb'

------------------------------------
------------------------------------

Want to know more? Have questions/concerns? Contact:
Alvin Religioso - religioso.ad@pg.com
Lexine Uy - uy.lr@pg.com
