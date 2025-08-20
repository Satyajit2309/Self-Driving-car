# Self-Driving Car Simulation

This project is a simple, interactive simulation of a self-driving car built with JavaScript. It demonstrates key concepts of neural networks and sensor-based decision-making in a visual environment.

## 🚀 How to Run

To run the simulation, simply open the `index.html` file in your web browser. There are no external dependencies required.

## 📋 Features

* **Self-Driving Car**: A car that learns to navigate a road and avoid obstacles.
* **Neural Network**: A simple neural network that controls the car's movement.
* **Sensors**: The car is equipped with sensors to detect its surroundings.
* **Traffic Simulation**: The simulation includes other cars to create a more realistic environment.
* **Visualizer**: A visual representation of the car's neural network.

## 📂 File Structure

* `index.html`: The main HTML file that sets up the simulation environment.
* `style.css`: The CSS file for styling the simulation.
* `main.js`: The main JavaScript file that initializes and runs the simulation.
* `car.js`: Defines the `Car` class, which includes the car's properties and methods.
* `controls.js`: Defines the `Controls` class, which handles user input for controlling the car.
* `sensor.js`: Defines the `Sensor` class, which creates the car's sensors.
* `road.js`: Defines the `Road` class, which creates the road and lanes.
* `network.js`: Defines the `NeuralNetwork` and related classes for the car's brain.
* `visualizer.js`: Defines the `Visualizer` class for visualizing the neural network.
* `utils.js`: Contains utility functions used throughout the project.

## 🧠 Key Concepts

### Neural Network

The car's "brain" is a simple neural network defined in `network.js`. It takes the sensor readings as input and outputs the car's next move (forward, backward, left, or right).

### Sensors

The car uses sensors (`sensor.js`) to "see" the road and other cars. The sensors cast rays out from the car, and if a ray intersects with an obstacle, the sensor reading is updated.

### Car Controls

The `controls.js` file allows for manual control of the car using the arrow keys. This can be useful for training the neural network or for simply driving the car around.

### Road and Traffic

The `road.js` file creates the road and the lanes. The `main.js` file also generates other cars to create traffic, which the self-driving car must learn to navigate.
