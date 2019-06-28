For SSD calibration, tested with OpenVINO 2019 R1
DataSet : VOCtest_06-Nov-2007.tar
TestSet : <dataset_root>/VOC2007/ImageSets/Main/ssd_test.txt
command : python calibrate.py --config .\configs\ssd_voc.yml -M ..\..\model_optimizer --models ..\model_downloader\object_detection\common\ssd\512\caffe\models\VGGNet\VOC0712Plus\SSD_512x512\ --source C:\Users\cpai\Documents\DPD\OpenVINO\dataset\VOCtest_06-Nov-2007\VOCdevkit