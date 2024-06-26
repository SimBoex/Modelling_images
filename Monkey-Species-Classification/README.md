# MonkeySpeciesClassification_FeatureExtraction-RandomForest
Here I  include  this classification project based on extracting features using a backbone (Vgg16) and passing them to a Random Forest classifier.

- The dataset is taken from [here](https://www.kaggle.com/datasets/slothkong/10-monkey-species/data)
-  When passing to a Vgg16, remember to transform from RGB to BGR (either explicitly or using the process_input function)

| Label | Latin Name             | Common Name               | Train Images | Validation Images |
|-------|------------------------|---------------------------|--------------|-------------------|
| n0    | alouatta_palliata      | mantled_howler            | 131          | 26                |
| n1    | erythrocebus_patas     | patas_monkey              | 139          | 28                |
| n2    | cacajao_calvus         | bald_uakari               | 137          | 27                |
| n3    | macaca_fuscata         | japanese_macaque          | 152          | 30                |
| n4    | cebuella_pygmea        | pygmy_marmoset            | 131          | 26                |
| n5    | cebus_capucinus        | white_headed_capuchin     | 141          | 28                |
| n6    | mico_argentatus        | silvery_marmoset          | 132          | 26                |
| n7    | saimiri_sciureus       | common_squirrel_monkey    | 142          | 28                |
| n8    | aotus_nigriceps        | black_headed_night_monkey | 133          | 27                |
| n9    | trachypithecus_johnii  | nilgiri_langur            | 132          | 26                |

- Clearly, this is a balanced dataset, but with few labelled instances for each class
