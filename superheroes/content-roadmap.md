# Content Roadmap

The Content Roadmap is a living document with **goals** **and** **sub-goals** **for each session**, helping us keep the big picture clear.

<details>

<summary><mark style="color:red;"><strong>Week 1:</strong></mark> 💡 Hallo, imagiCharm! · Hello, imagiCharm!</summary>

<mark style="color:$info;">**🎯**</mark>**&#x20;Ziele · Goals**

<mark style="color:$info;">Am Ende dieser Stunde können die Schüler\*innen ihren imagiCharm einschalten, die App öffnen und ihr erstes Pixel zum Leuchten bringen!</mark>

<mark style="color:$info;">By the end of this session the students can turn on their imagiCharm, open the app, and light up their first pixel!</mark>

***

**🔥 Aufwärmen — Compute-it · Warm-Up — Compute-it**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

Der/die Lehrer/in ist ein Roboter. Die Schüler\*innen müssen dem Roboter Schritt für Schritt Anweisungen geben um ein Quadrat zu Zeichnen. Dazu gibt jede/r Schüler/in der Reihe nach genau eine Anweisung und nennt davor seinen/ihren Namen und sein/ihr Alter. Danach geht ihr in die Besprechung: Warum war das so schwer? Nur ein kleiner Fehler, führt schon zu Problemen.

* Öffne compute-it.toxicode.fr auf deinem Bildschirm und spiele Level 1 gemeinsam als Klasse.
* Folge den Pfeilen und verfolge, was der Computer Schritt für Schritt tut.
* Frage: 'Was macht ein Computer eigentlich?' — er folgt Anweisungen, eine nach der anderen!
* Genau das macht Python auch — es liest deinen Code Zeile für Zeile, von oben nach unten.

🇬🇧 <mark style="color:$info;">English</mark>

The teacher is a robot. The students have to give the robot step by step instructions in order to draw a square. To do this/ every student has one turn in order. In their turn, they should say their name, age and give exactly one instruction. Afterwards, you discuss what happened. Why was this so difficult? Just one small mistake can cause big problems.

* Open compute-it.toxicode.fr on your screen and play Level 1 together as a class.
* Follow the arrows and trace what the computer does step by step.
* Ask: 'What does a computer actually DO?' — it follows instructions one at a time!
* This is exactly what Python does — it reads your code line by line, top to bottom.

***

**📖 Theorie — Was ist Python & imagiCharm? · Theory — What is Python & imagiCharm?**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Python ist eine echte Programmiersprache, die von Wissenschaftlern, Spieleentwicklern und sogar der NASA genutzt wird!
* Der imagiCharm ist ein 8×8-Raster aus 64 kleinen farbigen LEDs. Jede LED hat eine Position: Spalte (x) und Zeile (y), beide von 0 bis 7.
* Wir schreiben Python-Code in der imagi Edu App → sie sendet den Code via Bluetooth zum Charm → die Lichter gehen an!
* Die wichtigste Zeile: m\[x]\[y] = FARBE — x ist die Spalte (links→rechts) und y ist die Zeile (oben→unten).
* Eingebaute Farbkürzel: R = Rot, G = Grün, B = Blau, Y = Gelb, O = Orange, W = Weiß, K = Schwarz (aus).
* Für jede eigene Farbe benutze ein Tupel aus drei Zahlen (Rot, Grün, Blau) — jede von 0 bis 255. Beispiel: (255, 100, 0) = Orange.

<mark style="color:$info;">🇬🇧 English</mark>

* Python is a real programming language used by scientists, game makers, and even NASA!
* The imagiCharm is an 8×8 grid of 64 tiny coloured LEDs. Each LED has a position: column (x) and row (y), both from 0 to 7.
* We write Python code in the imagi Edu app → it sends the code to the charm via Bluetooth → the lights turn on!
* The key line: m\[x]\[y] = COLOR — where x is the column (left→right) and y is the row (top→bottom).
* Built-in colour shortcuts: R = red, G = green, B = blue, Y = yellow, O = orange, W = white, K = black (off).
* For any custom colour, use a tuple of three numbers (Red, Green, Blue) — each from 0 to 255. Example: (255, 100, 0) = orange.

💻 <mark style="color:$info;">Code</mark>

```
# Light up a red pixel at column 3, row 3
m[3][3] = R

# Light up a blue pixel at column 7, row 0
m[7][0] = B

# Custom colour using (Red, Green, Blue) numbers
m[0][0] = (255, 100, 0)   # orange
```

***

**💻 Übung — Pixel-Kunst · Exercise — Pixel Art**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Schritt 1 (5 Min): Öffne die imagi Edu App und verbinde deinen imagiCharm via Bluetooth.
* Schritt 2 (10 Min): Tippe den Beispielcode oben ein und führe ihn aus — schau, wie die Pixel aufleuchten! Versuche R in G oder B zu ändern.
* Schritt 3 (15 Min): Zeichne deine Initialen ODER ein Smiley-Gesicht mit m\[x]\[y] = FARBE Zeilen. Benutze mindestens 5 Pixel!
* Tipp: Skizziere dein Design zuerst auf Millimeterpapier — zeichne ein 8×8-Raster und färbe die Felder, die du zum Leuchten bringen möchtest.
* Herausforderung: Kannst du eine Herzform machen? (Hinweis: es braucht etwa 10 Pixel!)

🇬🇧 <mark style="color:$info;">English</mark>

* Step 1 (5 min): Open the imagi Edu app and connect your imagiCharm via Bluetooth.
* Step 2 (10 min): Type the example code above and run it — watch the pixels light up! Try changing R to G or B.
* Step 3 (15 min): Draw your initials OR a smiley face using m\[x]\[y] = COLOR lines. Use at least 5 pixels!
* Tip: Sketch your design on graph paper first — draw an 8×8 grid and colour the squares you want to light up.
* Challenge: Can you make a heart shape? (Hint: it takes about 10 pixels!)

***

**🎨 Freies Erstellen — Mein erstes Pixel-Kunstwerk · Free Create — My First Pixel Art**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Gestalte etwas Persönliches — deinen Namensinitialen, einen Stern, eine Blume oder irgendetwas, das dir gefällt!
* Wenn du fertig bist, halte deinen imagiCharm hoch und zeige der Klasse — alle teilen, was sie gemacht haben!
* Lehrertipp: Der häufigste Fehler ist ein Tippfehler im Variablennamen. R, G, B müssen GROSSBUCHSTABEN sein.

🇬🇧 <mark style="color:$info;">English</mark>

* Design something personal — your name initial, a star, a flower, or anything you like!
* When done, hold up your imagiCharm and show the class — everyone shares what they made!
* Teacher tip: The most common error is a typo in the variable name. R, G, B must be CAPITAL letters.

***

**💾 Speichern & Reflexion · Save & Reflection**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Speichere deinen Code in der App mit deinem Namen.
* Schnelle Runde: jede Schülerin sagt EINE Sache, die sie heute gelernt hat, in einem Satz.

🇬🇧 <mark style="color:$info;">English</mark>

* Save your code in the app with your name.
* Quick round: each student says ONE thing they learned today in one sentence.

***

