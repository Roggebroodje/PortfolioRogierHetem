## Welcome to Rogier Hetem's portfolio

## [Project 1: Which webiste to bet?](https://github.com/Roggebroodje/betting_on_boxing_matches)
#### Where do you get the highest odds on your favourite boxing match? <br>
In this [webscraping project](https://github.com/Roggebroodje/betting_on_boxing_matches) I compared the betting odds from four different betting websites. I specifically looked at boxing events. I used selenium and bs4 to scrape the desired information from the different websites. Using selfmade functions I paired the corresponding boxing events from the different websites. Then comparing the different odds and selecting the highest per boxing event, per outcome ('boxer 1' wins or 'boxer 2' wins). A table is returned displaying all the upcoming boxing events, the highest odds per event with their respected website. See below for the first 5 rows of this outcome table. <br> 

The main packages I used were: bs4, selenium and pandas. I used the following four websites: [www.bwin.com](www.bwin.com), [www.jacks.nl](www.jacks.nl), [www.bet365.nl](www.bet365.nl) and [www.wallacebet.com](www.wallacebet.com). <br>

#### First 5 rows from the outcome table:
 | Date | Boxer 1 | Boxer 2 | Best odds boxer 1 | Odds 1 at | Best odds boxer 2 | Odds 2 at | 
 | ------ | ------ | ------ | ------ | ------ | ------ | ------ | 
 | 2/5/22 |  Chris Eubank Jnr  |   Liam Williams | 1.35 | jacks | 3.5 | bwin | 
 | 2/6/22 |  Keith Thurman  |   Mario Barrios | 1.57 | bwin | 2.4 | bwin | 
 | 2/12/22 |  Daniel Jacobs  |   John Ryder | 1.57 | bwin | 2.6 | jacks | 
 | 2/19/22 |  Kell Brook  |   Amir Khan | 1.6 | jacks | 2.38 | wallace | 
 | 2/26/22 |  Josh Taylor  |   Jack Catterall | 1.11 | bwin | 8.5 | jacks | 
 <sup> last update 01/31/2022 18:54 <sub>
