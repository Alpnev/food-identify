# Project Name AI Rhar identifies pics of food

The Ai is made to identify diffrent foods

(https://github.com/Alpnev/food-identify/assets/141777906/cce2fdd7-4b40-4f64-a203-b3a682d1a2d7)



## The Algorithm

The algorithm trains by looking at images of food and matching them with the file name that they are grouped in

python3 train.py --model-dir=models/food11 data/food11

imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/cheesecake/[input file] [output file]



1. enter your docker using ./docker/run.sh
2. from inside the docker run this command cd python/training/classification/
3. then run this command to run your testing imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/cheesecake/[input file] [output file]
4. 
[View a video explanation here]([video link](https://youtu.be/wEpcCA-oV9E)https://youtu.be/wEpcCA-oV9E)
