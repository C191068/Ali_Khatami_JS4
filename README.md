# Ali_Khatami_Js4(Learning from the video of Dave Gray)

### Numbers

![j19](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/dc627031-86e1-425b-820c-3954dc930604)

here we will do the above <br>

Javascript considers both integers and floats to be number data types <br>

![j20](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/dbc6b082-9fac-4264-82cc-3f90aea044fa)

if after decimel there is no number except zero javascript will not show the decimel part <br>


![j21](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/e24279b4-aca3-452f-b8af-af6a9d3bd348)
If after decimel there is number other than ```0``` it will show it<br>


![j22](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/043dd6f4-39e1-4bb6-ae26-6573cefd2b5f)
Notice if we pass any number it will be shown in purple color <br>

![j23](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/327a142c-1ce7-4ceb-9fb9-ae62ed796bab)

If we pass only string it will show white color <br>


![j24](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/b475ae00-41c6-49cb-9e00-393ad0ba60f2)

if we don't give any number except zero after decimel palce at myFloat <br>
and then compare it with myNumber it wil return true <br>


![j26](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/faaad856-bf76-44ea-9412-bfcf26fba638)
code:

```

console.log(myString === myNumber);

```

Though mynumber and mystring looks equal but they are  different data type so the above will return false <br>




![j25](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/b24bba60-c677-4389-ad1f-b35265141971)
Code:

```
console.log(Number(myString));

```

we can change the string data type to number data type by the above <br>

thus the above output is shown in purple color <br>


![j27](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/5eedb750-e24b-496d-9291-6df11d711b9b)

now if we compare it will return true <br>

![j28](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/8f1f0d38-9244-4529-9f94-98b1fce0ac37)

If we want to convert a string that cannot be cconverted to number <br>

it will return NaN which means not a number <br>

![j29](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/3a2853bd-ab4c-47d8-a39b-97158332d4d0)

Boolean is different for true it will return 1 <br>



now we will talk about number methods <br>



![j30](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/e5857685-29f6-4512-9b20-e0c2d6ac279c)

Code:

```
console.log(Number.isInteger(myFloat));

```

The above tries to find if any number is integer or not <br>


![j31](https://github.com/C191068/Ali_Khatami_JS4/assets/89090776/0cff7475-10e7-4e47-8c2c-bc8f681234ef)


The parseFloat method parses the value pass to it and reeturns a floating point number <br>


the tofixedmethod() limits a floating point number <br>

to the number of decimels you provide as a parameter <br>















