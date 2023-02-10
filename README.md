# TIME_SLICE_DATABRICKS
SparkSQL implementation of Snowflake's TIME_SLICE function 


Calculates the start or ending of a 'slice' of time unit, where time unit can be a multiple of any of the following
(YEAR, QUARTER, MONTH, WEEK, DAY, HOUR, MINUTE, SECOND).

This Databricks Notebok contains two functions:
> 1. TIME_SLICE_DT : Takes input value/column as DATE datatype and returns DATE datatype, Can be used for (YEAR, QUARTER, MONTH, WEEK, DAY)
> 2. TIME_SLICE_TS : Takes input value/column as TIMESTAMP datatype and returns TIMESTAMP datatype, Can be used for (YEAR, QUARTER, MONTH, WEEK, DAY, HOUR, MINUTE, SECOND)


Reference : https://docs.snowflake.com/en/sql-reference/functions/time_slice.html
