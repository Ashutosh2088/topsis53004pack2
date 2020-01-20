topsis53004pack2 PACKAGE 
ISSUED UNDER THE MIT LICENSE
This is a package for python that implements the TOPSIS (The Technique for Order of Preference by Simmilarity to Ideal Solution ).
From the package import the file topsispack and call the function topsis(). It has three arguments
1)The dataset (.csv format)
2)Weights assigned to the features
3)Preferenc for each feature (+ if feature is desirable or needs to maximised or - otherwise)
e.g. python topsis "Data.csv" "1,2,3,4" "-,+,+,-"  (Command Line arguments)
or topsis("Data.csv", "1,2,3,4", "-,+,+,-")
The function outputs the selected matrix, the weights and the preferences along with the score assigned to each of the alternatives and the final choice
If you face any problems feel free to contact me :)