<strong>David Vílchez</strong> - <em>Podcasts</em> <sup><sub>09/06/2013 05:00:00</sub></sup>

A petición de Manuel os comparto este episodio de 32minutos, aviso: no sólo para aprendices :) TranslateShow original text 06×03 Ángel Java López - 32minutos.net


<strong>Nico Cortés</strong> - <em>Katas</em> <sup><sub>09/06/2013 05:00:00</sub></sup>

Aquí dejo mi kata de las nReinas. Aunque funciona, hay un montón de cuestiones que me han generado dudas. Así que cuando pueda, la retomaré para afrontarla de nuevo. Para hacer la kata en lineas generales, seguí el siguiente proceso * Casillas, Reinas, tablero * Generador de tableros 1 - Square (casilla donde se ubica una reina). Test y clase. - Esta clase gestiona tanto la ubicación (rank (fila), file (columna), - como la detección de posición relativa entre casillas: misma fila, misma columna, misma diagonal 2 - Queen: Contempla tanto - Una reina esta una casilla - Es responsible de saber cuando puede amenzar a otra reina 'isThreateningTo(Piece piece)' 3 - Piece: pieza genérica del ajedrez. He generado está superclase para Queen para unificar tanto los estados como comportamiento que pueda compartir cualquier pieza del ajedrez: - Toda pieza está úbicada en una casilla - Toda pieza tiene que saber cuando puede amenazar a cualquier otra 'isThreateningTo(Piece piece)' 4 - Board: tablero. Incluye: - Lista de piezas que están en el mismo (no almaceno las casillas, si no las piezas) - isSafe(Piece): metodo para saber si es posible poner una nueva pieza en el tablero sin que está se vea amenazada por alguna de las piezas que ya hay en el tablero. 5 - NQuennsBoardsFactory: clase para generar los tableros posibles para albergar nReinas sin que se ataquen entre ellas. Toda opinión será bien recibida. TranslateShow original text nQueensKata github.com


<strong>Manuel Rivero</strong> - <em>Katas</em> <sup><sub>08/06/2013 05:00:00</sub></sup>

StringCalculator kata en C++ para probar Igloo un framework de BDD para C++. <a target="_blank" href="https://bitbucket.org/trikitrok/stringcalculatokatacpp/src">https://bitbucket.org/trikitrok/stringcalculatokatacpp/src</a> Igloo (http://igloo-testing.org/) tiene buena pinta, las specs se leen bastante bien, aunque el Eclipse se vuelve loco con la sintaxis.


<strong>Manuel Rivero</strong> - <em>Readers Club</em> <sup><sub>08/06/2013 05:00:00</sub></sup>

Test Driven <a target="_blank" href="http://www.manning.com/koskela/">http://www.manning.com/koskela/</a> Empecé a leerlo hace poco y me parece muy bueno. Recuerdo que Carlos Blé nos dijo en un curso suyo al que asistí hace unos meses que era "el libro que le hubiera gustado escribir" (Carlos corrígeme si lo estoy recordando mal). Con esta referencia empecé a leerlo con unas expectativas muy altas y no me está defraudando. Solo leeré los capítulos más generales (partes 1 y 3) sobre TDD y ATDD, ya que la parte 2 está centrada en aplicar TDD en tecnologías Java específicas (estos son los capítulos de la parte 2: 5 Test-driving web components; 6 Test-driving data access; 7 Test-driving the unpredictable; 8 Test-driving Swing). Si esta parte es tan buena como la primera, creo que puede ser un recurso muy útil para los que trabajan habitualmente con Java. Supongo que Carlos Blé podría darnos un poco más de detalles sobre esto. TranslateShow original text Manning: Test Driven manning.com


<strong>Manuel Rivero</strong> - <em>Katas</em> <sup><sub>08/06/2013 05:00:00</sub></sup>

Prime factors kata in JavaScript <a target="_blank" href="https://bitbucket.org/trikitrok/primefactorkatainjavascript/src">https://bitbucket.org/trikitrok/primefactorkatainjavascript/src</a> trikitrok / PrimeFactorKataInJavaScript / source / — Bitbucket Clone in SourceTree. SourceTree is a free Windows client by Atlassian for Git and Subversion. SourceTree is a free Mac client by Atlassian for Git, Mercurial, and Subversion. Overview · Source · Commits · Pull requests · Issues · Wiki · Downloads. Branch default ... bitbucket.org


<strong>Pablo Jimeno Pérez</strong> - <em>XP, Lean & Agile</em> <sup><sub>08/06/2013 05:00:00</sub></sup>

This is basically a 1 day product ownership course compressed into a 15 minute animated presentation. More info: <a target="_blank" href="http://blog.crisp.se/2012/10/25/henrikkniberg/agile-product-ownership-in-a-nutshell">http://blog.crisp.se/2012/10/25/henrikkniberg/agile-product-ownership-in-a-nutshell</a> Agile Product Ownership in a Nutshell


<strong>Manuel Rivero</strong> - <em>Legacy Code</em> <sup><sub>07/06/2013 05:00:00</sub></sup>

Seventeen Secrets of the Great Legacy Makeover Masters, Brian Foote (@bigballofmud) <a target="_blank" href="http://www.infoq.com/presentations/17-Secrets-Legacy-Code">http://www.infoq.com/presentations/17-Secrets-Legacy-Code</a>


<strong>Gabriel Moral</strong> - <em>Clean Code</em> <sup><sub>07/06/2013 05:00:00</sub></sup>

<a target="_blank" href="http://vimeo.com/34459261">http://vimeo.com/34459261</a> Porqué Cervantes programaba mejor que tú vimeo.com


<strong>Manuel Rivero</strong> - <em>Domain Driven Design</em> <sup><sub>07/06/2013 05:00:00</sub></sup>

Folding together DDD & Agile <a target="_blank" href="http://skillsmatter.com/podcast/design-architecture/folding-together-ddd-agile">http://skillsmatter.com/podcast/design-architecture/folding-together-ddd-agile</a> Skills Matter : DDD eXchange 2010: Eric Evans on Folding tog skillsmatter.com


<strong>Manuel Rivero</strong> - <em>Courses, events, conferences,...</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

En Barcelona: <a target="_blank" href="http://www.barcelonajug.org/2013/06/workshop-continuous-delivery.html">http://www.barcelonajug.org/2013/06/workshop-continuous-delivery.html</a>


<strong>Manuel Rivero</strong> - <em>Clean Code</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Me encantaría leer su opinión sobre esta serie, este es el primero: My relationship with SOLID - Starting with S <a target="_blank" href="http://codeofrob.com/entries/my-relationship-with-solid---starting-with-s.html">http://codeofrob.com/entries/my-relationship-with-solid---starting-with-s.html</a> TranslateShow original text My relationship with SOLID - Starting with S Rob Ashton's blog and various other things. Javascript, C#, testing, whatever. codeofrob.com


<strong>Manuel Rivero</strong> - <em>Clean Code</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Is Design Dead? Martin Fowler <a target="_blank" href="http://martinfowler.com/articles/designDead.html">http://martinfowler.com/articles/designDead.html</a> Is Design Dead? martinfowler.com


<strong>Alfonso Burgos</strong> - <em>XP, Lean & Agile</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Originally shared by Alfonso Burgos gestión de proyectos agile - kanban con <a target="_blank" href="https://trello.com/">https://trello.com/</a> take the tour : <a target="_blank" href="https://trello.com/">https://trello.com/</a>tour alternativas : <a target="_blank" href="http://www.atlassian.com/software/greenhopper/overview/kanban">http://www.atlassian.com/software/greenhopper/overview/kanban</a> TranslateShow original text Kanban Process Management | Atlassian GreenHopper atlassian.com


<strong>Manuel Rivero</strong> - <em>Readers Club</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

<a target="_blank" href="http://shop.oreilly.com/category/deals/ux.do?code=WKUXDSN&imm_mid=0a9eb1&cmp=em-prog-books-videos-user-experiences-wkuxdsn-direct">http://shop.oreilly.com/category/deals/ux.do?code=WKUXDSN&imm_mid=0a9eb1&cmp=em-prog-books-videos-user-experiences-wkuxdsn-direct</a> Save 50% on UI/UX Ebooks - Deals - O'Reilly Media shop.oreilly.com


<strong>Manuel Rivero</strong> - <em>TDD - BDD - Testing - Monitoring</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Fractal TDD, Steve Freeman <a target="_blank" href="http://skillsmatter.com/podcast/agile-scrum/fractal-tdd-using-tests-to-drive-system-design">http://skillsmatter.com/podcast/agile-scrum/fractal-tdd-using-tests-to-drive-system-design</a>


<strong>Nico Cortés</strong> - <em>Tools - CI - CD</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Videodemo interactivo por web muy bueno para aprender a utilizar Git TranslateShow original text Learn Git Branching bit.ly


<strong>Nico Cortés</strong> - <em>Refactoring</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Refactoring techniques. Un buen resumen sobre las diferentes técnicas de refactoring, clasificadas por tipos, así como sus usos y smells asociados. TranslateShow original text www.thekua.com/publications/RefactoringCheatSheet.pdf thekua.com


<strong>Manuel Rivero</strong> - <em>Clean Code</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Naming From the Outside In <a target="_blank" href="https://www.facebook.com/notes/kent-beck/naming-from-the-outside-in/464270190272517">https://www.facebook.com/notes/kent-beck/naming-from-the-outside-in/464270190272517</a>


<strong>Alfonso Burgos</strong> - <em>Interesting Posts and Papers</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Alan Turing: El descifrado de la máquina Enigma blogs.elpais.com


<strong>Alfonso Burgos</strong> - <em>Readers Club</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

como referencia para el anterior ^_^ TranslateShow original text Decoding the Univers - 9780143038399 - ATRIL - La Central - Barcelona - 2011 lacentral.com


<strong>Manuel Rivero</strong> - <em>Professional matters</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

How much will you be worth in five years? Your Personal Technology Roadmap <a target="_blank" href="http://www.contentedcoder.com/2012/09/creating-your-personal-technology.html">http://www.contentedcoder.com/2012/09/creating-your-personal-technology.html</a> How much will you be worth in five years? Your Personal Technology Roadmap contentedcoder.com


<strong>Manuel Rivero</strong> - <em>TDD - BDD - Testing - Monitoring</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Classic TDD or "London School"? Jason Gorman (@jasongorman) <a target="_blank" href="http://codemanship.co.uk/parlezuml/blog/?postid=987﻿">http://codemanship.co.uk/parlezuml/blog/?postid=987﻿</a>


<strong>Manuel Rivero</strong> - <em>Clean Code</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Small Design Up Front & XP <a target="_blank" href="http://sivasu-venkat.blogspot.com.es/2011/11/small-design-up-front-xp.html">http://sivasu-venkat.blogspot.com.es/2011/11/small-design-up-front-xp.html</a> Small Design Up Front & XP Well, most of you would have definitely heard about Big Design Up Front (BDUF). It is typical in a waterfall-model based software project. We (devs) spend around 30% of the overall project effort during the design stage. My f... sivasu-venkat.blogspot.com.es


<strong>Nico Cortés</strong> - <em>Courses, events, conferences,...</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

Taller gratuito de Integración Continua con Java el 21 junio - Madrid TranslateShow original text javaHispano - Portada - Taller gratuito de Integración Continua con Java bit.ly


<strong>Manuel Rivero</strong> - <em>Clean Code</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

A GOOD NAME IS ABOUT AN IDEA, NOT AN IMPLEMENTATION <a target="_blank" href="http://www.cs.uni.edu/~wallingf/blog/archives/monthly/2012-11.html#e2012-11-06T15_34_58.htm">http://www.cs.uni.edu/~wallingf/blog/archives/monthly/2012-11.html#e2012-11-06T15_34_58.htm</a>


<strong>Alfonso Burgos</strong> - <em>Readers Club</em> <sup><sub>06/06/2013 05:00:00</sub></sup>

por si os animáis Programming the universe - 9781400033867 - ATRIL - La Central - Barcelona - 2011 lacentral.com


<strong>Alfonso Burgos</strong> - <em>Tools - CI - CD</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

Originally shared by Alfonso Burgos browser app that turns your browser into a worker for distributed computation tasks. See PDF : <a target="_blank" href="http://staff.science.uva.nl/~delaat/posters/2013-03-09-WeevilScout.pdf">http://staff.science.uva.nl/~delaat/posters/2013-03-09-WeevilScout.pdf</a> WeevilScout Version: 0.2a, BogoMFlops: N.A. Cluster Size: N.A. State: Idling. Completed Jobs: 0. Donated Time: 0s ... elab.lab.uvalight.net


<strong>José E. Rodríguez</strong> - <em>Interesting Posts and Papers</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

<a target="_blank" href="http://kunststube.net/encoding/">http://kunststube.net/encoding/</a> What Every Programmer Absolutely, Positively Needs to Know About Encodings and Character Sets to Work With Text kunststube.net


<strong>Manuel Rivero</strong> - <em>TDD - BDD - Testing - Monitoring</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

The Pragmatics of TDD, Robert C. Martin <a target="_blank" href="http://blog.8thlight.com/uncle-bob/2013/03/06/ThePragmaticsOfTDD.html">http://blog.8thlight.com/uncle-bob/2013/03/06/ThePragmaticsOfTDD.html</a> The Pragmatics of TDD | 8th Light We write beautiful web applications that are durable and free of defects in workmanship. blog.8thlight.com


<strong>Manuel Rivero</strong> - <em>Clean Code</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

The Liskov Substitution Principle Demystified, J. B. Rainsberger <a target="_blank" href="http://blog.thecodewhisperer.com/2013/01/08/liskov-substitution-principle-demystified/">http://blog.thecodewhisperer.com/2013/01/08/liskov-substitution-principle-demystified/</a>


<strong>Manuel Rivero</strong> - <em>Learning</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

Patterns as a source of freedom, Eugene Wallingford (@wallingf) <a target="_blank" href="http://www.cs.uni.edu/~wallingf/blog/archives/monthly/2005-03.html#e2005-03-30T10_44_45.htm">http://www.cs.uni.edu/~wallingf/blog/archives/monthly/2005-03.html#e2005-03-30T10_44_45.htm</a>


<strong>Vicente Monrabal</strong> - <em>Clean Code</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

Colección de artículos, vídeos y presentaciones para construir y mantener proyectos javascript. <a target="_blank" href="http://superherojs.com/">http://superherojs.com/</a> TranslateShow original text Superhero.js Superhero.js. Creating, testing and maintaining a large JavaScript code base is not easy — especially since great resources on how to do this are hard to find. This page is a collection of the best articles, videos and presentations we've found on the topic. Follow us on Twitter, GitHub, RSS, ... superherojs.com


<strong>Manuel Rivero</strong> - <em>TDD - BDD - Testing - Monitoring</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

The Mind Killer <a target="_blank" href="http://blogs.perl.org/users/buddy_burden/2012/07/the-mind-killer.html">http://blogs.perl.org/users/buddy_burden/2012/07/the-mind-killer.html</a> The Mind-killer | Buddy Burden [] I happen to be a TDD proponent. Now, right there I've probably lost about half of you, and the rest are probably going, “okay, yeah, get on with it.” TDD is one of those things that people either love or hate. For a full meditation on the ins and outs of technical hype, I'll refer you to my ... blogs.perl.org


<strong>Alfonso Burgos</strong> - <em>XP, Lean & Agile</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

Originally shared by Alfonso Burgos Why your users hate Agile development (and what you can do about it) itworld.com


<strong>Matias Mascazzini</strong> - <em>Community</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

Gracias por aceptarme en el grupo, espero poder aportar. Saludos desde Argentina. TranslateShow original text


<strong>Manuel Rivero</strong> - <em>Professional matters</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

GitHub is the new resume, and you don’t have to be a God of Programming for it to work by Elf Sternberg <a target="_blank" href="http://www.elfsternberg.com/2013/02/28/github-resume-god-programming-work/">http://www.elfsternberg.com/2013/02/28/github-resume-god-programming-work/</a> GitHub is the new resume, and you don’t have to be a God of Programming for it to work by Elf Sternberg I've been looking for work. My last employer decided that remote didn't work well, and gave its four remote workers the options of moving to California or accepting layoffs. I accepted the layoff. I was worried about looking for work; even a year ago, my search took several weeks and a lot of ... elfsternberg.com


<strong>Vicente Monrabal</strong> - <em>Readers Club</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

Libro interesante sobre TDD. Aprovechad que Carlos Ble está por la comunidad ;) <a target="_blank" href="http://www.dirigidoportests.com/el-libro">http://www.dirigidoportests.com/el-libro</a> TranslateShow original text DirigidoPorTests dirigidoportests.com


