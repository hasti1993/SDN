# Ryu_controller_SDN
Routing in SDN
In this project, there are collected dataset in 2D matrices through shortest path method for routing. The rows show the traffic in each link and the columns show the nodes'(switches') id. There are also labels collected in one-hot vectors which show the next node as the target. Then these dataset is given to CNN algorithm as the input. After the training phase, the trained model is saved in a .h5 file to be used in predicting the next node instead of shortest path method.
