## Purpose:  
To develop a reliable system to price art. Often in auctions, art pieces sell for well outside of the bounds experts give on the piece’s value. Knowing why or being able to predict when this will happen could provide more stability for art as an investment, and could help to protect parties when they put a piece up for auction.

## Questions:  
- Will a piece of art produce a positive or negative return? This would be a classification problem.
- What is the price of a piece of art? This could be answered through regression or clustering.
- Will a piece of art exceed or fall below estimates of its value when it goes to auction? This could be answered through a clustering or classification approach.
- Trends in art - does a piece of art sell for more, relative to other pieces in auction at that time, than it usually would? Relative to the investing landscape in general?

## Motivation:
Developing a reliable pricing system for art provides value to market participants by characterizing the risk they assume during their activities. By being more informed of the expected value and volatility of their investment, participants can make decisions that better suit their interests. There is substantial room for improvement in this area as auction price estimates have spreads of 10-30% of the mean estimated price, with the magnitude of these ranges in the tens to hundreds of thousands of dollars. Improving estimates for expected auction price or volatility, even a marginal amount, could represent significant monetary value. 
Also, the price of art can be influenced by personal sentiment or opinion. It can be difficult to objectively value art when emotionally invested in the art or artist, especially considering the uniqueness of artwork. By using a data driven approach, we can help inform participants of an objective estimate of the price in absence of a localized personal bias. This is important because artwork can be very expensive, and a poorly informed purchase can be financially very risky. Also, an objective pricing approach could be useful to evaluate estates when different parties have different personal attachments to the art.
    

## Data Desciption:  
The dataset provides records of auctions for artworks by 36 impressionist and contemporary artists. Each record includes information about the art price, the upper and lower bounds of what it had been estimated to sell for, as well as characteristics of the piece of art and the artist. This will allow for connections to be made between the sale price (output) and the characteristics of the piece of art and the time period in which it is being sold (features). The dataset has over 14,000 rows of data, each corresponding to a transaction. Regardless of the quality of the data, there should be sufficient information for training and testing predictive models on such an illiquid market as the art market.