<strong>Manuel Rivero</strong> - <em>Interesting Posts and Papers</em> <sup><sub>05/06/2013 05:00:00</sub></sup>

THELONIOUS MONK TEACHES SOFTWARE DESIGN <a target="_blank" href="http://www.cs.uni.edu/~wallingf/blog/archives/monthly/2013-02.html#e2013-02-25T16_07_20.htm">http://www.cs.uni.edu/~wallingf/blog/archives/monthly/2013-02.html#e2013-02-25T16_07_20.htm</a> Knowing and Doing: February 2013 Archives cs.uni.edu


<strong>Manuel Rivero</strong> - <em>Courses, events, conferences,...</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

Para los que vayan a estar en Barcelona el próximo 10 de Junio <a target="_blank" href="http://barcelona.agile-spain.org/2013/06/software-architecture-and-the-balance-with-agility-lunes-10-junio-18h/">http://barcelona.agile-spain.org/2013/06/software-architecture-and-the-balance-with-agility-lunes-10-junio-18h/</a> TranslateShow original text » Software architecture and the balance with agility – Lunes 10 Junio, 18h Agile Barcelona barcelona.agile-spain.org


<strong>Gabriel Moral</strong> - <em>Katas</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

Kata realizada con SpecFlow para los test de aceptación, para hacer mocking se utiliza la librería Moq. <a target="_blank" href="https://github.com/gabrielmoral/AcceptanceTestWithSpecFlow">https://github.com/gabrielmoral/AcceptanceTestWithSpecFlow</a> TranslateShow original text AcceptanceTestWithSpecFlow github.com


