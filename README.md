# Depth-in-control

In this project, we enhanced image generation by integrating the Global-Local Path Network (GLPN) with an Edge
Detection Block (EDB) and ControlNet. We aimed to improve image quality by refining depth maps, using the method
from ”Mind The Edge: Refining Depth Edges in Sparsely-Supervised Monocular Depth Estimation.” Our approach
involved fine-tuning the GLPN model on the DDAD dataset to generate more accurate depth maps, which were then used
as control inputs for ControlNet. Despite significant improvements in depth map quality, the generated images did not
meet expectations. Future work will focus on optimizing model fine-tuning, preprocessing, and hyperparameter settings
to enhance image quality
