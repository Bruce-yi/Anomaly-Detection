# Outlier analysis and anomaly detection

Using pyod tools to detect outlier in anomaly detection benchmarks

## Dataset  

[Anomaly Detection Meta-Analysis Benchmarks](https://ir.library.oregonstate.edu/concern/datasets/47429f155?locale=en)


## Tools

[Python Outlier Detection (PyOD)](https://github.com/yzhao062/pyod)

## Usage

you can simply clone this repository and run
```
jupyter notebook outlier_det_imgseg.ipynb/outlier_det_wine.ipynb
```

## Results

### imgseg results

There are imgseg/wine results, more detail can be found at results folder and jupyter notebook.

This is sample result, PCA+KNN performs best(roc 0.87) and PCA performs worst(roc 0.57)  
![sample_result](https://github.com/Bruce-yi/Anomaly-Detection/blob/master/results/imgseg/sample_benchmarks.JPG)  
This is all benchmarks result, KNN and LOF performs well in low anomaly rate but badly in high anomaly. On the contrast, PCA and LODA are more robust.  
![all_result](https://github.com/Bruce-yi/Anomaly-Detection/blob/master/results/imgseg/all_benchmarks.JPG)  

### wine results

This is sample result, also, PCA+KNN performs best(roc 0.87).  
![sample_result](https://github.com/Bruce-yi/Anomaly-Detection/blob/master/results/wine/sample_benchmarks.JPG)  
This is all benchmarks result, the trend of results of all models is consistent.  
![all_result](https://github.com/Bruce-yi/Anomaly-Detection/blob/master/results/wine/all_benchmarks.JPG)  


