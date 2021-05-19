# LSTM Stock Predictor

*by Arzu ISIK TOPBAS*

I used deep learning recurrent neural networks to model bitcoin closing prices. I used the FNG indicators to predict the closing price for one model while the second model, I used a window of closing prices to predict the nth closing price.
I evaluated each model and compared the performance.

### The Performance of each model
    I evaluated each model and compared the performance.
### LSTM Stock Predictor Using FNG
 
 * **Model Parameters**
   window_size = 10

   epoch_number = 200
     
 * **Model Summary**

   ![model.summary](https://github.com/arzuisiktopbas/11-LSTM_Stock_Predictor/blob/main/Images/FNG_model.summary.png)

 * **Performance**
 
   loss: 0.0769
   
   ![FNG](https://github.com/arzuisiktopbas/11-LSTM_Stock_Predictor/blob/main/Images/FNG.png)

### LSTM Stock Predictor Using Closing Prices
 
 * **Model Parameters**
   
   window_size = 10

   epoch_number = 200
     
 * **Model Summary**

   ![model.summary](https://github.com/arzuisiktopbas/11-LSTM_Stock_Predictor/blob/main/Images/Closing_model.summary.png)
   
 * **Performance**
 
   loss: 0.0134
   
   ![Closing](https://github.com/arzuisiktopbas/11-LSTM_Stock_Predictor/blob/main/Images/Close.png)


### Evaluate the performance of each model

* Which model has a lower loss? ---- Closing Prices

* Which model tracks the actual values better over time? ---- Closing Prices 

* Which window size works best for the model? ----- Window size of 3 would work best for both models.

- - -
