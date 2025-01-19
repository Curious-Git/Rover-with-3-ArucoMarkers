This is a rover in a mars world that has 3 aruco markers (IDs - 0, 10 and 42) that can be inserted in the Gazebo World.
The markers are stored in the folder 'models' in 'rover_gazebo'.
Open the simulation in Gazebo and go to the Insert Tab, click on the marker you want to insert and place it in the world landscape.

In case you cannot see the markers in the inser tab, then:

navigate to your workspace directory


run this command:  export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:models

along with the usual source setup bash etc

This adds the all the models to the environment variable GAZEBO_MODEL_PATH



