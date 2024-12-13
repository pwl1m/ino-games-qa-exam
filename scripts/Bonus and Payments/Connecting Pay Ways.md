### Description
Verify that symbols aligned from the far left to the right on adjacent reels correctly trigger payouts according to the 99-ways system, ensuring that only the highest-paying combination per connecting pay way is awarded.

### Pre-Conditions
- The slot game is loaded and configured with 99 connecting pay ways.
- The pay table is available and outlines the symbol values and combinations.
- The reels spin and stop, displaying multiple symbols in sequence from left to right.

### Post-Conditions
- Symbols forming a valid sequence from far left to right on adjacent reels should pay out according to the pay table.
- Only the highest-paying combination for each connecting pay way is awarded.
- Non-adjacent symbols or those not forming a valid left-to-right sequence should not trigger a payout.

### Steps
Given the game is loaded with 99 connecting pay ways and a known pay table  
When the player initiates a spin and the reels stop with symbols aligned from the far left to right  
Then the system should identify all valid adjacent combinations along the 99 pay ways  
And it should determine the highest-paying win per connecting pay way based on the pay table  
And only these highest wins should be awarded, ignoring lower-paying combinations that share the same sequence  
And the final payout should be displayed accurately to the player.
