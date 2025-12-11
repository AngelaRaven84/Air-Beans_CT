# Answers to the questions we will have from the seminar about AI-tools 11/12-2025 #


01 - 

ChatGPT has answers that goes in very much detail in every step.

If you choose ChatGPT the process of choosing a movie feels overwhelming. Aizo is more comprehensive in the answers. A guiding friend that works.


02 - 

ChatGPT:s structure of its answer is giving actual pseudocode, whereas Aizo is giving back a flowchart in text.
So ChatGPT is more technical and Aizo is more general.

Here is ChatGPT:s answer:

// 1. Ange humör
humor ← fråga_användare("Vilket humör är du på?")

// 2. Välj genre baserat på humör
genrelista ← föreslå_genrer(humor)
valda_genrer ← fråga_användare("Vilka av dessa genrer vill du se?", genrelista)

// 3. Bestäm praktiska begränsningar
max_tid ← fråga_användare("Hur lång film orkar du se (i minuter)?")
plattform ← fråga_användare("Vilken plattform använder du?")

// 4. Hämta kandidatfilmer
filmer ← hämta_filmer(plattform)
filmer ← filtrera(filmer, genre = valda_genrer)
filmer ← filtrera(filmer, längd ≤ max_tid)

// 5. Sortera filmer baserat på preferenser
sorterade_filmer ← sortera(filmer, efter = ["favoritregissör", "favoritskådespelare", "betyg"])

// 6. Välj toppalternativ
toppalternativ ← ta_första(sorterade_filmer, antal = 3)

// 7. Låt användaren se trailers
visa_trailers(toppalternativ)

// 8. Användaren gör val
vald_film ← fråga_användare("Vilken film vill du se?", toppalternativ)

// 9. Spara övriga filmer
spara_i_lista("Att se senare", toppalternativ - vald_film)

// 10. Visa slutligt val
skriv_ut("Du valde att se: " + vald_film)


03 - 

ChatGPT can get confused when you have several different types of files, that needs to be synchronized with eachother (context).
You have to be very specific to have a chance of an appropriate answer (which can be hard).

There are a whole bunch of defferent API:s, and it can be hard for AI to know which one is best for every given scenario.

Persons can have different approaches that all can work, but AI answers one thing, whereas in reality there can be many right answers (logic).
ChatGPT has learned from different peoples questions.


04 - 

They are pretty similar, but Aizo is giving us sentences. ChatGPT is giving us explanations in bullet points, with a summary at the bottom.


05 - 

Question 1 - There is at least some sort of validility in the code, which could be reason for the AI to think that if all it's other suggestions didnt work, then at least to initial one might be the better one.
Theory - Maybe it's starting to learn your code version after so many times seeing it, and suppose it can be a good one.
Maybe the AI is "hallucinating". And then you can get into a "feedback loop", and get stuck there =)

Question 2 - ChatGPT is learning from the questions being asked to it, and therefore learns old techniques if people are asking it about old techniques, and that way of solving their problems.
For example giving back old-style code, div:s.
