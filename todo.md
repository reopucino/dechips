- testing player collide sama wall
- checking box saat maju apakah ada tembok / penghalang? (looping 1x)
- checking trigger box saat box ke isi di posisinya (buat open map)

done:
- cabut player movement (maunya movement di atur di game controller)
- move player dari game controller
- testing player collide sama box
- majuin box saat player collide


RULES
1. WHEN PLAYER (REAL MAN) DO INPUT UPDATE THE BOARD
2. SIMULATION MOVEMENT
3. DONE

**SIMULATION MOVEMENT**
PREDICT PLAYER MOVE FIRST
IS PLAYER COLLIDE? 
    YES, 
        POSSIBLE MOVE THE OBJECT? 
            YES, 
                OBJECT MOVE.
                PLAYER MOVE
            NO
                DO NOTHING
    NO
        MOVE PLAYER

RULES SEND MESSAGE OBJ MOVEMENT
1. MOVE FIRST
2. CHECK CURRENT POSITION IS EMPTY OR NOT
2a. empty = DONE
2b. not empty
    2bi. wall = move back
    2bii. object = (do point 1 loop-1)


other rules
1. possible move?
2. move
2. not move
3. not move is wall
3. not move is object
4. object move first