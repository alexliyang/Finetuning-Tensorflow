# Finetuning-Tensorflow
Fine tuning MobileNet for hand gestures recognition using tensorflow.

# Re-Training
python retrain.py --image_dir ./gestures-dataset --architecture mobilenet_1.0_224

# Classification-Test
python label_image.py --graph=/tmp/output_graph.pb --labels=/tmp/output_labels.txt --image=./gestures-dataset/SUBFOLDER_2/CLASS2_IMG2.jpg --input_layer=input --output_layer=final_result --input_mean=128 --input_std=128 --input_width=224 --input_height=224

# Dataset 
Thanks to Michal Kawulok, Tomasz Grzejszczak, Jakub Nalepa, Mateusz Knyc for hand posture database.
http://sun.aei.polsl.pl/~mkawulok/gestures/



