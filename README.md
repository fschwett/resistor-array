# Resistor array

## Idea:

I wanted to have a resistor array for test purposes. After seeing extremely expensive ones online I decided to create my own. My plan was to order it along with other PCBs, but that didn't end up happening.

## Concept:

An array of resistors which can be added to or removed from the total resistance. I wanted to order five PCBs to be able to play around with values more freely and be able to for example coordinate two resistances. I went with the classic 1, 2, 3, 4 design most of these arrays use. This means I have 1 Ω, 10 Ω, 100 Ω, 1 kΩ, 10 kΩ, 100 kΩ and 1 MΩ, then 2 Ω, 20 Ω and so on. This let's me get any nominal value from 0 Ω to 11.111.110 Ω.

## Implementation:

I had some SMD SPDT slide switches laying around. I chose SMD, because it would give the PCB a clean back. THT could've made contact with other parts and could've ended up shorting the whole thing. For some of the values I had to comine resistors, because I didn't have the right ones or they simple weren't part of the e series. I also used SMD resistors. This had the disadvantage of a low power rating though. Mine are .25 W 1% resistors. Unfortunately I don't know the temperature coefficient of these resistors, but I assume it's between 100 ppm and 200 ppm.

That's the actual design:

<img width="480" height="496" alt="image" src="https://github.com/user-attachments/assets/0fd089bc-69c0-45a5-be11-b8731cd3a482" />
