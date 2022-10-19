# Neural_Network_Charity_Analysis

## Overview

### Purpose

The purpose of this analysis was to help our friend Beks by creating a neural network capable of determining which applicants would return a successful result if they were funded by her company, Alphabet Soup.

## Results

### Pre-Processing

The target of our model is the IS_SUCCESSFUL variable, with the features being application type and classification. 

<img width="602" alt="image" src="https://user-images.githubusercontent.com/105998378/196593485-cd2faddb-98c9-4ef1-bf89-63c8da7d3caa.png">

<img width="487" alt="image" src="https://user-images.githubusercontent.com/105998378/196593321-1fff9883-f891-48d5-93ca-c85b8ce5455f.png">

<img width="476" alt="image" src="https://user-images.githubusercontent.com/105998378/196593352-1035e0e9-382c-488a-9dfb-ad77aa1aab43.png">

Columns EIN and NAME were neither features nor targets and so they had to be removed.

<img width="469" alt="image" src="https://user-images.githubusercontent.com/105998378/196593418-2e81d269-8412-4148-8ea1-cb41dd211e25.png">

### Compiling, Training, Evaluating

At first I tried to brute force the results by using a large amount of neurons in two layers.

<img width="662" alt="image" src="https://user-images.githubusercontent.com/105998378/196593730-376c1dd4-691b-4768-a987-712bcfc114db.png">

Then I tried to change up the activations and added another layer.

<img width="709" alt="image" src="https://user-images.githubusercontent.com/105998378/196593805-a4f964e8-674d-48ab-9443-0ad19bec7c49.png">

And finally I tried to alternate the activations while adding in yet another hidden layer.

<img width="731" alt="image" src="https://user-images.githubusercontent.com/105998378/196593885-d737e220-2493-4463-9693-9b952dc1b8c9.png">

None of these got me over the 75% accuracy mark.

## Summary

### Conclusion

I've learned that adding hidden layers and neurons is not always the best way to get the results that you desire. Additionally, different activations won't necessarily fix a situation either. I believe that if I had taken the time to bucket other items better that I may have achievedthe results that I wanted. 
