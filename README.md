# DevTest1

Used StringBuilder instead of string to append strings because when we use string type, for every string concatenation a new string object is created in memory and the old string is destroyed. This is a costly operation. String are immutable which means a string once created cannot be altered in memory. A copy of it is created with the new changes.