**🎮 Kahoot — Zeit zum Spielen! · Kahoot — Game Time!**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Öffne Kahoot und gib den Spiel-PIN ein.
* 10 Fragen über heute — Pixel, Farben, Python-Grundlagen!
* Die Top 3 Gewinner bekommen einen Applaus 👏

🇬🇧 <mark style="color:$info;">English</mark>

* Open Kahoot and enter the game PIN.
* 10 questions about today — pixels, colours, Python basics!
* Top 3 winners get a round of applause 👏

</details>

<details>

<summary><mark style="color:orange;"><strong>Week 2:</strong></mark> 🌈 Jede Farbe mischen · Mix Any Colour!</summary>

<mark style="color:$info;">**🎯**</mark>**&#x20;Ziele · Goals**

<mark style="color:$info;">Die Schüler\*innen lernen, was Variablen sind und wie sie jede Farbe mit RGB-Werten mischen kannst.</mark>

<mark style="color:$info;">The students will learn what variables are and how to mix any colour using RGB values.</mark>

***

**🔥 Aufwärmen — Compute-it Level 2 · Warm-Up — Compute-it Level 2**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Die Schüler\*innen müssen den Satz ausfüllen: "Wenn ich ein persönliches Logo für meinen Rucksack programmieren müsste, wäre es eine \[Farbe] \[Form], die meine Begeisterung für \[Hobby] zeigt.". Dazu kriegen sie 60 Sekunden Zeit um sich ihre Werte für die drei Variablen auszudenken. Jetzt "führt" jede/r ihren code der Reihe nach "aus", indem sie den Satz, mit ihren Werten eingesetzt, vorlesen.

* Öffne compute-it.toxicode.fr — spiele Level 2 als Klasse.
* Fokus: Der Computer merkt sich Werte in 'Boxen' (Variablen). Beobachte, wie sich der Wert in der Box ändert.
* Frage: 'Wenn die Box mit 5 beginnt und wir 3 addieren, was ist jetzt drin?' → Das ist genau das, was eine Variable macht!

<mark style="color:$info;">🇬🇧 English</mark>

The students need to fill out the sentence: "If I had to code a personal logo for my backpack, it would be a \[Color] \[Shape] that represents my love for \[Hobby].". They will get 60 seconds to think of their values for the three variables in this sentence. Then they will each "run their code", by reading the sentence filled out with their values for the variables one by one.

* Open compute-it.toxicode.fr — play Level 2 as a class.
* Focus: the computer remembers values in 'boxes' (variables). Watch how the value in the box changes.
* Ask: 'If the box starts with 5 and we add 3, what's inside now?' → This is exactly what a variable does!

***

🧠 **Wiederholen · Recap**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Was haben wir letzte Woche gelernt? Stelle offene Fragen und identifiziere die wesentlichen Punkte von letzter Woche, an die sich die Kinder erinnern sollen. Was ist Python? Was ist ImagiCharm? Was sind Fake-News? Wie erkennt man Fake-News?

<mark style="color:$info;">🇬🇧 English</mark>

What did we learn last week? Ask open-ended questions and identify what the kids should remember from last week. What is Python? What is ImagiCharm? What are are fake news? How can you identify fake news?

***

**📖 Theorie — Variablen & RGB · Theory — Variables & RGB**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Eine VARIABLE ist wie eine beschriftete Box. Du gibst ihr einen Namen und legst einen Wert hinein.
* In Python: meine\_farbe = (255, 100, 0) — jetzt hält 'meine\_farbe' diese orangene Farbe für immer!
* Warum Variablen nutzen? Statt jedes Mal (255, 100, 0) zu tippen, schreibe einfach meine\_farbe. Leichter zu lesen UND zu ändern!
* Namensregeln: keine Leerzeichen (benutze \_ stattdessen), keine Zahlen am Anfang, keine Sonderzeichen.
* Gute Namen: himmel\_blau, mein\_rot, lieblingsfarbe. Schlechte Namen: 1farbe, meine farbe, farbe!
* RGB-Mischung: Rot+Grün=Gelb, Rot+Blau=Lila, Grün+Blau=Cyan, alle 255=Weiß, alle 0=Schwarz (aus).
* Du kannst auch die eingebauten Kürzel nutzen: R, G, B, Y, O, A, P, M, W, K — kein Tupel nötig!

🇬🇧 <mark style="color:$info;">English</mark>

* A VARIABLE is like a labelled box. You give it a name and put a value inside.
* In Python: my\_colour = (255, 100, 0) — now 'my\_colour' holds that orange colour forever!
* Why use variables? Instead of typing (255, 100, 0) every time, just write my\_colour. Easier to read AND change!
* Naming rules: no spaces (use \_ instead), no numbers at the start, no special characters.
* Good names: sky\_blue, my\_red, fav\_colour. Bad names: 1colour, my colour, colour!
* RGB mixing: Red+Green=Yellow, Red+Blue=Purple, Green+Blue=Cyan, all 255=White, all 0=Black (off).
* You can also use the built-in shortcuts: R, G, B, Y, O, A, P, M, W, K — no tuple needed!

💻 <mark style="color:$info;">Code</mark>

```
# Store colours in variables (RGB tuples)
my_red    = (255, 0, 0)
my_blue   = (0, 0, 255)
sunshine  = (255, 220, 0)
my_pink   = (255, 50, 150)

# Use variables to light up pixels
m[0][0] = my_red
m[7][7] = my_blue
m[3][3] = sunshine
m[4][4] = my_pink

# Or use the built-in shortcuts directly
m[1][1] = R    # red
m[2][2] = G    # green
m[3][0] = O    # orange
```

***

**💻 Übung — Meine Farbpalette · Exercise — My Colour Palette**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Schritt 1 (10 Min): Erstelle 4 Farbvariablen mit RGB-Tupeln. Mische Farben, die du noch nie gesehen hast!
* Schritt 2 (10 Min): Benutze deine 4 Farben, um mindestens 8 Pixel in einem Muster zu beleuchten.
* Schritt 3 (10 Min): Ändere EINE Zahl in einer deiner Farben — was passiert? Versuche, deine Lieblingsfarbe zu machen!
* Farbherausforderung: Kannst du ROSA machen? Versuche (255, 20, 147).
* Kannst du ORANGE machen? Versuche (255, 165, 0).

🇬🇧 <mark style="color:$info;">English</mark>

* Step 1 (10 min): Create 4 colour variables using RGB tuples. Mix colours you've never seen before!
* Step 2 (10 min): Use your 4 colours to light up at least 8 pixels in a pattern.
* Step 3 (10 min): Change ONE number in one of your colours — what happens? Try to make your favourite colour!
* Colour challenge: Can you make PINK? Try (255, 20, 147).
* Can you make ORANGE? Try (255, 165, 0).

***

**🎨 Projekt — Mein Pixel-Charakter · Project — My Pixel Character**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Gestalte einen Pixel-Charakter mit deinen eigenen Farben! Es könnte ein Roboter, Alien, Tier oder Superheld sein.
* Anforderungen: Benutze mindestens 3 verschiedene Farbvariablen, beleuchte mindestens 10 Pixel.
* Benenne deinen Charakter und zeige ihn einem Partner — können sie erraten, was es ist?

🇬🇧 <mark style="color:$info;">English</mark>