<strong>Gabriel Moral</strong> - <em>Tools - CI - CD</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

Para hacer BDD. <a target="_blank" href="http://www.specflow.org/">http://www.specflow.org/</a> Es muy parecido a Cucumber y se integra con Visual Studio. TranslateShow original text SpecFlow - Pragmatic BDD for .NET specflow.org


<strong>Paulo Clavijo</strong> - <em>TDD - BDD - Testing - Monitoring</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

En la linea con lo visto hoy en clase de QA, os dejo una presentación sobre ATDD que preparé para las tardes de formación de mi empresa. Saludos. TranslateShow original text ATDD - Desarrollo Dirigido por Test de Aceptación es.slideshare.net


<strong>Manuel Rivero</strong> - <em>Community</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

¿Las charlas las ponemos todas juntas o por temática? Al principio las estaba poniendo todas juntas pero si que quizás sería mejor ponerlas por temática como ha hecho Paulo. ¿Qué les parece? TranslateShow original text


<strong>Manuel Rivero</strong> - <em>Architecture/Design</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

Hexagonal architecture in JavaScript <a target="_blank" href="http://css.dzone.com/articles/hexagonal-architecture">http://css.dzone.com/articles/hexagonal-architecture</a> Hexagonal architecture in JavaScript | Web Builder Zone The goal: unit testing JavaScript code, in isolation from frameworks, the server side and the DOM.To pursue this goal, the code under development must contain... css.dzone.com


