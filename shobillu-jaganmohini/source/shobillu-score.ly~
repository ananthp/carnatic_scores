\version "2.12.3"
\include "carnatic/melam/15_mayamalavagowla.ly"


\header {
  title = "Shobhillu Saptaswara (Kriti)"
  subtitle = "Jaganmohini"
  composer = "St. Tyagaraja"
  arranger = "arr. Ananth"
  meter = "Rupaka Thalam" 
  %Feb 2, 2011
  copyright = "© 2011 Ananth, beautifulnote.com   Creative Commons License: BY-NC-SA 3.0"
}


global = {
  \time 6/8
}

murchana = \new Staff \with {\remove Time_signature_engraver 
  instrumentName = "Murchana" }
\relative sa' {
  %Scale
  
  \cadenzaOn
  
  \grace {<<sa pa' sa>>} sa,8\([ ga ma pa ni  ] sa1\)
  sa8\([ ni pa ma ga ri ] sa1\) 
  \cadenzaOff
  
} \addlyrics { s g m p n s s n p m g r s }


pallavi = \relative sa' {
  \global
  #(set-paper-size "a4")
 

  ga4. ri8( sa)  ni | sa4 ga ma8 ma |
  ga4. pa16( ma ga ri) sa( ni) | sa4 ga ma8 ma | \break
  
  ga16( ma pa ma ga ma) pa( ma ga ri) sa( ni) | sa4 ga ma8 ma
  ga16( ma pa ni pa ma) pa( ma ga ri) sa( ni) | sa4 ga ma8 ma \break
  
  ga16( ma pa ni sa ni) pa( ma ga ri) sa( ni) | sa( ga ma8) ga16( ma pa8) ma16( pa) ni8 \break

  
  
  sa16( ni pa ma ga ma) pa( ma ga ri sa) ni |  sa( ga ma pa32 ma) ga16( ma pa ni32 pa) ma16( pa) ni8
  sa8.( ri16) sa( ni) pa8 pa ma | ga16( ma pa8) ma16( pa) ni8 pa16 ni sa( ri) | \break
  
  sa16( ni pa ma ga ma) pa( ma ga ri sa) ni  |  sa( ga ma pa32 ma) ga16( ma pa ni32 pa) ma16( pa) ni8
  pa16( ni sa8) ga ri16( sa) ni( pa) ma8 | ga16( ma pa32 ni pa16) ma( pa) ni32( sa ni16) pa ni sa( ri) | \break
  
  sa16( ri32 sa ni16 sa32 ni) pa16( ni32 pa ma16 pa32 ma) ga16( ri sa ni) |  sa4 ga4. ma8 | ga2. |s2. \break||
  
   
  
} \addlyrics {
  Sho bhil lu sa pta swa ra
  Sho bhil lu sa pta swa ra 
  Sho bhil lu sa pta swa ra 
  Sho bhil lu sa pta swa ra 
  Sho bhil lu sa pta swa ra 
  Sho bhil lu sa pta swa ra  Sun da ru la bha jim pa ve ma na sa
  Sho bhil lu sa pta swa ra  Sun da ru la bha jim pa ve ma na sa
  Sho bhil lu sa pta swa ra 
  }


anupallavi = \relative sa' {
  \global
  
  
} \addlyrics {
}

charanam = \relative sa' {
  \global
  
  
} \addlyrics {
}





\markup "Jaganmohini: 15th Mela Janyam"
\score { \murchana }
\score {\new Staff \with {instrumentName="Pallavi" }\pallavi \layout{} \midi{} }
