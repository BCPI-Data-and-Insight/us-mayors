us-mayors
=========

Download and parse data about mayors of cities in the United States.


## Data Source
[US Conference of Mayors (Meet the Mayor)](https://www.usmayors.org/mayors/meet-the-mayors/)
- Type in state name to get list of mayor in the state.

## Steps to Run
Use help to see the variable options
```
python mayors.py --help
```

Example to run all states to output.csv
```
python mayors.py output.csv --format csv 
```

Example with Alaska and Colorado in csv format to file called output.csv
```
python mayors.py output.csv --state AK CO --format csv 
```

### Formats
1. csv
2. json

## Requirements
 * cssselect
 * lxml
 * requests
 * pandas
 * tqdm
