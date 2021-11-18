# SOFTX_2020_112
pyGRETA, pyCLARA, pyPRIMA: A pre-processing suite to generate flexible model regions for energy system models
Introduction for the test case of pyGRETA, pyPRIMA and pyCLARA
Step 1a:
1. Go to Directory of pyGRETA and there to the subdirectory env.
2. Start a console and create a conda environment for pyGRETA.
conda env create –f pyGRETA.yml
3. When the creation is done, activate the environment. conda activate pyGRETA
4. In the console, go to the pyGRETA subdirectory code. cd ../code
5. Make sure in the file config.py the path to the database is correct (lines 68 and 70) and make further changes if necessary or wanted.
6. Run the python script runme_step1A.py python runme_step1A.py
If an Error “No such file or directory” occurs, check if all the data from the instructions is correctly placed in the database folder. Otherwise, wait until it is finished.
Step 1b:
1. Still in the console, go to Directory of pyPRIMA and there to the subdirectory env. cd ../../pyPRIMA/env
2. Again, create a conda environment, this time for pyPRIMA.
conda env create –f pyPRIMA.yml
3. When the creation is done, activate the environment. conda activate pyPRIMA
4. In the console, go to the pyPRIMA subdirectory code. cd ../code
5. Make sure in the file config.py the path to the database is correct (lines 68 and 70) and make further changes if necessary or wanted.
6. Run the python script runme_step1B.py and wait until it is finished. python runme_step1B.py
Step 2:
1. After that, go to Directory of pyCLARA and there to the subdirectory env. cd ../../pyCLARA/env
2. As before, create the conda environment for pyCLARA.
conda env create –f pyCLARA.yml
3. When the creation is done, activate the environment. conda activate pyCLARA
4. In the console, go to the pyCLARA subdirectory code. cd ../code
5. Make sure in the file config.py the path to the database is correct (lines 68 and 70) and make further changes if necessary or wanted.
6. Run the python script runme_step2.py and wait until it’s finished. python runme_step2.py
Step 3A:
7. Go back to Directory of pyGRETA and directly to the subdirectory code. cd ../../pyGRETA/code
8. Activate the environment again.
conda activate pyGRETA
9. Run the python script runme_step3A.py and wait until it is finished. python runme_step3A.py
Step 3B:
1. Finally, go to the subdirectory code of the pyPRIMA directory. cd ../../ pyPRIMA /code
2. Activate the environment again.
conda activate pyPRIMA
3. Run the python script runme_step3B.py and wait until it is finished. python runme_step3B.py