* Design a pixel character using your custom colours! It could be a robot, alien, animal, or superhero.
* Requirements: use at least 3 different colour variables, light up at least 10 pixels.
* Name your character and show it to a partner — can they guess what it is?

***

**🎮 Kahoot — Farben & Variablen · Kahoot — Colours & Variables**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* 10 Fragen zu Variablen und RGB-Farben. Mal sehen, wer sich am meisten merkt!

🇬🇧 <mark style="color:$info;">English</mark>

* 10 questions on variables and RGB colours. Let's see who remembers the most!

</details>

<details>

<summary><mark style="color:yellow;"><strong>Week 3:</strong></mark> 🔄 Hör auf, dich zu wiederholen! · Stop Repeating Yourself!</summary>

<mark style="color:$info;">**🎯**</mark>**&#x20;Ziele · Goals**

<mark style="color:$info;">Die Schüler\*innen lernen, wie for-Schleifen ihnen helfen, viele Pixel mit wenigen Zeilen Code zu beleuchten.</mark>

<mark style="color:$info;">The students will learn how for loops help them light up many pixels with just a few lines of code.</mark>

***

**🔥 Aufwärmen — Compute-it Level 3 · Warm-Up — Compute-it Level 3**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

Ihr werdet jetzt Stille Post spielen. Versammelt euch dazu im Kreis. Ein/e Schüler\*in denkt sich jetzt ein Wort aus. Nun flüstert er/sie das Wort zum/r  Nächsten. Das passiert nun weiter so im Kreis bis das Wort wieder bei dem/der ersten Schüler\*in ankommt. Dann vergleicht ihr das Startwort und das aktuelle Wort und schaut ob sich das Wort verändert hat.

* Spiele Compute-it Level 3 — dieses Level führt SCHLEIFEN ein: dieselbe Sache mehrmals tun.
* Zähle zusammen: Wie oft läuft die Schleife? Was ändert sich jedes Mal?
* Schleifen im echten Leben: 5 Mal klatschen, bis 10 zählen, jeden Teller abwaschen — gleiche Aktion, wiederholt!

🇬🇧 <mark style="color:$info;">English</mark>

You will now be silently passing a message through the group. To do this, first gather in a circle. Now the first student can think of a word. They will now whisper their word to the next student. This continues throughout the entire circle until the word arrives back at the first student. Now compare the first word and the current word and see if something has changed.

* Play Compute-it Level 3 — this level introduces LOOPS: doing the same thing multiple times.
* Count together: how many times does the loop run? What changes each time?
* Real-world loops: clapping 5 times, counting to 10, washing each dish — same action, repeated!

***

🧠 **Wiederholen · Recap**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Was haben wir letzte Woche gelernt? Stelle offene Fragen und identifiziere die wesentlichen Punkte von letzter Woche, an die sich die Kinder erinnern sollen. Was ist eine Variable? Warum gibt es Variablen? Was ist RGB? Gehe die Recap Folie durch.

<mark style="color:$info;">🇬🇧 English</mark>

What did we learn last week? Ask open-ended questions and identify what the kids should remember from last week. What are variables? Why do we use variables?  What is RGB? Go through the recap slide.

***

**📖 Theorie — For-Schleifen · Theory — For Loops**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Eine FOR-SCHLEIFE wiederholt Code eine bestimmte Anzahl von Malen. Statt dieselbe Zeile 8 Mal zu schreiben, schreibe sie einmal in einer Schleife!
* Syntax: for i in range(8): — dies führt den eingerückten Code 8 Mal aus, mit i = 0, 1, 2, 3, 4, 5, 6, 7.
* EINRÜCKUNG ist entscheidend! Der Code innerhalb der Schleife muss eingerückt sein (4 Leerzeichen oder 1 Tab). Python nutzt Einrückung, um zu wissen, was 'innerhalb' der Schleife ist.
* range(8) gibt: 0, 1, 2, 3, 4, 5, 6, 7 — das sind 8 Zahlen ab 0.
* range(2, 6) gibt: 2, 3, 4, 5 — beginne bei 2, stoppe vor 6.
* VERSCHACHTELTE SCHLEIFEN: eine Schleife in einer Schleife! Nutze dies, um das gesamte 8×8-Raster mit nur 4 Zeilen abzudecken.

<mark style="color:$info;">🇬🇧 English</mark>

* A FOR LOOP repeats code a set number of times. Instead of writing the same line 8 times, write it once in a loop!
* Syntax: for i in range(8): — this runs the indented code 8 times, with i = 0, 1, 2, 3, 4, 5, 6, 7.
* INDENTATION is critical! The code inside the loop must be indented (4 spaces or 1 Tab). Python uses indentation to know what's 'inside' the loop.
* range(8) gives: 0, 1, 2, 3, 4, 5, 6, 7 — that's 8 numbers starting from 0.
* range(2, 6) gives: 2, 3, 4, 5 — start at 2, stop before 6.
* NESTED LOOPS: a loop inside a loop! Use this to cover the whole 8×8 grid with just 4 lines.

<mark style="color:$info;">💻 Code</mark>

```
# Light up an entire row (row 0) in red
for x in range(8):
    m[x][0] = R

# Light up the whole grid in blue
for x in range(8):
    for y in range(8):
        m[x][y] = B

# Fill the grid with a custom colour
my_colour = (100, 0, 200)   # purple
for x in range(8):
    for y in range(8):
        m[x][y] = my_colour
```

***

**💻 Übung — Streifen & Muster · Exercise — Stripes & Patterns**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Übung 1 (10 Min): Beleuchte alle 8 Pixel in Zeile 3 mit deiner Lieblingsfarbe mithilfe einer for-Schleife.
* Übung 2 (10 Min): Beleuchte Spalte 4 (alle y-Werte von 0 bis 7) mit einer anderen Farbe.
* Übung 3 (10 Min): Benutze verschachtelte Schleifen, um das GESAMTE Raster mit einer Farbe zu füllen. Dann ändere die Farbe — nur 1 Zeile zu bearbeiten!
* Bonus: Beleuchte Zeilen 0, 2, 4, 6 in R und Zeilen 1, 3, 5, 7 in B, um horizontale Streifen zu machen.

<mark style="color:$info;">🇬🇧 English</mark>

* Exercise 1 (10 min): Light up all 8 pixels in row 3 with your favourite colour using a for loop.
* Exercise 2 (10 min): Light up column 4 (all y values from 0 to 7) with a different colour.
* Exercise 3 (10 min): Use nested loops to fill the ENTIRE grid with one colour. Then change the colour — only 1 line to edit!
* Bonus: Light up rows 0, 2, 4, 6 in R and rows 1, 3, 5, 7 in B to make horizontal stripes.

***

**🎨 Projekt — Streifen & Leitern · Project — Stripes & Ladders**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Erstelle ein gestreiftes oder kariertes Muster NUR mit for-Schleifen — keine einzelnen m\[x]\[y]-Zeilen erlaubt!
* Ideen: Regenbogenstreifen (jede Zeile eine andere Farbe), diagonales Muster, Rahmen.
* Teile dein Muster: Kann dein Nachbar es nachbauen, nur indem er deinen imagiCharm anschaut?

<mark style="color:$info;">🇬🇧 English</mark>

