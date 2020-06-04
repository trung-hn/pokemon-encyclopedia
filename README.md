### Click [here](http://bit.ly/pokemon_100) view all Pokemons in HTML format using http://htmlpreview.github.io

![image](https://user-images.githubusercontent.com/39042628/75634103-a1923a80-5bd8-11ea-8a97-7888985b9705.png)

A nonogram generator with the following features:
- no account created needed
- Can create account to save progress

- solving status:
    - has indication for which row we are on: https://webpbn.com/index.cgi?page=solving.html
    - check if it's correct
        - button
        - real-time
        - visually display where you are on the grid
    - left mouse cycle forward, right mouse cycle backward, mid mouse toggle
        - remember state when moving (to select multiple cells)
    - keyboard support:
        - `left`, `right`, `up`, `down` to move around
            - `ctrl` to move to the end like excel
            - `shift` to select while moving like excel
        - `q`, `e` to cycle color
        - space to enter color, 
        - number to select color
        - `c` to clear color on cell
        -  to toggle/cycle
    - a button to show the name of the puzzle
    - another button to show the original picture
    - Info:
        - Show number of moves
    - When solved:
        - Show image with full color (pop up)

- mobile support:
    - responsive UI

- seperate site (library/collection/gallery) to see pokemon sprite (pixel) upscaled (nearest neighbor)
    - There is a switch to hide/unhide pokemon (User might want to know the pokemon they are trying to solve)
    - Sorting features:
        - By Difficulties
        - By Col
    - Choosing a pokemon:
        - Pick number of color palette (4 to 15)
    - Show info:
        - name
        - generation

Sprites:
    - https://pokemondb.net/sprites
    - Save the data locally.
    - There is a link to show me a nonogram version of this. 
    
- domain: nonogramio.com

- preprocessing image for scaling:
    - Using Python for upscaling: https://pillow.readthedocs.io/en/stable/reference/Image.html


Future:
- database for existing puzzle.

- Create nonogram from image

- Share created nonogram
    - link with session.
- user profile to show process]

- REST API

Forum:
- https://www.reddit.com/r/Picross/
- https://www.reddit.com/r/nonograms/ 