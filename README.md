# Intrument muzical controlat prin intensitatea luminoasa
Senzorul ALS al telefonului produce semnalele sonore si vizuale. Datele preluate de la senzori sunt transformate in mesaje de tip OSC, fiind transmise in Max.

## Instalare
Se descarca arhiva si se instaleza pe smartphone aplicatia Sensors2OSC. Host-ul aplicatie este adresa IPv4 al calculatorului.

## Utilizare
1. Se deschide fisierul"Proiect final.maxpat"
2. In aplicatia Sensors2OSC, se activeaza butonul "Send data" si "Light".
3. Se apasa butonul "Play" (difuzorul)
4. Se apasa butonul 1 X
5. Se apasa butonul 2 X
6. Ne asiguram ca avem deschisa fereastra "screen"
7. Se apasa butonul "basis noise.simplex"
8. Cu ajutorul unui led sau unei lanterne se lumineaza ecranul telefonului

Legenda butoane
Negru = Oprit
Alb = Pornit

## Istoric

(13.05) Crearea efectelor sonore

(3.06) Crearea efectelor vizuale

(11.06) Optimizare

## Link-uri
Basic Synthesizer https://youtu.be/TOtzaJBKhfM
Deformation of Shape https://www.youtube.com/watch?v=Folzepz9ioE


# Dezvoltarea proiectului

Pentru început:

1. Creează-ți cont pe Github
2. Download și install [Github Desktop](https://desktop.github.com/)
3. Citește [acest ghid](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) și ține la îndemână [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet).

Apoi, procesul este următorul (inspirat de [aici](https://cs.anu.edu.au/courses/comp1720/deliverables/05-major-project/#submission-process)):

1. *fork* al acestui template către propriul tău cont de Github

![](assets/fork.gif)

_(dacă preferi cumva ca repo-ul să nu fie vizibil de către public, îl poți seta ca Private din Settings - "Change visibility". Atunci trebuie să mă adaugi drept colaborator, ca eu să am acces.)_

2. *clone* al repo-ului din Github Desktop pentru a-l downloada local

![](assets/clone.gif)

3. *commit* și *push* pe măsură ce lucrezi la proiect. Ultima versiune push-ată pe server înainte de deadline va conta pentru evaluare.

![](assets/commit.gif)

## Elemente obligatorii

1. Acest readme completat. Titlu, descriere, mod de utilizare, istoric, link-uri utile.

   Poți include și imagini și chiar [gif-uri animate](https://www.screentogif.com/), sau link-uri către materiale audio/video.
   
   Vezi [aici](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) mai multe sugestii.

2. [Declarația de originalitate](statement-of-originality.yml) completată. Tot ce nu este inclus acolo va fi considerat 100% contribuție proprie.

    *(formatul este adaptat de [aici](https://gitlab.cecs.anu.edu.au/comp1720/2018/comp1720-2018-major-project/-/blob/master/statement-of-originality.yml). Da, este un pic ironic să refolosim un doc [de altundeva](https://cs.anu.edu.au/courses/comp1720/resources/faq/#how-do-i-fill-out-my-statement-of-originality), dar menționăm sursa deci nu este plagiat!)*

3. Proiectul în sine. Tot codul trebuie să fie prezent, proiectul trebuie să poată rula conform instrucțiunilor din readme. Dacă e nevoie de asset-uri mari (sunete, video etc), [folosește Git LFS](https://git-lfs.github.com/) sau include link de download în instrucțiunile de instalare.

