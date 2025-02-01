1. Go into the `hw1code` directory with Terminal and install the dependencies with `pip install scikit-learn scipy numpy matplotlib`.
2. To see the plot for q2e, run `python3 q2.py`.
3. To see the plot for q4a (MNIST), uncomment the code between lines `71-77` and comment out the code between lines `79-85` in `q4.py`, then run `python3 q4.py`.
   
   To see the plot for q4b (SPAM):
   - First, go into the `scripts` directory, comment out the code between lines `312-354` in `featurize.py`, then run `python3 featurize.py`.
   - Once the above is done, exit back into the `hw1code` directory, then comment out the code between lines `71-77` and uncomment the code between lines `79-85` in `q4.py`.
   - Finally, run `python3 q4.py`.

4. To see the plot for q5, run `python3 q5.py`. The table will be printed out in the terminal.
5. To see the plot for q6, run `python3 q6.py`. The table will be printed out in the terminal.
6. To generate the CSV for q7a (MNIST):
   - Uncomment the code between lines `50-61` and comment out the code between lines `63-80` in `q7.py`, then run `python3 q7.py`.
   - The test predictions will be saved to `mnist_kaggle.csv`.
   
   To generate the CSV for q7b (SPAM):
   - First, go into the `scripts` directory, uncomment the code between lines `312-354` in `featurize.py`, then run `python3 featurize.py`.
   - Once the above is done, exit back into the `hw1code` directory, then comment out the code between lines `50-61` and uncomment the code between lines `63-85` in `q7.py`.
   - Finally, run `python3 q7.py`.
   - The test predictions will be saved to `spam_kaggle.csv`.
