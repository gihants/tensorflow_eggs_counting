# eggs_counting

## annotation
1. put image files into the directory 'images'
2. run (from the master directory): python labelImg/labelImg.py
3. on GUI, set both images and output directories as 'images'
4. continue annotation with lables. For more details and help for installation please visit: https://github.com/tzutalin/labelImg

## creating tfrecords
## for training data:
python generate_tfrecord.py --csv_input=data/train_labels.csv  --output_path=data/train.record

### for testing data:
python generate_tfrecord.py --csv_input=data/test_labels.csv  --output_path=data/test.record

