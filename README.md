# PHP Loose Comparison Bug

This example demonstrates a common issue in PHP related to loose comparisons.  The function `bar` uses loose comparison (`==`), which can lead to unexpected results when comparing values of different types.  The function `foo` uses strict comparison (`===`), which avoids this problem.

Loose comparison (`==`) will attempt type juggling, while strict comparison (`===`) will only return true if the values are identical in both type and value.