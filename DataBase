/* Marlene Azevedo */
/*CRUD (Create Read Update Delate)*/

/* Create the table with the coloumns */
create table Game_Score (id varchar(100), 
                Pieces_Remain varchar(100), 
                Made_Kings integer, 
                Kings_Lost integer, 
                Outcome_of_Game varchar(100),
                Player_Color varchar(25) 
                );

/* Display the Table Name */
SHOW TABLES;

/* Add the values to the table. Leave some blank to input values in it later */
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('1_First Game', 3, 2, 0, 'Win','');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('2_Second Game', 7, 1, 1, 'Lost', 'White');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('3_Third Game', 5, 2, 1, 'Win', 'Black');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('4_Fourth Game', 4, 1, 0, 'Lost', '');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('5_Fifth Game',1, 2, 1, 'Lost', 'Black');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('6_Sixth Game', 6, 0, 0,'Win', 'White');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('7_Seventh Game', 4, 1, 0, 'Lost', 'Black');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('8_Eight Game', 3, 3, 1, 'Win', 'Black');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('9_Nineth Game', 6, 0, 0, 'Win', '');
insert into Game_Score(id, Pieces_Remain, Made_Kings, Kings_Lost, Outcome_of_Game, Player_Color) values('10_Tenth Game', 5, 1, 0, 'Lost', 'White');

SELECT * FROM Game_Score;
SHOW TABLES;



/*UPDATE*/
/* UPDATE the table with the following set values. These sections are empty so it will add 'Black' color in specific ID's where there are 3 remaining pieces */
UPDATE Game_Score SET Player_Color = 'Black' WHERE Pieces_Remain = 3; 
UPDATE Game_Score SET Player_Color = 'White' WHERE id = '4_Fourth Game';
UPDATE Game_Score SET Player_Color = 'White' WHERE id = '9_Nineth Game';
SELECT * FROM Game_Score;
/* Display the Table Name to divide the table results. */
SHOW TABLES;


/*READ*/
/* Read only the Columns where the player lost 1 king */
SELECT * FROM Game_Score WHERE Kings_Lost = 1;   /* <-- WORKS */
/*SELECT * FROM Game_Score;*/
SHOW TABLES;



/*DELETE*/ 
/* Delete scores where there are 5 or more pieces left on the board or where the player color is white*/
DELETE FROM Game_Score WHERE Pieces_Remain >= 5 OR Player_Color = 'White';
SELECT * FROM Game_Score;





