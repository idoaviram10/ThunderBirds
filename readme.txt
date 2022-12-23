C++  ThunderBirds Ex 2
Ori Avitan 206589855
Ido Aviram 318599834
Bonus  additions:   Colors mode

Notes:
- Each ghost has a character that symbolizes it in the screen file. 
   But in the board printing, all the ghosts look the same - they are marked with the '%' character.

- All blocks are marked with a character between '1' and '9 '. 
  But this does not mean that different blocks must be marked with a different character.

- We used the Directory iterator and as a result, in order for the program to be compiled, 
   the "C++ Language Standard" should be "ISO C++ 17 Standard (std:c++17)" at least.
   You should change this in Project -> Properties -> General.

- If you want to edit a SCREEN file, open it using "Notepad" instead of a regular txt file.
  Then press Ctrl+a and then resize the text to 8.
  This will give you an accurate view of the board - so you can easily edit.

- Although written in instructions to run the file like this: "thunderbirds.exe -load | -save [-silent]",
  The name of our project is "ThunderBirds Ex3" so it should run like this: "thunderBirds Ex3.exe -load | -save [-silent]",
  Or just add the arguments through the visual studio itself.

- We used inheritance and polymorphism in the Ship, Block and Ghost classes.
   They inherit from the GameObject class.