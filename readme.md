### HSR Frontend Enginieering CAS 2016 Rapperwil/SG Switzerland
Course: 4.05.2016 - 20.12.2016
___
###What is Frontend Engineering?

[Nate Koechley: Professional Frontend Engineering](https://www.youtube.com/watch?v=B9n3Fy7rJmA)

___
###Front End Development is Development
  GEOFF GRAHAM // JULY 24, 2015

There is some sentiment out there that front end development isn't real development. It's a swaggering, trollish sentiment. Still, it's fun to puff our chests back sometimes. Let's try to put a point on why front end development is every bit as difficult and worthy of the title as any other subset.


This is a continuation of my post last week on how the expected skills of a front end developer are hard to nail down and how different we all can be. That post struck a chord with a good chunk of readers, and the comments that came in were full of interesting stories and experiences about what front end development means in both the technical and personal sense.

The practice of front end development is similar to playing the bass: it's easy to learn but difficult to master. There is a lot more to it than HTML and CSS (which are plenty difficult onto themselves).

Chris posed the question on Twitter in fill-in-the-blank form:

Front end development is hard because _________.

— Chris Coyier (@chriscoyier) July 16, 2015
And while the majority of responses were certainly entertaining and LOL-worthy, there were some nuggets of wisdom in there as well. Let's take a look at the common themes that make front-end development, uh, development!

###We have to deal with cross browser compatibility.

Inconsistent browser behaviour

— Nathaniel Flick (@nathanielflick) July 16, 2015
This was far and away the most cited gripe in the group. While Internet Explorer continues to be the brunt of most jokes, every browser has its own quirks that often require special development techniques to overcome.

It's rather expected of us that we know how to build websites that can work cross-browser. We should know what browsers support what and how to debug and overcome browser-specific issues. We should know how to do emulate or otherwise test on a variety of browsers.

We should know tools that help us with cross-browser problems either automatically or enable us to write code to handle situations of support and nonsupport of features. We should know how to do fallbacks. We should know about progressive enhancement and graceful degradation.

Cross browser compatibility is a hugely complex development task.

###Oh my, all those devices!

Varying screen sizes and browsers.

— Nicholas Bumgarner (@NickBumgarner) July 16, 2015
In addition to dealing with browser inconsistencies, front end developers are also charged with developing for as many screen sizes, screen orientations, pixel densities, and input types as possible.

The burden of the massive landscape of different screens, browsers, and capabilities lies most heavily on front end developers.

###Frameworks, libraries, preprocessing, dependencies, plugins...

So many new things everyday and no idea what will become standard.

— dean (@visualcookie) July 16, 2015
All the lame frameworks out there

— Rick Blalock (@rblalock) July 20, 2015
It used to be that linking up a stylesheet and maybe a JavaScript file in the HTML was all that was needed to start designing and building a site. In fact, that's still the baseline.

Today's development feels a lot different. The toolchain is a lot thicker. We're making choices about build processes, which libraries to use, what languages to write in, how invested in future syntaxes we want to be, how much we want to depend on frameworks, which third-party tools make sense and feel safe to use.

Not only is it fatiguing to think about the choices, it's increasingly difficult to know what the best choices are and if these choices are smart in the long term.

There are just as many choices, or more, at the front end level of development than there are anywhere else. Not to mention the landscape moves extremely quickly.

###We're the bridge between visual designers, back end developers, and other disciplines.

because it doesn't feel entirely "front-end" anymore

— Ara Abcarians (@ItsMeAra) July 17, 2015
Many of today's frameworks and CMS's, straddle the line between lots of different disciplines. Front end developers are right in the middle of it all. We're ultimately responsible for design—how the site looks. We're helping content people ensure they have what they need and they give us what we need. We're working in templates prying out the data we need in the formats we need. We're handling user input and ensuring it funneling where it goes for more back end concerns.

You get confused between who you are - programmer or a designer

— Priyanka N Majumder (@PriyankaNM) July 17, 2015
The chain of blame starts with front end

— Chris (@chrisdebelen) July 16, 2015
Not only do we sit in the intersection of a lot of disciplines, there is some expectation that we know enough back end languages to be useful. You'd be pretty sorry WordPress developer if you didn't know any PHP. You wouldn't be very useful on a Rails project if you didn't know any Ruby or Rails conventions at all. The more you know, the more agile and self-sufficient you can be for your team.

###Everybody and their dentist thinks they can do it.

It's easy, make it like this..wait-now like this...ok now that we're done, can we change everything to this? it's easy...

— Andrew League (@aleague888) July 16, 2015
The barrier to entry for front end development is fairly low. Everyone has heard of HTML. They "know enough to be dangerous" as it were. Because that barrier is low and because it so easy to dabble, it makes sense people assume there isn't that much to know and that front end development isn't particularly difficult.

###Naming things. And we have to name a lot of things.

You have to name things.

— Stuart Robson (@StuRobson) July 16, 2015
I imagine you've heard the maxim about naming things being one of the hardest problems in computer science. Us front enders are naming things all the time. Class names and IDs, data attributes, file names, communicating patterns with your team. It's endless. It feels like there are dozens of name choices on an average day.

Not to mention the task of copywriting often falls to us, which isn't quite naming but is in a similar vein of difficulty.

###"The right way" and "the wrong way" aren't as cut and dry as with back end development.

No standard production pipeline. No reference browser implementation. No right answers, but tons of wrong ones.

— Pelle Bjerkestrand (@pcbjerkestrand) July 16, 2015
In back end development, if what you are expecting to happen happens, you've succeeded. Surely they are different ways to get there, some better than others. But in front end development, the paths to completing a task seem endless. Even if you've seemingly succeeded, it can feel like just a matter of time until a bug is found in how you've done it.

###CSS is very hard to test.

Back end languages (and even JavaScript) can use unit testing and integration testing to help make sure the code works as expected. CSS has no such luxury. There are certainly people trying and there is some information and tools out there. But none of it is all that great and there are very few success stories.

Bugs can be subtle, confusing, and unexpected. Worse, a seemingly little change may have an adverse effect in an unexpected place where you don't notice until it's too late.

There are linting tools, which help a little. There are some styleguide enforcement tools, but they don't really help enforce more important things like adherence to naming standards.

Front end developers need to hold a very strong understanding of the entire website in their head in order to be most effective and efficient.

###JavaScript is just as complex as any other programming language. It's weird and hard.

JavaScript is front end development. JavaScript is programming. Programming is part of software development. Software development is hard.

###Performance is 80% on our shoulders.

The rule of thumb is that 20% of the waiting for a website to load is from back end concerns. Once HTML document has arrived, the rest of loading time is the concern of front end developers. What resources are loaded, how many resources are loaded, how optimized they are, in what fashion they load in and how that feels, etc.

###It's where accessibility happens.

Building sites that are visually stunning is one thing and the accessibility of them is another. Designers care very much how users interact with a site and that might not always be a visual interaction. Designing and developing for disabilities is a discipline onto itself, but is most tightly tied to front end development. Accessibility has its own set of specifications that sadly aren't typically taught along with traditional front end development training.

###It's hard to hire for.

Front end developers are typically the hardest seats to fill.


___
###9 Gründe, warum das Frontend so anspruchsvoll ist wie das Backend

 28. Juli 2015  Kypriani Sinaris
shutterstock_183150020
©Shutterstock/igor.stevanovic
Kann man Frontend-Entwicklung mit Backend-Entwicklung vergleichen? Ja, findet Geoff Graham. In einem Blogpost macht der Web Designer seinem Ärger über unterschätzte Frontend-Arbeit Luft: Seiner Meinung nach umfasst die Arbeit von Frontend-Entwicklern weitaus mehr als ein bisschen HTML. Ein Entwickler des Frontends müsse mit vergleichbaren Herausforderungen kämpfen wie sein Kollege im Backend. Welche sind das?
In seinem Blogpost vergleicht Geoff Graham das Erlernen der Frontend-Entwicklung mit dem Lernen des Bass: Der Bass sei zwar leicht zu lernen, aber schwer zu beherrschen. Und so gäbe es viel mehr als nur HTML oder ein bisschen CSS, was der Frontend-Entwickler lernen müsse. Auf Reddit entfachte sein Post eine gewaltige Diskussion, in der sich aber vor allem Zustimmung für die Meinung des Entwicklers finden lässt. Die folgenden 9 Gründe sollen aufzeigen, warum auch Frontend-Entwicklung eben Entwicklung ist, nach dem Motto „JavaScript is front end development. JavaScript is programming. Programming is part of software development. Software development is hard”. Welche Grenzen muss ein Frontend-Entwickler überwinden?

1. Browser-Grenzen

Frontend-Entwickler müssen in ihrer Arbeit die Cross-Browser-Kompatibilität beachten. Wie Geoff Graham anmerkt, ist die Cross-Browser-Programmierung eine hochkomplexe Aufgabe in der Entwicklung, da jeder Browser mit eigenen Kniffen ausgestattet ist. Dabei würde von den „Frontendlern“ aber erwartet, dass sie für all diese Kniffe bereits die Lösung kennen. Mit diesem Punkt scheint Geoff Graham wohl auch bei den Programmierern auf Reddit Salz in die Wunde zu streuen: Der Kommentator ABC_AlwaysBeCoding geht dabei recht pragmatisch an die Sache heran:

Yeah but who wants to manually troubleshoot CSS rendering issues across different browsers? I sure as hell don’t. Which is why I pushed for backend dev.

2. Gerätegrenzen

Es gibt eine große Auswahl an verschiedenen Bildschirmgrößen. Und so müssen Frontend-Entwickler auch für die verschiedenen Anforderungen gewappnet sein. Ähnlich komplex wie die Cross-Browser-Kompatibilität ist auch die Programmierung für jede dieser Bildschirmgrößen mit Herausforderungen wie unterschiedlicher Pixel-Dichte, Input Types usw. verbunden und gehört zu den Aufgaben eines Frontend-Entwicklers.

3. Technische Grenzen

Wie Geoff Graham betont, sind Frontend-Entwickler dem täglichen Erscheinen neuer Frameworks, Libraries, Plug-ins und Co. „ausgesetzt“. Damit ginge eine viel größere Auswahl und damit Entscheidungsschwierigkeiten einher, als in der Backend-Entwicklung. Welche Library ist für das aktuelle Projekt die beste Wahl? Geoff Graham beschreibt die Auswahl an immer neuen Technologien als ermüdend und als immer schwerer werdenden Prozess, vor allem, wenn Entscheidungen auf lange Sicht getroffen werden müssen.

4. Disziplinäre Grenzen

Frontend-Entwickler seien die Vermittler zwischen Backend-Entwicklern, Visual Designern und anderen Disziplinen. So müssen sie nicht nur interdisziplinär vermitteln, sondern auch arbeiten: Ein WordPress-Entwickler sollte auch ein paar Kenntnisse in PHP aufweisen oder ein Frontend-Entwickler in einem Rails-Projekt sollte auch etwas über Ruby on Rails wissen, so Geoff Graham. Diese interdisziplinäre Herausforderung beschreiben auch Frontend-Entwickler auf Twitter, nachdem Geoff Graham sie über die Plattform bat, den Satz „Front end development is hard because___“ zu vervollständigen. So sagt Priyanka N Majumder:

You get confused between who you are – a programmer or a designer

Auch auf Reddit beschreibt der User barrypickles die Situation vieler Frontened-Entwickler, zum Teil auch das Wissen der anderen Expertengruppen beherrschen zu müssen.

A good front end developer is hard to find because a good front end developer is a designer, UX, and developer all in one.

5. Eigene Grenzen

Dies mag eine sehr persönliche Wahrnehmung Geoff Grahams sein: Jeder, wirklich jeder denke, er könne die Frontend-Entwicklung übernehmen. Die Hürde sei relative gering, denn jeder habe schon einmal von HTML gehört. Auf Twitter kommentiert Andrew League die Attitüde, mit der „Nicht-Frontendler“ an ihn herantreten:

it’s easy, make it like this..wait-now like this…ok now that we’re done, can we change everything to this? it’s easy…

Aber nur, weil das Frontend möglicherweise leichter zu erfassen scheint als das Backend, heißt das eben nicht, dass auch jedem die erfolgreiche Programmierung glückt, so Geoff Graham.

6. Kreative Grenzen

Das Benennen von Dingen kann eine gewaltige Herausforderung darstellen, JAXenter.de berichtete bereits über dieses Phänomen. Und auch Geoff Graham findet, dass dies zu den schwierigsten Aufgaben eines jeden Entwicklers gehört und zwar nicht nur im Backend, sondern auch im Frontend. Auch wenn es um Copywrite-Fragen ginge, wären die Entwickler des Frontends oft die erste Anlaufstelle. Das Benennen von Dingen sei eine tägliche Herausforderung des Jobs.

7. Korrektur-Grenzen

Im Backend scheint der Weg einfach: Wenn das eintritt, was man erwartet hat, dann war das Programmieren erfolgreich, so Geoff Graham. Auch wenn es hier mehrere Wege geben mag, die zum Ziel führen, seien diese doch im Vergleich zum Frontend überschaubar – der Weg im Frontend sei dagegen quasi endlos. Auch wenn man meint, fertig zu sein, so gäbe es immer etwas zu fixen oder zu verändern. Die fehlende „Standard-Produktions-Pipeline“ für Frontend-Entwickler sei das Problem, findet Pelle Bjerkestrand auf Twitter. Eine streitbare Aussage, denn auch “Backendler” kennen dieses Problem.

8. Testing-Grenzen

„CSS is very hard to test“ behauptet Geoff Graham. Viele Programmiersprachen des Backends könnten auf Unit- und Integration Tests zurückgreifen, um ihr Coding-Ziel zu erreichen. CSS habe diese Möglichkeit aber nicht, so würden scheinbar kleine Veränderungen schon zu Problemen führen, die erst auf den dritten oder vierten Blick entdeckt werden könnten, wenn überhaupt. Daher stünden Frontend-Entwickler vor der Herausforderung, stets den Überblick über das Projekt und jede gemachte Änderung zu haben, in Situationen, in denen andere Entwickler sich auf Testing-Methoden verlassen können.

9. Accessibility-Grenzen

Dem Bauen visuell sehr ansprechender Seiten steht meist die Accesibility der Seiten gegenüber. Die Art und Weise, wie Besucher der Seite mit selbiger interagieren, ist eine Disziplin für sich. Diese würden viele Frontend-Entwickler aber erst im Selbststudium erlernen, da Accessibility kein Teil der traditionellen Front-End-Ausbildung sei, so Geoff Graham. Gerade ein Design, welches besonderen Anforderungen unterliegt, wie beispielsweise die Entwicklung einer Seite für sehbehinderte Menschen, stelle eine besondere Herausforderung dar. Eine zusätzliche Herausforderung für die Frontend-Programmierung, findet der Blogger.

Fazit

Zugegeben: Der Blogpost ist natürlich subjektiv. Betrachtet man aber die Kommentare dazu, sowohl auf Twitter, Reddit, als auch innerhalb des Blogposts selbst, so scheint es zumindest keine Einzelmeinung zu sein. Zwischen technischen, kreativen und kommunikativen Herausforderungen müssen Frontend-Entwickler ihren Platz im Produktionsablauf finden. Anders als bei „Backendlern“ scheint sich dieser Platz von Projekt zu Projekt und von Unternehmen zu Unternehmen unterschiedlich darzustellen und die Programmieranforderungen unterschiedlich groß zu sein. Unterm Strich lässt sich also kaum sagen, ob der Beruf des Frontend-Entwicklers per se unterschätzt wird. Die simple Tautologie eines Kommentators fasst die Diskussion recht gut zusammen: “A developer is a developer is a developer. Different skills, same job.”