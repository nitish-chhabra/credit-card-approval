# Finding the people who should be approved for a loan

This is a case study where ABC Payments Bank wants to give out digital credit cards to its customers. It also wants to analyze what should be the credit approved for each person. The detailed case study is explained in the Data Science Problem - ABC Payments Bank as a pdf.

## Requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following packages.

```bash
pip3 install lux pyforest scipy sklearn lazypredict
pip3 install scikit-learn==0.23
pip3 install pandas-profiling[notebook]
```


## Data Insights

- This does not have any information on Default!  
The model will only be dependent on past approvals which will re-propagate any errors/bias that are prevalent in the current system


- 24.8% approval rate
- Gender - 67.5% Male, 32.5% Female users
- date of birth is date need to convert to age
- 73.7% Private Job, Rest small chunks
- Only 5.6% have masters, rest 16.7% bachelors, 32.7% only till high school and 21.9% some college
- education_num has issues where most data is in 9,10,13  - 71.3%
- 91.6% had no capital gain
- asset_class_cd has lots of missing values
- Bucketing is required in - capital gain, capital loss, hours per week, 

## License
[MIT](https://choosealicense.com/licenses/mit/)