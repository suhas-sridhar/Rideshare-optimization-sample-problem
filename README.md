# Rideshare-optimization-sample-project
The function takes in an excel file. It can take an arbitrary threshold value and pool limit. These can be defined by the user.
A sample excel file with benefit values for pooling rides has been attached. These benefit values can be defined by the user and the code will provide the optimized output that tells you what rides to pool, and the total benefit value. This output will be in an excel file defined by the user in the function.

![image](https://user-images.githubusercontent.com/96037819/146886335-ed701ace-407e-4f51-b1aa-0bf02d1fd7dd.png)

Future refinements to consider:
- List currently appends all possible combinations of rides, and then pops out the duplicates. Example the list will have A-B and B-A as two rides to pool, and then the code removes the duplicates. Code can be refined to have a check and update the list only once.
- Improve the output file that has better readability of the combinations of rides to pool.
- Reduction of time complexity
