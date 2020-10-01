# TOPSIS-53004 PACKAGE 
<br>
    ISSUED UNDER THE MIT LICENSE

```
This is a package for python that implements the TOPSIS 
(The Technique for Order of Preference by Simmilarity to Ideal Solution).
```

  It contains a single function "topsis" that takes three arguments
| S.No. | Inputs                                                                                      |
| ----- | --------------------------------------------------------------------------------------------|
| 1     | The dataset (.csv format)                                                                   |
| 2     | Weights assigned to the features                                                            |
| 3     | Preferenc for each feature (+ if feature is desirable or needs to maximised or - otherwise) |

### Example
```
python topsis "Data.csv" "1,2,3,4" "-,+,+,-"  (Command Line arguments)
or topsis("Data.csv", "1,2,3,4", "-,+,+,-")
```
The function outputs the selected matrix, the weights and the preferences along with the score assigned to each of the alternatives and the final choice
If you face any problems feel free to contact me :)
