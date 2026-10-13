# The Meeples

Undergraduate research group from **De La Salle University, Manila** and **De La Salle University – Dasmariñas**.

Ralph Almarza   [@ralph-almarza](https://github.com/ralph-almarza)     <br>
Enrique Aragon   [@ena0553](https://github.com/ena0553)                 <br>
Stephen Borja    [@OutForMilks](https://github.com/OutForMilks)         <br>
Justin Ching     [@JustinChing30](https://github.com/JustinChing30)     <br>
Erin Chua        [@chua-e](https://github.com/chua-e)                   <br>

\* **Correspondence**. Talk to Stephen via [`stephen_borja_a@dlsu.edu.ph`](mailto:stephen_borja_a@dlsu.edu.ph). <br>
**Faculty Adviser**: Nathaniel Oco

## Research Project

Filipinos are among the world's heaviest social media users, with about 90.8 million social media user identities in the Philippines as of January 2025 (DataReportal, *Digital 2025: The Philippines*). Much of what they post mixes Filipino and English, a practice known as Taglish. Before an NLP system can analyze sentiment, detect hate speech, or translate this text, it first has to work out which language each word is in.

Tagging whole words as Filipino or English works reasonably well. The harder case is a single word that contains both languages. Filipino builds words by attaching prefixes, inserting infixes, and repeating syllables, and speakers apply these same rules to English roots: *nag-facebook* ("went on Facebook"), *ch‹in›eck* ("checked"), *nag-fa-facebook* ("keeps going on Facebook"). Existing tagging schemes handle these words poorly. Some put them in a catch-all "Other" category, some count them as Filipino, and the ones with a "mixed" label rarely predict it correctly.

There is also no large, public, hand-checked dataset that splits mixed Filipino-English words into their Filipino and English parts. This study aims to (1) measure how well existing tagging schemes and tools handle these mixed words, (2) build a hand-segmented corpus of Taglish words formed from Filipino affixes and English roots, and (3) develop a tagger that labels each word's language and splits mixed words into their Filipino and English parts.
