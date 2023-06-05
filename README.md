First time here, follow these steps:

You have the very latest MLOX (v1.1+)fork by rfuzzo
[https://github.com/rfuzzo/mlox/releases/latest](https://github.com/rfuzzo/mlox/releases/latest)
After dropping mlox.exe on your Morrowind folder, simply execute it. 
Mlox v1.1+ will automatically download the latest rules from the mlox-rules GitHub repository.
But even with this new functionality, you can still add your own personal rules like so:

1. Go to your mlox rule folder
   - this is either in %localappdata%/mlox/mlox
   - or in <Morrowind>/mlox if you run mlox with the --local --gui flags
2. Create a new text file called mlox_my_rules.txt
3. Add your own rules there. On the next start, mlox will add these rules.

  
You have an older version of MLOX
1. make sure you have MLOX installed
2. run it once, a file `mlox_base.txt` will be created
3. download all three files from this repo.
- `mlox_base.txt` replaces the one that was just created
- `mlox_user.txt ` goes in the exact same directory
- `Update_Rules.bat` goes in your MLOX directory
> You can also clone the github repo directly into your mlox directory and git fetch
the mlox repo has a gitignore file that is updated to work with mlox

Enjoy!
