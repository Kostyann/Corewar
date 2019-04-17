# Corewar
Final project in algorithmic branch. This project required a group to create:

1) a "champion" in pseudo assembly language;
2) an assembler which translates a champion`s code into byte-code;
3) and finally a virtual machine ("battlefield") with vizualisation, where champions are gonna fight for dominance.

The project is inspired by the original CoreWar from 1984: https://en.wikipedia.org/wiki/Core_War 

# Subject
https://github.com/Kostyann/Corewar/blob/master/Subject/corewar.en.pdf
https://github.com/Kostyann/Corewar/blob/master/Subject/resources_corewar.en.pdf
# Usage
make

./asm Banana_killer_v2.s && ./corewar -vizo Banana_killer_v2.cor vm_champs/champs/Gagnant.cor
