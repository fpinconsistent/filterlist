# Filter list containing Spatial Inconsistenices for FP-Inconsistent
This repository hosts the filter list containing filter rules using FP-Inconsistent algorithm. The filter list is of the following format:
```first_feature|$$|first_feature_value|$$|second_feature|$$|second_feature_value|$$|eval_qualifier```

Where:

- ```first_feature```: is the name of the first feature
- ```first_feature_value:``` is the value of the first feature
- ```second_feature:``` is the name of the second feature
- ```second_feature_value:``` is the name of the second feature
- ```eval_qualifier:``` is the qualifier used during evaluation. It can only have a value of either ```allow``` or ```block```. If this is set as ```allow```, only the requests where both first feature value and second feature value match will be allowed and all others will be blocked. While, if this is set as ```block```, only the requests where the first feature value and the second value feature match will be blocked, and rest will be allowed.
