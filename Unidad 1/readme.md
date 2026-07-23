setcpm(4)

let sax = note ("[e5@2 f5@2 g5 g5 g5 g5 g5@2 c5 e5 d5 d5 d5 d5 d5@2 e5 d5 c5 c5 c5 c5 c5@2 b5 c6 b5@3 a5 e5@3 e5 f5 g5 g5 g5 g5 g5@2 c5 e5 d5 d5 d5 d5 d5@2 e5 d5 c5@2 g4 e5 f5 d5 c5 c5@3]")
  .sound("gm_soprano_sax:3")
  .legato(1)
  .gain(1)

let piano = note("[<e3 g3 b3> @4 <c3 e3 g3> @4 <a2 c3 e3> @4 <b2 d3 fs3> @4]")
   .sound("piano")
   .gain(0.5)

let strings = note("[e4@8 c4@8 a3@8 b3@8]")
  .sound("gm_string_ensemble_1:3")
  .gain(0.35)

let bass = note("[e2@4 e2@4 c2@4 c2@4 a1@4 a1@4 b1@4 b1@4]")
  .sound("gm_acoustic_bass:3")
  .gain(0.6)


stack(
  sax,
  piano,
  strings,
  bass
)