* Create a striped or checkered pattern using ONLY for loops — no individual m\[x]\[y] lines allowed!
* Ideas: rainbow stripes (each row a different colour), diagonal pattern, border frame.
* Share your pattern: can your neighbour recreate it just by looking at your imagiCharm?

***

**🎮 Kahoot — Schleifen-Quiz · Kahoot — Loops Quiz**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* 10 Fragen zu for-Schleifen, range() und Einrückung!

🇬🇧 <mark style="color:$info;">English</mark>

* 10 questions on for loops, range(), and indentation!

</details>

<details>

<summary><mark style="color:blue;"><strong>Week 4:</strong></mark> 🎬 Bring es zum Bewegen! · Make It Move!</summary>

<mark style="color:$info;">**🎯**</mark>**&#x20;Ziele · Goals**

<mark style="color:$info;">Die Schüler\*innen erstellen ihre erste Animation auf dem imagiCharm — mehrere Frames, die wie ein Daumenkino ablaufen!</mark>

<mark style="color:$info;">The students will create their first animation on the imagiCharm — multiple frames playing like a flip book!</mark>

***

**🔥 Aufwärmen — Compute-it Level 4 · Warm-Up — Compute-it Level 4**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

Ihr spielt wahr oder falsch. Dazu liest der/die Lehrer/in eine Aussage vor und die Schüler\*innen müssen entscheiden, ob die Aussage wahr oder falsch ist. Wenn sie glauben, dass die Aussage wahr ist, sollen sie aufstehen. Ansonsten sollen sie sitzen bleiben. Im Anschluss erklärt ihr zusammen warum.

* Spiele Compute-it Level 4 — dieses Level zeigt SEQUENZEN: Schritte, die nacheinander passieren.
* Daumenkino-Demo: Blättere schnell durch ein kleines Daumenkino (oder zeige ein GIF) — frage 'Was lässt das wie Bewegung aussehen?'
* Antwort: Viele Standbilder, sehr schnell gezeigt! Genau so funktioniert Animation im Code.

🇬🇧 <mark style="color:$info;">English</mark>

You will be playing true or false. To do so, the teacher will read a statement and the students have to decide whether the statement is true or false. If they think that the statement is true, they should stand up. Otherwise, they should stay seated. Afterwards, you will discuss together why.

* Play Compute-it Level 4 — this level shows SEQUENCES: steps that happen one after another.
* Flip-book demo: quickly flip through a small flip-book (or show a GIF) — ask 'what makes this look like it's moving?'
* Answer: many still images shown very fast! That's exactly how animation works in code.

***

🧠 **Wiederholen · Recap**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Was haben wir in den letzten drei Wochen gelernt? Stelle offene Fragen und identifiziere die wesentlichen Punkte von den letzten Woche, an die sich die Kinder erinnern sollen. Arbeite mit der Recap Folie. Woche 1: Koordinaten und Farben (Wie funktionieren Koordinaten im ImagiCharm?), Woche 2: Variablen (Warum benutzt man Variablen?), Woche 3: Die for-Schleife (Wie funktioniert die for-Schleife?).

<mark style="color:$info;">🇬🇧 English</mark>

What did we learn in the last three weeks? Ask open-ended questions and identify what the kids should remember from the last weeks. Work with the recap slide. week 1: coordinates and colours (How do coordinates work in ImagiCharm?), week 2: variables (Why do we use variables?), week 3: the for-loop (How does the for loop work?).

***

**📖 Theorie — Animation & Frames · Theory — Animation & Frames**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Animation = viele FRAMES, die nacheinander gezeigt werden.
* In imagi Edu: Erstelle zuerst ein Animation-Objekt — a = Animation()
* Dann setze Pixel auf der Matrix m und rufe a.add\_frame(m, dauer) auf, um diesen Frame zu speichern.
* Dauer ist in Millisekunden: 500 = eine halbe Sekunde, 200 = schnell, 1000 = eine volle Sekunde.
* Um den Bildschirm zwischen Frames zu löschen, setze Pixel auf K (schwarz/aus) vor dem Zeichnen des nächsten Frames.
* Designtipp: Ändere nur wenige Pixel zwischen Frames, um eine flüssige Bewegung zu erzeugen.

<mark style="color:$info;">🇬🇧 English</mark>

* Animation = many FRAMES shown one after another.
* In imagi Edu: first create an Animation object — a = Animation()
* Then set pixels on the matrix m, and call a.add\_frame(m, duration) to save that frame.
* duration is in milliseconds: 500 = half a second, 200 = fast, 1000 = one full second.
* To clear the screen between frames, set pixels to K (black/off) before drawing the next frame.
* Design tip: change only a few pixels between frames to create smooth movement.

<mark style="color:$info;">💻 Code</mark>

```
a = Animation()

# --- Frame 1: dot on the left ---
m[0][3] = Y
a.add_frame(m, 400)

# --- Frame 2: clear, then dot in the middle ---
m[0][3] = K        # turn off previous dot
m[3][3] = Y
a.add_frame(m, 400)

# --- Frame 3: clear, then dot on the right ---
m[3][3] = K
m[7][3] = Y
a.add_frame(m, 400)
```

***

**💻 Übung — Meine erste Animation · Exercise — My First Animation**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Übung 1 (10 Min): Kopiere das Beispiel oben und führe es aus — schau, wie der Punkt über den Bildschirm reist!
* Übung 2 (10 Min): Füge 2 weitere Frames hinzu, damit der Punkt von rechts nach links zurückreist.
* Übung 3 (10 Min): Ändere die Farbe des Punktes in jedem Frame — lass ihn durch R, G, B, Y wechseln!
* Tipp: Schalte immer den vorherigen Punkt aus (= K), bevor du die neue Position zeichnest.

🇬🇧 <mark style="color:$info;">English</mark>

* Exercise 1 (10 min): Copy the example above and run it — watch the dot travel across the screen!
* Exercise 2 (10 min): Add 2 more frames to make the dot travel back from right to left.
* Exercise 3 (10 min): Change the colour of the dot in each frame — make it cycle through R, G, B, Y!
* Tip: Always turn off (= K) the previous dot before drawing the new position.

***

**🎨 Projekt — Schlagendes Herz · Project — Beating Heart**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Erstelle eine schlagende Herz-Animation: Frame 1 = kleines Herz (Mittelpixel), Frame 2 = größeres Herz (äußeren Ring hinzufügen), wiederholen!
* Benutze Rot (R) oder ein eigenes Dunkelrot (200, 0, 50) für die Herz-Pixel.
* Setze die Dauer auf 300ms für einen realistischen Herzschlag.
* Trage deinen imagiCharm und zeige dein schlagendes Herz der Klasse!

<mark style="color:$info;">🇬🇧 English</mark>

* Create a beating heart animation: Frame 1 = small heart (centre pixels), Frame 2 = bigger heart (add outer ring), repeat!
* Use red (R) or a custom deep red (200, 0, 50) for the heart pixels.
* Set duration to 300ms for a realistic heartbeat.
* Wear your imagiCharm and show your beating heart to the class!

***

**🎮 Kahoot — Animation-Quiz · Kahoot — Animation Quiz**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* 10 Fragen zu Animation(), add\_frame() und Timing!

<mark style="color:$info;">🇬🇧 English</mark>

* 10 questions on Animation(), add\_frame(), and timing!

</details>

<details>

