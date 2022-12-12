# Baccarat-Game
1. Technology: Html, Css, JS
2. UI design: https://www.figma.com/file/a5vpSxpmwq6F2uGN1mpvCn/Untitled?node-id=0%3A1&t=sKUmFHt298oBt8I3-1
3. Basic logic:
a) When click "next play" button, it will first clear the cards from last play and then draw cards automatically, setInternal like half second, use logic to check whether to draw. We have the full rules. Then popup Player/Banker wins, and show the circle on left
b) Have 52 images for 52 cards like what we did with android final. use 8 decks. so we have an array which holds 416 numbers. 1-8 represent one same card, 9-16 represent one same card, so on. Get random from the array and show the card in the placeholder, then remove the element from the array

4. Functions needed:
  onePlay(){
	  do{
      playerDraw();
      bankerDraw();
    } while (nextDraw())
  }
  
Boolean nextDraw()    //baccarat rules here

playerDraw()

bankerDraw()

resetGame()
