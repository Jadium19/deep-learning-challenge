# deep-learning-challenge

Bootcamp: UTA-VIRT-DATA-PT-04-2023-U-LOLC-MTTH

Code Files: 
  1. AlphabetSoupCharity.ipynb
  2. AlphabetSoupCharity.h5
  3. AlphabetSoupCharity_Optimization.ipynb
  4. AlphabetSoupCharity_Optimization.h5
  5. AlphabetSoupCharity_Optimization_v01.ipynb
  6. AlphabetSoupCharity_Optimization_v01.h5
  7. AlphabetSoupCharity_Optimization_v02.ipynb
  8. AlphabetSoupCharity_Optimization_v02.h5

  
## Program:
Alphabet Soup is a nonprofit foundation that provides funding for client ventures. Four versions of a binary classifier that predicts whether applicants will be successful if funded by Alphabet Soup was created in an attempt to provide an optimized model.

First attempt: AlphabetSoupCharity.h5
  1. Entity ID and Name removed.
  2. Dimensionality reduced for APPLICATION_TYPE and CLASSIFICATION features.
  3. Utilize two hidden layers. The input layer has 80 neurons and the second layer has 30 neurons with relu activation on both layers. The output layer has sigmoid activation.
  4. Result: loss: 0.5585 - accuracy: 0.7265 - epochs 100
  5. Loss Graph:
  6. ![image](https://github.com/CharlesQuinn1/deep-learning-challenge/assets/128498023/bb6d4c16-7f28-4ae9-a945-529201a2caae)

## First Optimization:
Model: AlphabetSoupCharity_Optimization.ipynb
Output: AlphabetSoupCharity_Optimization.h5
  1. Limit features to entity specific features. Features used APPLICATION_TYPE, AFFILIATION, ORGANIZATION, and ASK_AMT.
  2. Dimensionality reduced for all features.
  3. Utilize one hidden layer. The input layer has 16 neurons with relu activation. The output layer has sigmoid activation.
  4. Result: loss: 0.5726 - accuracy: 0.7230 - epochs 100
  5. Loss Graph:
  6. ![image](https://github.com/CharlesQuinn1/deep-learning-challenge/assets/128498023/68856e25-036e-4284-adfb-1a478f9ffba4)

## Second Optimization:
Model: AlphabetSoupCharity_Optimization_v01.ipynb
Output: AlphabetSoupCharity_Optimization_v01.h5

  1. Limit features to entity specific features. Features used APPLICATION_TYPE, AFFILIATION, ORGANIZATION, and ASK_AMT.
  2. Dimensionality reduced for all features.
  3. Utilize one hidden layer. The input layer has 32 neurons with relu activation. The output layer has sigmoid activation.
  4. Result: loss: 0.5725 - accuracy: 0.7241 - epochs 100
  5. Loss Graph:
  6. ![image](https://github.com/CharlesQuinn1/deep-learning-challenge/assets/128498023/b3625f83-159c-4f6f-b4ab-531e3a3e432b)

## Third Optimization:
Model: AlphabetSoupCharity_Optimization_v02.ipynb
Output: AlphabetSoupCharity_Optimization_v02.h5

  1. Limit features to entity specific features. Features used APPLICATION_TYPE, AFFILIATION, ORGANIZATION, and ASK_AMT.
  2. Dimensionality reduced for all features.
  3. Utilize two hidden layers. The input layer has 32 neurons with relu activation, the hidden layer has 32 neurons with relu activation, and the output layer has sigmoid activation.
  4. Result: loss: loss: 0.5712 - accuracy: 0.7247 - epochs 100
  5. Loss Graph:
  6. ![image](https://github.com/CharlesQuinn1/deep-learning-challenge/assets/128498023/8c013ccd-d689-4010-974e-c805d97da729)
