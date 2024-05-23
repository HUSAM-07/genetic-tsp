# Genetic Optimization Algorithm for TSP

### Demo Overview
- Uses a genetic algorithm to solve the Traveling Salesman Problem (TSP).
- Developed for the Artificial Intelligence Course by *Mohammed Husamuddin*.

### Parameters
- **Dataset Selection**: Choose from multiple pre-defined datasets.
- **Number of Generations**: Set the evolutionary generations (10-5000).
- **Population Size**: Define the size of the population (10-5000).
- **Mutation Probability**: Adjust the mutation rate (0.0-1.0).
- **Random Seed**: Option to set a random seed for reproducibility.

### Output
- **Best Solution**: Displays the optimal route and its distance.
- **Distance Over Time**: Shows the progress of the distance optimization.
- **Optimal Distance**: Compares with known optimal distances.

### Execution
- Runs the genetic algorithm with selected parameters.
- Visualizes the optimization process and final results.


> This is not meant to have great performance (neither in terms of speed or accuracy), it
is instead more focused in displaying the process visually and serve as an introduction
to the topic of genetic algorithms.

### Screen capture :video_camera:
![](images/streamlit-app-2021-05-08-15-05-17.gif)

### Run it locally :microscope:
Right now this project is not hosted anywhere so if you'd like to test it, you can do so
by running `make run`. Once it builds the image and starts the server, you can access
it at `http://localhost:8501/`.
