# HAR-UML20

This repository contains the collected wearable data from 10 participants at University of Massachusetts Lowell. 

## Read the data
Dataset can be loaded in python script using read_dataset.py

```python
import read_dataset

path_to_dataset = "./" # Path to the folder containing the dataset
test_subject = "S10" # the subject to be used as test set [S1, S2, ..., S10]

# Get data in np.array format
[X_train, y_train, epochs, X_test, y_test, test_epochs, kcal_MET, test_kcal_MET] = read_dataset.main(path_to_dataset, test=test_subject)

```

## Visualization of the data
visualize_UML-HAR20.ipynb shows how to simply read the data.

## References

If this repository was useful for your research, please cite.

```
@ARTICLE{UML-HAR20,
  author={Barut, Onur and Zhou, Li and Luo, Yan},
  journal={IEEE Internet of Things Journal}, 
  title={Multitask LSTM Model for Human Activity Recognition and Intensity Estimation Using Wearable Sensor Data}, 
  year={2020},
  volume={7},
  number={9},
  pages={8760-8768},
  doi={10.1109/JIOT.2020.2996578}}
```
