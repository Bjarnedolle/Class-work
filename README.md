Jeg har opsat filen launch.json for at aktivere vores debugger, samt taks.json så jeg kan run og build i vores progam.
Udover dette har jeg vores main.c, vores root source file, som er den grundlæggende fil.
For at løse problemstillingen af at skulle aktivere thrusterne i forskellige altitudes, har jeg benyttet et if else if system, samt vedhæftet et flowchart der beskriver dens sammenhæng.
For at gøre dette har vi beskrevet altitude og thrusters som en integer, hvor vi definere thrusters værdig til at være 0.
I tilfældet af at altitudes værdi er mellem 100 og 0, ændre vi så tilstanden på thrusterne, ergo skifter 0 til 1, så de aktiveres.
