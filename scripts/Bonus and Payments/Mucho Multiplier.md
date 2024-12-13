### Description
Verify that the Mucho Multiplier increases by one level each time a winning combination occurs or an Explosivo Wild symbol appears, up to the defined maximum multiplier level.

### Pre-Conditions
- The game (Main game or Bonus game) is loaded and running.
- The Mucho Multiplier is displayed below the game reels.
- The maximum multiplier level is defined and known.

### Post-Conditions
- Each win or Explosivo Wild appearance should increment the multiplier by one level.
- The multiplier should not exceed its maximum defined level.
- The updated multiplier value should be visibly reflected below the reels.

### Steps
Given the game is loaded and the Mucho Multiplier is visible below the reels  
When the player achieves a winning combination or an Explosivo Wild symbol appears  
Then the Mucho Multiplier should increase by one level  
And if the multiplier has not reached the maximum level, it continues to increase accordingly with subsequent wins or Explosivo Wild appearances  
And if the multiplier reaches its maximum level, it should not increase further  
And the final multiplier value should be correctly displayed to the player.