<summary><mark style="color:$success;"><strong>Week 5:</strong></mark> 🧠 Code der denkt! · Code That Thinks!</summary>

<mark style="color:$info;">**🎯**</mark>**&#x20;Ziele · Goals**

<mark style="color:$info;">Die Schüler\*innen lernen, wie ihr Code Entscheidungen treffen kann — mit if, elif und else.</mark>

<mark style="color:$info;">The students will learn how their code can make decisions — using if, elif, and else.</mark>

***

**🔥 Aufwärmen — Compute-it Level 5 · Warm-Up — Compute-it Level 5**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

Die Schüler\*innen werden sich jetzt in sortierten Reihen zusammenfinden müssen. Dazu gibst du ein Kriterium vor (z.B. Alter) und Schüler\*innen müssen sich so schnell wie möglich nach diesem Kriterium sortiert aufstellen. Um das ganze etwas spannender zu machen kannst du das Spiel noch modifizieren, indem die Schüler\*innen z.B. nicht reden dürfen oder du ihnen ein Zeitlimit setzt. Beispiele für Kriterien sind: Alter, Geburtagsmonat, Körpergröße, Vorname (alphabetisch), etc.

* Spiele Compute-it Level 5 — dieses Level führt BEDINGUNGEN (if/else-Entscheidungen) ein.
* If/else im echten Leben: 'WENN es regnet, nimm einen Regenschirm. SONST trage eine Sonnenbrille.'
* Frage Schüler: Gib 3 Beispiele aus dem echten Leben für if/else-Entscheidungen, die du jeden Tag triffst.

🇬🇧 <mark style="color:$info;">English</mark>

The students will now have to line up in order according to a criterion. To do so you will determine the criterion (e.g.  age) and the students have to line up in order as fast as possible. To make this more interesting, you can modify the game by having a silent round, where the students can't talk to each other or by setting a time limit. Examples of criteria are: age, birthday month, height, name (alphabetically), etc.

* Play Compute-it Level 5 — this level introduces CONDITIONS (if/else decisions).
* Real-life if/else: 'IF it's raining, take an umbrella. ELSE, wear sunglasses.'
* Ask students: give 3 real-life examples of if/else decisions they make every day.

***

🧠 **Wiederholen · Recap**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Was haben wir in den letzten vier Wochen gelernt? Stelle offene Fragen und identifiziere die wesentlichen Punkte von den letzten Woche, an die sich die Kinder erinnern sollen. Arbeite mit der Recap Folie. Woche 1: Koordinaten und Farben (Wie funktionieren Koordinaten im ImagiCharm?), Woche 2: Variablen Warum benutzt man Variablen?), Woche 3: Die for-Schleife (Wie funktioniert die for-Schleife?), Woche 4: if-Anweisungen (Was machen if-Anweisungen?).

<mark style="color:$info;">🇬🇧 English</mark>

What did we learn in the last four weeks? Ask open-ended questions and identify what the kids should remember from the last weeks. Work with the recap slide. week 1: coordinates and colours (How do coordinates work in ImagiCharm?), week 2: variables (Why do we use variables), week 3: the for-loop (How does the for loop work?), week 4: if-conditions (What do if conditions do?).

***

📖 **Theorie — If/Else & Modulo · Theory — If/Else & Modulo**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* IF/ELSE lässt deinen Code wählen, was er basierend auf einer Bedingung tun soll.
* Syntax: if Bedingung: → tue dies. else: → tue stattdessen das.
* elif = 'sonst wenn' — für mehrere Auswahlmöglichkeiten!
* Vergleichsoperatoren: == (gleich), != (ungleich), > (größer), < (kleiner).
* DER MODULO-OPERATOR % gibt den REST der Division. 4 % 2 = 0 (gerade). 5 % 2 = 1 (ungerade).
* Zaubertrick: if (x + y) % 2 == 0 → eine Farbe. else → andere Farbe. Das erzeugt automatisch ein Schachbrett!

🇬🇧 <mark style="color:$info;">English</mark>

* IF/ELSE lets your code choose what to do based on a condition.
* Syntax: if condition: → do this. else: → do that instead.
* elif = 'else if' — for multiple choices!
* Comparison operators: == (equal), != (not equal), > (greater), < (less).
* THE MODULO OPERATOR % gives the REMAINDER of division. 4 % 2 = 0 (even). 5 % 2 = 1 (odd).
* Magic trick: if (x + y) % 2 == 0 → one colour. else → another colour. This auto-generates a checkerboard!

💻 <mark style="color:$info;">Code</mark>

```
# Auto-generate a checkerboard pattern!
for x in range(8):
    for y in range(8):
        if (x + y) % 2 == 0:
            m[x][y] = R
        else:
            m[x][y] = B

# Three-colour pattern with elif
for x in range(8):
    for y in range(8):
        if x % 3 == 0:
            m[x][y] = R
        elif x % 3 == 1:
            m[x][y] = G
        else:
            m[x][y] = B
```

***

**💻 Übung — Bedingungen in Aktion · Exercise — Conditions in Action**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Übung 1 (10 Min): Tippe den Schachbrett-Code ein und führe ihn aus. Ändere R und B in deine eigenen Farben!
* Übung 2 (10 Min): Ändere die Bedingung — versuche (x + y) % 3 == 0. Welches Muster entsteht?
* Übung 3 (10 Min): Benutze elif für ein 3-Farben-Streifenmuster mit x % 3.

🇬🇧 <mark style="color:$info;">English</mark>

* Exercise 1 (10 min): Type the checkerboard code and run it. Change R and B to your own colours!
* Exercise 2 (10 min): Modify the condition — try (x + y) % 3 == 0. What pattern does it make?
* Exercise 3 (10 min): Use elif to make a 3-colour stripe pattern using x % 3.

***

🎨 **Projekt — Magisches Schachbrett · Project — Magic Checkerboard**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Erstelle dein eigenes einzigartiges Muster mit if/else und Schleifen — keine manuelle Pixel-Platzierung!
* Herausforderung: Mache ein Muster mit 3 oder mehr Farben.
* Superherausforderung: Mache ein DIAGONALES Streifenmuster (Hinweis: benutze x == y oder x + y Bedingungen).
* Zeige dein Muster — kann jemand die Bedingung erraten, die du benutzt hast?

<mark style="color:$info;">🇬🇧 English</mark>

* Create your own unique pattern using if/else and loops — no manual pixel placement!
* Challenge: make a pattern that uses 3 or more colours.
* Super challenge: make a DIAGONAL stripe pattern (hint: use x == y or x + y conditions).
* Show your pattern — can anyone guess the condition you used?

***

🎮 **Kahoot — Bedingungen-Quiz · Kahoot — Conditionals Quiz**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* 10 Fragen zu if/else, elif und Modulo!

🇬🇧 <mark style="color:$info;">English</mark>

* 10 questions on if/else, elif, and modulo!

</details>

<details>

<summary><mark style="color:violet;"><strong>Week 6:</strong></mark> 🎲 Füge Überraschungen hinzu! · Add Some Surprise!</summary>

<mark style="color:$info;">**🎯**</mark>**&#x20;Ziele · Goals**

<mark style="color:$info;">Die Schüler\*innen lernen, wie sie das random-Modul importieren und damit Kunst erstellen, die jedes Mal anders aussieht.</mark>

