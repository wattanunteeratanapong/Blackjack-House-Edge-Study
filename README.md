# Blackjack House Edge Study
![table_games_game_no_bust_blackjack_lg](https://github.com/user-attachments/assets/e8045eff-3e86-495b-bc19-4ab7518c2d02)
<br><br>
Have you ever wondered if the odds in Blackjack are really on the house's side? &nbsp;
Lets find out.<br>
<br>

## Overview 
Blakjack is a one of the most game that heavily relie on math, unlike most games that are just based on luck. This repo is all about figuring out which side has the edge. We are running 10 million simulations to get as close as we can to the theoratical probability.<br>
<br>

## Control Variable
- This experiment test 1v1 against dealer
- If player hand total value is lower than 17, player are gonna hit until it's more than 17 (most of the player are likely hit until their hand are higher than 17 then stop)
- Bet at the same amount every round 
- Using 6 deck of card, similar to a real casino
- Reset the deck after it is below 70% of total amount, similar to a real casino
- Test around 10 million round, the higher testing round the closer to theoratical probability
- Player didn't use any kind of technique like "Card Counting" or "Basic Strategy Chart"
- And there is no "Splitting" or "Doubling Down" in this experiment
<br>

## Traditional Rules of Blackjack <br>
1. If dealer hand total value are higher than 17, dealer can't hit anymore (player doesn't affect by this rule, player still be able to hit even if their hand is equal to 17 or higher) <br>
2. If dealer hand total value are lower than 17, dealer must hit no matter what (player doesn't affect by this rule, player could decide to stand without regard to their score) <br>
3. If player win by any mean they get back x2 their bet, but if they get blackjack they get back x2.5 their bet (some of a casino may use a different ratio of return payout) <br>
<br>

## Conclusion <br>
<img src="https://github.com/user-attachments/assets/96c9efbc-529f-4271-9569-3d8fb6a57426" width="100%" height="100%" alt="Image 1"> <br>
<img src="https://github.com/user-attachments/assets/deb0ae7a-15c4-4d80-878e-f2e3fe27c5c5" width="100%" height="100%" alt="Image 1"> <br>

From this experiment if player didn't having any kind of technique and go 1v1 against dealer, they are likely to lose. 
This game is design for a dealer to have more edge than a player. So if you wanna get rich from Blackjack, be a dealer.<br>
<br><br>

## Why blackjack odd are on the dealer side? <br>
If we take a look at the simulation we can see the busted ratio between player and dealer, player are busted more often than a dealer. 
This is because player have to hit before the dealer this is why they busted more often than dealer, player get busted before the dealer are actuallly play.
Because of this reason the longer they play, the more they likely lose their money.
<br><br>

## Disclaimer <br>
This experiment player didn't use any kind of technique like "Card Counting" or "Basic Strategy Chart". If player using any kind of technique they might be able turn an odd to their favor. <br>
<br>

## Future Direction <br>
In the future, I may explore techniques that could potentially turn the odd to my favor in Blackjack like "Card Counting" or "Basic Strategy Chart". <br>
<br>

## Source <br>
<a href="https://youtu.be/eyoh-Ku9TCI?si=7lreOZh8m4uysgaU">How to Play Blackjack | wikiHow</a>
<br>

<a href="https://youtu.be/PljDuynF-j0?si=GUkZF2RifbRJyifh"> How to Play (and Win) at Blackjack: The Expert's Guide</a>
<br>

<a href="https://www.techopedia.com/gambling-guides/blackjack-odds-probability"> Blackjack Odds Explained – House Edge and Payout</a>
<br>
