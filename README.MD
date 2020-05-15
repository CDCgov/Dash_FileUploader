# Dash Demonstration of the File Uploader and Dynamic Populating Dropdown Menu

This Dash App reads the included mpg.csv file, and creates a "Column Name" drop down menu and a "Column Value" drop down menu generated dynamically from the the csv file. You can select the column name and value, and the output table will be subsetted to display only entries matching the column name and value combination.

The File Uploader is at the top of app. You can upload your own csv file, and the app will dynamically generate the drop down menus with options from your file. You can subset the table by selecting the menus as above. The iris.csv files are included in the repo for your convenience.

The mpg and iris dataset are download from the R dataset repository.

## Dependency and How to run
This code depends on Python3, dash, and pandas.

Run the code with the following command:
```
python3 app_file_loader.py
```

## Author
Jiangwei Yao

## Related Documents
* [Disclaimer](DISCLAIMER.md)
* [Contribution Notice](CONTRIBUTING.md)
* [License](LICENSE)
