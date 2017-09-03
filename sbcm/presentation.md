(capa)


**title**:
Vivace: a collaborative live coding language and platform

**authors**:
 Vilson Vieira, Guilherme Lunhani, Geraldo Magela de Castro Rocha Junior,
 Caleb Mascarenhas Luporini, Daniel Penalva, Ricardo Fabbri and Renato Fabbri
 (Cod.ai, IPRJ/UERJ, ICMC/USP)

**event**:
Simpósio Brasileiro de Computação Musical - SBCM/2017
(Sep/3-6/2017)









============
(slide 1)


* Livecoding

* Vivace:
  - Domain Specific Language (DSL)
  - Interface
    * Web Audio API (Tone.js)
    * HTML 5 Video
    * Jison










===========
(slide 2)


Vivace is proposed as 
a simple to learn and use
livecoding language and environment:
* simple syntax and grammar
* runs on every popular browser

Also:
* built using the standards (Web Audio API and HTML 5)
* integrates audio and video
* full control/parametrization of audio nodes by language or UI










=============
(slide 3)



** "Hello world" in Vivace **

    a.signal = synth
    a.notes = [d4, e4, c4]
    a.notes = {1m}












===========
(slide 4)


** More elaborate examples **

    a.signal = synth => filter => reverb

    a.signal = sampler('./media/bass.wav') => reverb
    b.signal = video('./media/eyes.mp4')

    a.filter.frequency = [300, 450]
    a.filter.frequency = {4n, 8n}












============
(slide 5)


Using vivace on the fly.

(
on Heroku? locally? void.cc?
should anyone connect to it?
)








============
(slide 6)


Freak coding:
* hacky interface
* many coders including individuals from de audience
* monsters
* presentations
* Freakcoding manifesto (published)
* teratology/criptozoology







============
(slide 7)


** Conclusions and further work **


* Finish/polish/enhance the new vivace
  - Agree on what are the minimal constructions on the language
  - Find out if we have better solutions that using HTML 5 for video
* Maintain an online instance (github.io?)
* Make more performances


  Thanks! Questions?
| renato.fabbri@gmail.com |
| automata@void.cc        |
