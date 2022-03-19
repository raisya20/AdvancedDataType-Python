# AdvancedDataType-Python

  Advanced data type usualy use for array data. advanced data type divided to 4 kind of type. if we know characteristic for each advanced type data we can expolre more and exploit its characteristic to make our data clean from duplicated, cant't be changed and a lot other function

4 Kinds of Advaced Data Type

- LIST : A list is an ordered data structure with elements separated by a comma and enclosed within square brackets. ist is one of advanced type data used most cause its flexibility. this kind of data aslo allow us to place a dulicated value so useful for something like matrix in matematic

- TUPLE : The tuple data type is an immutable, ordered data type that allows you to store data in Python. Tuple usually use for data you dont wanto to change for example key dictionary

- DICTIONARY : Python's dictionaries are kind of hash table type. They work like associative arrays or hashes found in Perl and consist of key-value pairs. A dictionary key can be almost any Python type, but are usually numbers or strings. Values, on the other hand, can be any arbitrary Python object. Dictonary is use when we want to call value with keyword we already prepare cause usuallu dictionary use for group data with a lot data make hard to count its index if go with manual

- SET : set is an abstract data type that can store unique values, without any particular order. set usually use for matematic use or if we dont want duplicated value

Type Operation

1. Slicing is a way to take a part from group of data. slicing only possible in list, dictionary, and tupple with few rules
- only one index inside square bracket mean only call one data that place in that index
- to call more than one data use colon with detail (start data you want to take : end data you want to take +1 : step of the returned items)
- Blank in treat as default if blank in start data mean want to take data from the beginning , if blank in end data mean want to take data till the end of the group data and if blank in step mean that every first item will be returned in the result
2. Input data to array
- append function will add one data to group data in the end of group data with format inside parentheses (data you want to input)
- extend function will add another list data to list in the end of group data with format inside parentheses ([list you want to input])
- insert function will add one data to specific index with format inside parentheses (index, data you want input
3. Change a element inside array
- del function can remove elements by index from the list with the del statement.
- remove function can delete the first item from the list of values whose value is equal to the specified value by remove.
- pop is a function that removes the item at the specified index from the list. pop will remove the last value if it doesn't specify a value.
- x[index]= data we want to replace, replace element with slice data equal to new data to replace that slice data with new data
