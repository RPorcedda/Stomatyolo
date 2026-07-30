# Stomatyolo
Reproducibility material for the paper "AI-enabled simultaneous phenotyping of leaf vein and stomatal traits uncovers independent genetic control in maize".

yolov8_obb_STOMATA.ipynb fine-tunes YOLOv8n-obb for stomata detection and produces the final detection dataset.
MAGIC_Leaf_Veins.ipynb extracts the lengths of veins and bundles in each image.
Cluster&Regress.ipynb puts together the results from the other notebooks to obtain the stomatal spatial distribution measures.