<mark style="color:$info;">The students will learn how to import the random module and use it to create art that looks different every time.</mark>

***

**🔥 Aufwärmen — Compute-it Level 6 · Warm-Up — Compute-it Level 6**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Die Schüler\*innen werden jetzt ein Ketten-Assoziationsspiel spielen. Dazu versammelt ihr euch im Kreis. Ein/e Schüler/in kann jetzt das erste Wort nennen (z.B. Sonne). Der/die nächste/r im Kreis muss jetzt schnell ein Wort nennen, das dazu passt (z.B. Licht). Das geht jetzt im Kreis immer so weiter. Wenn jemand mehr als 3 Sekunden braucht oder ein Wort wiederholt ist er raus.

* Spiele Compute-it Level 6 — dieses Level führt ZUFÄLLIGKEIT ein.
* Würfelspiel: Wirf einen echten Würfel. Frage: 'Kannst du vorhersagen, welche Zahl als nächstes kommt?' → Nein! Das ist Zufälligkeit.
* Wo ist Zufälligkeit im Code nützlich? Spiele, Kunst, Simulationen, Sicherheit!

<mark style="color:$info;">🇬🇧 English</mark>\
The student will now be playing a chain-association game. To do this, first gather in a circle. Then one student can say one word out loud (e.g. sun). Now the next student in the circle has to quickly say a fitting word (e.g. light). This then continues through the circle. If someone needs more than 3 seconds to come up with a word or repeats a word, they are eliminated.

* Play Compute-it Level 6 — this level introduces RANDOMNESS.
* Dice game: roll a real die. Ask: 'Can you predict what number comes next?' → No! That's randomness.
* Where is randomness useful in code? Games, art, simulations, security!

***

🧠 **Wiederholen · Recap**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Was haben wir in den letzten fünf Wochen gelernt? Stelle offene Fragen und identifiziere die wesentlichen Punkte von den letzten Woche, an die sich die Kinder erinnern sollen. Arbeite mit der Recap Folie. Woche 1: Koordinaten und Farben, Woche 2: Variablen, Woche 3: Die for-Schleife, Woche 4: if-Anweisungen, Woche 5: Animationen.

<mark style="color:$info;">🇬🇧 English</mark>

What did we learn in the last five weeks? Ask open-ended questions and identify what the kids should remember from the last weeks. Work with the recap slide. week 1: coordinates and colours, week 2: variables, week 3: the for-loop, week 4: if-conditions, week 5: animations.

***

**📖 Theorie — Module & random · Theory — Modules & random**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Ein MODUL ist ein Werkzeugkasten mit fertigen Funktionen. Python hat Hunderte davon!
* Um ein Modul zu nutzen, musst du es zuerst IMPORTIEREN: import random
* random.randint(a, b) gibt eine zufällige ganze Zahl zwischen a und b (einschließlich beider).
* Beispiel: random.randint(0, 7) gibt eine zufällige Pixelposition (0 bis 7)!
* random.randint(0, 255) gibt einen zufälligen Farbwert — kombiniere drei für ein zufälliges Farb-Tupel!
* Jedes Mal, wenn du den Code ausführst, bekommst du andere Ergebnisse — das ist generative Kunst!

🇬🇧 <mark style="color:$info;">English</mark>

* A MODULE is a toolbox of ready-made functions. Python has hundreds of them!
* To use a module, you must IMPORT it first: import random
* random.randint(a, b) gives a random whole number between a and b (including both).
* Example: random.randint(0, 7) gives a random pixel position (0 to 7)!
* random.randint(0, 255) gives a random colour value — combine three for a random colour tuple!
* Every time you run the code, you get different results — that's generative art!

💻 <mark style="color:$info;">Code</mark>

```
import random

# Random colour on every pixel!
for x in range(8):
    for y in range(8):
        r = random.randint(0, 255)
        g = random.randint(0, 255)
        b = random.randint(0, 255)
        m[x][y] = (r, g, b)

# Random stars: only light up some pixels
for x in range(8):
    for y in range(8):
        m[x][y] = K            # clear first
if random.randint(0, 10) > 7:
    m[x][y] = W            # sparse white star
```

***

**💻 Übung — Zufällige Kunst · Exercise — Random Art**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Übung 1 (10 Min): Führe den zufälligen Farbcode oben aus. Führe ihn 3 Mal aus — jedes Mal anders!
* Übung 2 (10 Min): Mache einen 'zufällige Sterne'-Effekt: Lösche das Raster zuerst auf K, dann beleuchte Pixel nur, wenn random.randint(0, 10) > 7.
* Übung 3 (10 Min): Wähle zufällige Positionen für 5 gelbe Sterne: rx = random.randint(0,7), ry = random.randint(0,7), m\[rx]\[ry] = Y

🇬🇧 <mark style="color:$info;">English</mark>

* Exercise 1 (10 min): Run the random colour code above. Run it 3 times — different each time!
* Exercise 2 (10 min): Make a 'random stars' effect: clear the grid to K first, then light up pixels only when random.randint(0, 10) > 7.
* Exercise 3 (10 min): Pick random positions for 5 yellow stars: rx = random.randint(0,7), ry = random.randint(0,7), m\[rx]\[ry] = Y

***

**🎨 Projekt — Funkelnde Sterne · Project — Sparkling Stars**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Erstelle eine Sternenfeld-Animation: Jeder Frame hat zufällig platzierte weiße/gelbe Punkte auf schwarzem Hintergrund.
* Schritt 1: a = Animation()
* Schritt 2: In einer Schleife für 4 Frames — Raster auf K löschen, dann 6 zufällige Sterne mit random.randint(0,7) platzieren, dann a.add\_frame(m, 300).
* Die Sterne werden funkeln — verschiedene Positionen in jedem Frame!
* Optional: Benutze eine zufällige Farbe für jeden Stern.

<mark style="color:$info;">🇬🇧 English</mark>

* Create a starfield animation: each frame has randomly placed white/yellow dots on a black background.
* Step 1: a = Animation()
* Step 2: In a loop for 4 frames — clear grid to K, then place 6 random stars using random.randint(0,7), then a.add\_frame(m, 300).
* The stars will twinkle — different positions each frame!
* Optional: use a random colour for each star.

***

**🎮 Kahoot — Module & Zufall · Kahoot — Modules & Randomness**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* 10 Fragen zu import, random und generativer Kunst!

🇬🇧 <mark style="color:$info;">English</mark>

* 10 questions on import, random, and generative art!

</details>

<details>

<summary><mark style="color:pink;"><strong>Week 7:</strong></mark> 🧩 Baue deine eigenen Werkzeuge! · Build Your Own Tools!</summary>

<mark style="color:$info;">**🎯**</mark>**&#x20;Ziele · Goals**

<mark style="color:$info;">Die Schüler\*innen lernen, eigene Funktionen zu schreiben — wiederverwendbare Code-Bausteine wie LEGO-Steine.</mark>

<mark style="color:$info;">The students will learn to write their own functions — reusable code building blocks like LEGO bricks.</mark>

***

**🔥 Aufwärmen — Compute-it Level 7 · Warm-Up — Compute-it Level 7**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