<strong>Miguel Angel Fernández</strong> - <em>XP, Lean & Agile</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

Scaling Agile at Spotify dl.dropboxusercontent.com/u/1018963/Articles/SpotifyScaling.pdf dl.dropboxusercontent.com


<strong>Manuel Rivero</strong> - <em>Architecture/Design</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

Estos son los links que encontré sobre arquitectura hexagonal el verano pasado: <a target="_blank" href="http://garajeando.blogspot.com.es/2012/08/ports-and-adapters.html">http://garajeando.blogspot.com.es/2012/08/ports-and-adapters.html</a> TranslateShow original text Ports and Adapters In Growing Object-Oriented Software, Guided By Tests its authors explain how they grow systems a slice of functionality at a time. As the code scales up, they need to structure the functionality so they can continue to unders... garajeando.blogspot.com.es


<strong>Manuel Rivero</strong> - <em>Courses, events, conferences,...</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

Curso DesignPatterns en Barcelona por Xavi Gost dia 11 de 3 a 8, 70 euros, 20 plazas.http://bit.ly/11zArTm Creo que es una gran oportunidad para ver los patrones de diseño desde la perspectiva de un gran programador. TranslateShow original text Curso beCode de Design Patterns en Barcelona 11/06 | bit.ly


<strong>Vicente Monrabal</strong> - <em>TDD - BDD - Testing - Monitoring</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

Charla de Carlos Ble sobre TDD en Javascript <a target="_blank" href="http://vimeo.com/58440569">http://vimeo.com/58440569</a> TranslateShow original text Madrid Java Script Carlos Ble vimeo.com


<strong>Manuel Rivero</strong> - <em></em> <sup><sub>04/06/2013 05:00:00</sub></sup>

<a target="_blank" href="https://plus.google.com/hangouts/_/a2c5303761cfb2ba54833cce376c56435cf13bbb?authuser=0&hl=en-GB">https://plus.google.com/hangouts/_/a2c5303761cfb2ba54833cce376c56435cf13bbb?authuser=0&hl=en-GB</a> Google+ Google+ aims to make sharing on the web more like sharing in real life. Take a look at Circles, Events and Hangouts; just a few of the things that we've been working on. plus.google.com


<strong>Manuel Rivero</strong> - <em>TDD - BDD - Testing - Monitoring</em> <sup><sub>04/06/2013 05:00:00</sub></sup>

TDD Tetris Tutorial <a target="_blank" href="https://github.com/orfjackal/tdd-tetris-tutorial">https://github.com/orfjackal/tdd-tetris-tutorial</a> orfjackal/tdd-tetris-tutorial · GitHub github.com


[Next page](index73.md)
