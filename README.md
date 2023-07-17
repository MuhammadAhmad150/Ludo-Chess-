# Ludo-Chess-
Just create 3d Unity project and replace this Assets folder 
This is dynamic ludo or chess board made in unity. the dice button is pressed and player movement done . Currently i have made movement across the border only 

Attaching screenshots.
Add scenes to BuildSettings in the Assets>Scenez folder
16:9 Portrait aspect ratio Android version

U can work this on scene mode for changes. basically you jys have to to ensure topLeftPoint coordinates . work ths out as per as per your needs. 
U press dice, the player moves.
You may have to make it responsive.

IT WORKS PERFECTLY.

You can make it hoolow even.
 line 162////Foe Edges Bordersonly
                        // if(row==0 || row==rows-1 || col==0 || col==cols-1)
                        //     tile1.SetActive(true);
                        // else
                        //     tile1.SetActive(false);
//line166

lines-111-115
just uncomment these lines 111-115 , 162-165
code given. THIS WILLGIVE hollow board only borders
