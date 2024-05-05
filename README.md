# Tips
Descripton <br>

# Ghost
**Example** <br>
<img src="mainTable.png"> <br>

**Sample Usage** <br>
```python
If(D3="","",If(D3>=80%,"Approved","Disapproved"))
```

**Syntax** <br>
```python
If(value1,value2,If(value3,value4,value5))
```
* **value1:** the initial value is being compared to an empty value. <br>
* **value2:** if the initial value is blank, then the field will remain blank. <br>
* **value3:** the value entered in the 'Test' column is compared to 80%. <br>
* **value4:** if the value3 is greater than or equal to 80%, then the field will display the word 'Approved'. <br>
* **value5:** if the value3 is less than 80%, then the field will display the word 'Disapproved'. <br>

> [!NOTE]
> These steps outline a process of evaluating and classifying data points based on predefined criteria, providing a clear understanding of the status or outcome associated with each value within the data processing system.
