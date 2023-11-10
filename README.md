# COMP 472 Assignment 1
## Team: RoboCops
### Team Members:
- Rongxi Meng (40045067)
- Chen Qian (27867808)

## There are several dicrectories need to be configured:

### directory to Load the datasets
penguins_data = pd.read_csv(**"./datasets/penguins.csv"**) <br>
abalone_data = pd.read_csv(**"./datasets/abalone.csv"**) <br>

### create a new folder called "result" to save texts and figures
for example: <br>
evaluate_and_save_results(base_dt_penguins, x_penguins, y_penguins, **"./result/penguin-performance.txt"**, "Base-DT")

the rest of program can run from top to bottom >_< 
