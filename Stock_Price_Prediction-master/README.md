# Stock_Price_Prediction

Stock market analysis has attracted lots of research interests in the literature. Recent studies have shown that Machine learning algorithm achieved better performance than traditional statistical methods.

We used LSTM as a benchmark and obtained prediction accuracy around 99.2% for the integrated aproach of SVM for the TATA Global markets. However, only slight improvement of SVM was observed.

The algorithm of choice here is the LSTM (Long-Short term memory) network. It's a type of recurrent network that has proved very successful on a number of problems given its capability to distinguish between recent and early examples by giving different weights for each while forgetting memory it considers irrelevant to predict the next output. In that way, it is more capable to handle long sequences of input when compared to other recurrent neural networks that are only able to memorize short sequences.

# LSTM has three gates:
• The input gate: The input gate adds information to the cell state
• The forget gate: It removes the information that is no longer required by the model
• The output gate: Output Gate at LSTM selects the information to be shown as output

# Result
The LSTM model can be tuned for various parameters such as changing the number of LSTM layers, adding dropout value or increasing the number of epochs. But are the predictions from LSTM enough to identify whether the stock price will increase or decrease? It's a probability.


# REFERENCE
[1] E. F. Fama and B. G. Malkiel, “Efficient capital markets: Areview of theory and empirical work,”The Journal of Finance,vol. 25, no. 2, pp. 383–417, 1970. [Online]. Available: http://dx.doi.org/10.1111/j.1540-6261.1970.tb00518.x
[2] B. G. Malkiel, A Random Walk Down Wall Street. Norton, New York,1973.
[3] A. E. Biondo, A. Pluchino, A. Rapisarda, and D. Helbing, “Are Random Trading Strategies More Successful than Technical Ones?” PLoS ONE, vol. 8, p. e68344, Jul. 2013.
[4] A. Lo and A. MacKinlay, A non-random walk down WallStreet.Princeton, NJ [u.a.]: Princeton Univ. Press, 1999. [Online].Available: http://gso.gbv.de/DB=2.1/CMD?ACT=SRCHA&SRT=YOP&IKT=1016&TRM=ppn+249613484&sourceid=fbwbibsonomy
