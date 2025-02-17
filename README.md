# Lab 1 - Python fundamentals
### OPA24 @ NBI/Handelsakademin, Gothenburg
This repository is the first lab of my current part-course **AI 1 - Python** of my ongoing education "Object-oriented programming with AI".

The purpose of this lab is to use fundamentals of python to transform raw data into a representable format. 

### Initial thoughts & workflow
First I looked through the .txt-files to see how they are formatted, so that I could write the code to properly divide the sequences. I saw the ">" and thought it will be perfect to use for dividing the sequences. I started by extracting the data by opening the file, extracting the sequences, and finally closing the file. The extracted sequences was stored in a **list of dictionaries** that I could later use to count letters in. 
I used a **print()** to check whether I had divided the sequences properly or not.

After the sequences were divided, I needed to store them separately and count the letters (ignoring letters that are not A, T, C, or G) and storing their count. Lists of dictionaries felt like the best way to store this. Initially I was going to loop through the sequences to count the letters, but then I found out about the module **Counter** that I decided to use instead. After counting the letters I used **print()** to confirm their count compared to the .txt-file.

After getting all of the previous to work, I went on with reading up on **matplotlib**. Initially I had issues with this due to not having fully understood virtual environments in Python, which lead me to read up more on this subject to fully grasp the how's and why's. After getting the virtual environment situation sorted I got **matplotlib** to work, and managed to print out the letter counts as a bar chart.

