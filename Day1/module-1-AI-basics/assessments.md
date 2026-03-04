TRY OUT CREATING FOLDER USING PYTHON:

import os
os.mkdir("AI_Project")
os.makedirs("AI/Day1/Labs")

or 
//if already exist
import os

if not os.path.exists("AI_Project"):
    os.mkdir("AI_Project")