Ihr spielt Feuer, Wasser, Sturm. Die Schüler\*innen laufen frei im Raum herum. Wenn du ein Befehl gibst, müssen alle Schüler\*innen diesen befolgen. Die Befehle sind:

* 🔥 Feuer: Lauft in die Raumecke!
* 💧 Wasser: Setzt euch auf einen Stuhl (Füße hoch)!
* ⛈️ Sturm: Legt euch flach auf den Bauch!
* 🧊 Eis: Bleibt wie eingefroren stehen!

Nach ein paar Runden kann dann ein/e Schüler/in die Befehle geben. Ihr könnt auch eigene Befehle hinzufügen oder andere Wörter (z.B. Tornado) zur Verwirrung sagen.

* Spiele Compute-it Level 7 — dieses Level zeigt FUNKTIONEN: benannte Blöcke von Anweisungen.
* LEGO-Analogie: Eine Funktion ist wie ein LEGO-Stein. Du entwirfst ihn einmal, dann schnappst du ihn überall ein, wo du ihn brauchst!
* Funktionen im echten Leben: Ein Rezept ist eine Funktion! 'kuchen\_backen()' — du rufst es auf und es macht alle Schritte.

🇬🇧 <mark style="color:$info;">English</mark>

You will be playing Feuer, Wasser, Sturm. The students will be walking through the room freely. When you give an instruction, they must do the corresponding action. The instructions are:

* 🔥 Feuer: Run to a corner of the room!
* 💧 Wasser: Sit down on a chair (lift your feet)!
* ⛈️ Sturm: Lay down flat on your belly!
* 🧊 Eis: Stand still as if you were frozen!

After a few rounds a student can be giving the instructions. You can also add your own instructions or add in random words (e.g. Tornado) for confusion.

* Play Compute-it Level 7 — this level shows FUNCTIONS: named blocks of instructions.
* LEGO analogy: a function is like a LEGO brick. You design it once, then snap it in wherever you need it!
* Real-world functions: a recipe is a function! 'make\_cake()' — you call it and it does all the steps.

***

**📖 Theorie — Funktionen definieren & aufrufen · Theory — Defining & Calling Functions**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Definiere eine Funktion mit 'def': def meine\_funktion(): → dann rücke den Code darin ein.
* Rufe eine Funktion auf, indem du ihren Namen mit Klammern schreibst: meine\_funktion()
* PARAMETER lassen dich Werte in eine Funktion übergeben: def punkt\_zeichnen(x, y, farbe): — jetzt kannst du punkt\_zeichnen(3, 3, R) aufrufen!
* Warum Funktionen? Einmal schreiben, viele Male nutzen. Ändere die Funktion → ändert sich überall, wo sie benutzt wird!
* Funktionen machen langen Code kurz und lesbar.

🇬🇧 <mark style="color:$info;">English</mark>

* DEFINE a function with 'def': def my\_function(): → then indent the code inside.
* CALL a function by writing its name with parentheses: my\_function()
* PARAMETERS let you pass values into a function: def draw\_dot(x, y, colour): — now you can call draw\_dot(3, 3, R)!
* Why functions? Write once, use many times. Change the function → changes everywhere it's used!
* Functions make long code short and readable.

💻 <mark style="color:$info;">Code</mark>

```
# Define a function to draw a cross shape
def draw_cross(cx, cy, colour):
    m[cx][cy]     = colour   # centre
    m[cx-1][cy]   = colour   # left
    m[cx+1][cy]   = colour   # right
    m[cx][cy-1]   = colour   # up
    m[cx][cy+1]   = colour   # down

# Call the function with different positions!
draw_cross(2, 2, R)
draw_cross(5, 5, B)
draw_cross(2, 5, Y)

# Define a function to fill a whole row
def fill_row(y, colour):
    for x in range(8):
        m[x][y] = colour

fill_row(0, G)
fill_row(7, O)
```

***

**💻 Übung — Eigene Funktionen · Exercise — Your Own Functions**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Übung 1 (10 Min): Schreibe eine Funktion punkt\_zeichnen(x, y, farbe), die ein Pixel beleuchtet. Rufe sie 5 Mal mit verschiedenen Positionen und Farben auf.
* Übung 2 (10 Min): Schreibe eine Funktion zeile\_fuellen(y, farbe), die eine gesamte Zeile beleuchtet. Rufe sie für Zeilen 0, 3 und 7 auf.
* Übung 3 (10 Min): Schreibe eine Funktion box\_fuellen(x1, y1, x2, y2, farbe), die einen rechteckigen Bereich füllt. Benutze verschachtelte Schleifen innerhalb der Funktion!

🇬🇧 <mark style="color:$info;">English</mark>

* Exercise 1 (10 min): Write a function draw\_dot(x, y, colour) that lights up one pixel. Call it 5 times with different positions and colours.
* Exercise 2 (10 min): Write a function fill\_row(y, colour) that lights up an entire row. Call it for rows 0, 3, and 7.
* Exercise 3 (10 min): Write a function fill\_box(x1, y1, x2, y2, colour) that fills a rectangular area. Use nested loops inside the function!

***

**🎨 Projekt — Form-Generator · Project — Shape Generator**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Baue eine Form-Bibliothek: Schreibe Funktionen für mindestens 3 Formen (Kreuz, gefülltes Quadrat, Diagonallinie, usw.).
* Dann rufe deine Funktionen auf, um eine Szene zu komponieren — wie eine Stadtsilhouette oder ein Gesicht!
* Herausforderung: Füge jedem Funktion einen Farb-Parameter hinzu, damit du Farben leicht ändern kannst.
* Superherausforderung: Mache eine animierte Version, die durch deine Formen mit Animation() zykliert!

🇬🇧 <mark style="color:$info;">English</mark>

* Build a shape library: write functions for at least 3 shapes (cross, filled square, diagonal line, etc.).
* Then call your functions to compose a scene — like a city skyline or a face!
* Challenge: add a colour parameter to every function so you can change colours easily.
* Super challenge: make an animated version that cycles through your shapes using Animation()!

***

**🎮 Kahoot — Funktionen-Quiz · Kahoot — Functions Quiz**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* 10 Fragen zu def, Parametern und dem Aufrufen von Funktionen!

<mark style="color:$info;">🇬🇧 English</mark>

* 10 questions on def, parameters, and calling functions!

</details>

<details>

<summary><mark style="color:purple;"><strong>Week 8:</strong></mark> ✨ Baue dein Demo-Tag-Projekt! · Build Your Demo Day Project!</summary>

<mark style="color:$info;">**🎯**</mark>**&#x20;Ziele · Goals**

<mark style="color:$info;">Die Schüler\*innen kombinieren alle gelernten Fähigkeiten, um ihr persönliches Demo-Tag-Projekt zu erstellen und es vor einem Publikum zu präsentieren.</mark>

<mark style="color:$info;">The students will combine all their skills to create their personal Demo Day project and rehearse presenting it to an audience.</mark>

***

**🔥 Aufwärmen — Compute-it Level 8 + Rückblick · Warm-Up — Compute-it Level 8 + Review**

TODO: add warm-up from icebreaker list

🇩🇪 <mark style="color:$info;">Deutsch</mark>

