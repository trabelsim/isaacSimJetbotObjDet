# isaacSimJetbotObjDet
Jupyter notebook implementation for a jetbot controller compacted in an object detection algorithm for Isaac Sim

isaac_sim_jetbot_objdet.ipynb - the script is meant to be used in connection with Isaac Sim simulator:
    It loads the scene with a cube, groundplane and the jetbot
    It activates the camera from the viewport
    It reads the camera image and process through the deep neural network already trained for basic shape objects
    
jetbot_objdet_v2.ipynb - is meant to work for a real jetbot equipped with a camera:
    It activates the camera from Jetbot class (Camera)
    It reads the camera image and process through the deep neural network
