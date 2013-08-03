Kalah Gameboard is a software that implements an ancient board game called
Kalah or Mancala.

From Wikipedia (en.wikipedia.org/wiki/Kalah):
    
    The game requires a Kalah board and 36 - 72 seeds or stones. The board has 
    six small pits, called houses, on each side; and a big pit, called a Kalah 
    or store, at each end. 
    The object of the game is to capture more seeds than one's opponent.
    
    Rules.
    1. At the beginning of the game, three seeds are placed in each house.
    2. Each player controls the six houses and their seeds on his/her side of 
    the board. His/her score is the number of seeds in the store to his/her 
    right.
    3. Players take turns sowing their seeds. On a turn, the player removes 
    all seeds from one of the houses under his/her control. Moving 
    counter-clockwise, the player drops one seed in each house in turn, 
    including the player's own store but not his/her opponent's.
    4. If the last sown seed lands in the player's store, the player gets 
    an additional move. There is no limit on the number of moves a player can 
    make in his/her turn.
    5. If the last sown seed lands in an empty house owned by the player, and 
    the opposite house contains seeds, both the last seed and the opposite 
    seeds are captured and placed into the player's store.
    6. When one player no longer has any seeds in any of his/her houses, 
    the game ends. The other player moves all remaining seeds to his/her store, 
    and the player with the most seeds in his/her store wins.
    
    The game may vary with amount of initial seeds: 3, 4, 5, 6. The more seeds
    the more harder to play.

Tips of how to create your own gameplay method.

    To create your own search method that plays Kalah you should 
    create a method class that inherited from the Method class 
    (methods/method.py). You should place a new method's file to the methods
    folder. When you finished creating your method it will be accessible in the 
    Kalah options dialog window. For more details please refer a method template 
    in methods/method_template.py file and check examples in 
    methods/random.py and methods/minmax.py
    
Project structure

    
    
License agreement

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

Author information

    Oleksii Molchanovskyi
    National Technical University of Ukraine "Kyiv Polytechnic Institute"
    Kyiv, Ukraine
    E-mail: olexiim@gmail.com