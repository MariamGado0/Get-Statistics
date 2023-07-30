# Get-Statistics
# Get Statistics

- **_A function that takes in a list of numbers and returns a dictionary containing the following statistics about the numbers: the mean, median, mode, sample variance, sample standard deviation, and 95% confidence interval for the mean._**

**_Note that:_**

• **_Can assume that the given list contains a large-enough number of samples from a population to use a z-score of 1.96_**

• **_If there's more than one mode, The function can return any of them._**

• **_Shouldn't use any libraries._**

• **_Output values will automatically be rounded to the fourth decimal._**

- Sample Input:
     - `input_list = [2, 1, 3, 4, 4, 5, 6, 7]`
- Sample Output:
`
{
"mean": 4.0,
"median": 4.0, "mode": 4.0,
"sample_variance": 4.0,
"sample_standard_deviation": 2.0,
"mean_confidence_interval": [2.6141, 5.3859], 
}`

## Usage

`python`