Die Kinder werden sich gegenseitig programmieren. Teile dazu die Kinder in Paare ein. Ein Kind ist der/die Programmierer/in  und das andere Kind ist der Roboter. Der/die Programmierer/in muss nun dem Roboter Schritt für Schritt Anweisungen geben um eine Aufgabe zu machen. Der Roboter darf aber nur GENAU das machen, was ihm der/die Programmier/in sagt. Das führt du lustigen Fehlern, die der/die Programmier/in beheben muss. Nachdem die Aufgabe erfüllt ist, tauschen die Kinder ihre Rollen. Beispielaufgaben: Ein Quadrat zeichnen auf Papier oder etwas kleines aus Bausteinen bauen.

* Spiele Compute-it Level 8 — das letzte Level! Feiere den Abschluss des gesamten Spiels.
* Schneller Fähigkeiten-Rückblick: Gehe durch den Raum — jede Schülerin nennt EINEN Python-Begriff, den sie sich merkt.
* Fähigkeiten-Checkliste an der Tafel: Variablen ✓ Schleifen ✓ Animation ✓ If/Else ✓ Zufall ✓ Funktionen ✓

🇬🇧 <mark style="color:$info;">English</mark>

The kids will be programming each other. Pair the students up. One kid is the programmer and one kid is the robot. The programmer will now be giving the robot step by step instructions to do a task. However, the robot is only allowed to do EXACTLY what he is instructed. This causes funny mistakes that the programmer has to fix. After the task is finished, the kids will swap roles. Example tasks: Draw a square on a piece of paper or build something small out of blocks.

* Play Compute-it Level 8 — the final level! Celebrate completing the whole game.
* Quick skills review: go around the room — each student names ONE Python concept they remember.
* Skills checklist on the board: Variables ✓ Loops ✓ Animation ✓ If/Else ✓ Random ✓ Functions ✓

***

**📖 Projektplanung — Dein Demo-Tag-Projekt · Project Planning — Your Demo Day Project**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Dein Demo-Tag-Projekt sollte MINDESTENS 3 der Fähigkeiten nutzen, die du gelernt hast.
* Ideen: Animierte Geschichte (Charakter bewegt sich), generative Kunst (zufällige Muster), interaktive Anzeige (Formen + Farben), Pixel-Porträt.
* Planungsschritte: 1) Wähle dein Thema. 2) Skizziere deine Frames auf Papier. 3) Liste auf, welche Python-Fähigkeiten du nutzen wirst. 4) Programmiere es! 5) Teste und verfeinere.
* Präsentationstipp: Bereite eine 60-Sekunden-Rede vor — 'Mein Projekt ist... Ich habe... benutzt. Das Schwierigste war... Ich bin stolz auf...'

<mark style="color:$info;">🇬🇧 English</mark>

* Your Demo Day project should use AT LEAST 3 of the skills you've learned.
* Ideas: animated story (character moving), generative art (random patterns), interactive display (shapes + colours), pixel portrait.
* Planning steps: 1) Choose your theme. 2) Sketch your frames on paper. 3) List which Python skills you'll use. 4) Code it! 5) Test and polish.
* Presentation tip: prepare a 60-second speech — 'My project is... I used... The hardest part was... I'm proud of...'

💻 <mark style="color:$info;">Code</mark>

```
import random

# --- Helper functions ---
def draw_star(cx, cy, colour):
    m[cx][cy]   = colour
    m[cx-1][cy] = colour
    m[cx+1][cy] = colour
    m[cx][cy-1] = colour
    m[cx][cy+1] = colour

# --- Background with if/else ---
for x in range(8):
    for y in range(8):
        if (x + y) % 2 == 0:
            m[x][y] = (10, 10, 30)   # dark navy
        else:
            m[x][y] = K

# --- Random gold stars ---
for _ in range(5):
    rx = random.randint(1, 6)
    ry = random.randint(1, 6)
    draw_star(rx, ry, Y)

# --- Save as animation frame ---
a = Animation()
a.add_frame(m, 800)
```

***

**💻 Build Studio — Dein Meisterwerk · Build Studio — Your Masterpiece**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

* Das ist DEINE Zeit! Baue dein Demo-Tag-Projekt von Grund auf.
* Die Lehrerin geht herum, um zu helfen — Fokus auf Ermutigung zur Kreativität, nicht auf alles reparieren.
* Meilenstein-Check bei 25 Min: Alle sollten mindestens einen funktionierenden ersten Frame haben.
* Bei 40 Min: Beginne mit dem Polieren — Fehler beheben, Farben anpassen, Animationstiming hinzufügen.
* Bei 50 Min: Übe deine 60-Sekunden-Präsentation mit einem Partner.
* Denk daran: Es muss nicht perfekt sein — es muss DEINS sein!

<mark style="color:$info;">🇬🇧 English</mark>

* This is YOUR time! Build your Demo Day project from scratch.
* Teacher circulates to help — focus on encouraging creativity, not fixing everything.
* Milestone check at 25 min: everyone should have at least a working first frame.
* At 40 min: start polishing — fix bugs, adjust colours, add animation timing.
* At 50 min: rehearse your 60-second presentation with a partner.
* Remember: it doesn't have to be perfect — it has to be YOURS!

***

**🎮 Kahoot — Großes Abschluss-Quiz! · Kahoot — Grand Final Quiz!**

🇩🇪 <mark style="color:$info;">Deutsch</mark>

* Das GROSSE Abschluss-Quiz — 10 Fragen über ALLE 8 Sitzungen! Wer ist der Python-Superheld?

<mark style="color:$info;">🇬🇧 English</mark>

* The BIG final quiz — 10 questions covering ALL 8 sessions! Who is the Python Superhero?

</details>

<details>

<summary><mark style="color:$danger;"><strong>Week 9:</strong></mark> 🎉 Demo-Tag · Demo Day!</summary>

<mark style="color:$info;">Die Schüler\*innen haben es geschafft! Zeit, ihren imagiCharm zu tragen, die Bühne zu betreten und der Welt zu zeigen, was sie mit Python gebaut haben!</mark>

<mark style="color:$info;">The students have done it! Time to wear their imagiCharm, take the stage, and show the world what they built with Python!</mark>

***

**Willkommen! ·** **Welcome!**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Die Lehrerin teilt Highlights aus der 9-wöchigen Reise mit dem Publikum.

<mark style="color:$info;">🇬🇧 English</mark>

Teacher shares highlights from the 9-week journey with the audience.

***

**Präsentieren! · Present!**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Jede Schülerin zeigt ihr imagiCharm-Projekt und erklärt einen Code, auf den sie stolz ist.

<mark style="color:$info;">🇬🇧 English</mark>

Each student shows their imagiCharm project and explains one piece of code they're proud of.

***

**Galerie-Rundgang! · Gallery Walk!**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Schülerinnen tragen ihre imagiCharms und unterhalten sich mit Eltern und dem ReDI-Team.

<mark style="color:$info;">🇬🇧 English</mark>

Students wear their imagiCharms and mingle with parents and the ReDI team.

***

**Feiern! · Celebrate!**

<mark style="color:$info;">🇩🇪 Deutsch</mark>

Zertifikate werden vergeben. Gruppenfoto. Du bist jetzt offiziell eine Python-Programmiererin!

<mark style="color:$info;">🇬🇧 English</mark>

Certificates awarded. Group photo. You are officially a Python coder!

</details>
