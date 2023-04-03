## End to end Machine Learning Project


How to activate venv?

conda activate venv


Was facing an issue related to importing xgboost and catboost

"ImportError: DLL load failed while importing _catboost: Not enough memory resources are available to process this command."

Below link helped solve that issue:
https://stackoverflow.com/questions/66315487/dll-load-failed-while-importing-cv2-not-enough-memory-resources-are-available-to 

Run command to fix:
conda update -c conda-forge --all