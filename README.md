# Sistemas-Fisicos-Interactivos
setcpm(4)
let melody1 = note ("[e4@2 f4@2 g4 g4 g4 g4 g4@2 c4 e4 d4 d4 d4 d4 d4@2 e4 d4 c4 c4 c4 c4 c4@2 b4 c5 b4@3 a4 e4@3 e4 f4 g4 g4 g4 g4 g4@2 c4 e4 d4 d4 d4 d4 d4@2 e4 d4 c4@2 g3 e4 f4 d4 c4 c4@3]").sound("piano").legato(1);

let melody2 = note ("[e5@2 f5@2 g5 g5 g5 g5 g5@2 c5 e5 d5 d5 d5 d5 d5@2 e5 d5 c5 c5 c5 c5 c5@2 b5 c6 b5@3 a5 e5@3 e5 f5 g5 g5 g5 g5 g5@2 c5 e5 d5 d5 d5 d5 d5@2 e5 d5 c5@2 g4 e5 f5 d5 c5 c5@3]").sound("gm_soprano_sax:3").legato(1);

let melody3 = note ("[e4@2 f4@2 g4 g4 g4 g4 g4@2 c4 e4 d4 d4 d4 d4 d4@2 e4 d4 c4 c4 c4 c4 c4@2 b4 c5 b4@3 a4 e4@3 e4 f4 g4 g4 g4 g4 g4@2 c4 e4 d4 d4 d4 d4 d4@2 e4 d4 c4@2 g3 e4 f4 d4 c4 c4@3]").sound("gm_acoustic_bass:3").legato(1);

let melody4 = note ("[e4@2 f4@2 g4 g4 g4 g4 g4@2 c4 e4 d4 d4 d4 d4 d4@2 e4 d4 c4 c4 c4 c4 c4@2 b4 c5 b4@3 a4 e4@3 e4 f4 g4 g4 g4 g4 g4@2 c4 e4 d4 d4 d4 d4 d4@2 e4 d4 c4@2 g3 e4 f4 d4 c4 c4@3]").sound("gm_steel_drums:4").legato(1);

$: melody1

$: melody2

$: melody3

$: melody4
