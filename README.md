SVT Get
==========
"Ladda ner fr�n SVT Play" in Swedish, SVT Get is a free software tool to make local cache files of SVT Play web streams, available from SVTPlay.se


Bitcoin address: 1Nt5H47TU76pFpnaX6FQQvzLoS6F4sXC3Y


Vad g�r SVT Get?
====================
Eftersom SVT Get �r fri mjukvara kan du granska k�llkoden direkt. F�r n�rvarande fungerar det genom att anv�nda sig av andra fria mjukvaror, s�som bash, curl och rtmpdump, f�r att ladda hem och tolka hemsidan SVTPlay.se.

Hos SVT Play s� finns all information man beh�ver f�r att ladda hem deras videoklipp. Det k�nns ganska sj�lvklart egentligen, men m�nga tror att "streaming" �r n�got annat �n "nedladdning" - men oavsett vad du g�r s� f�r du hem informationen till din dator. Kan du se det kan du kopiera det - allts� kan vi spara ner informationen p� din dator. Att det sedan blir en perfekt digital kopia �r bara en bonus av kopimi.
Hur laddar jag ner fr�n SVT Play?
I mjukvarans nuvarande stadie beh�ver du k�ra ett POSIX-kompatibelt operativsystem d�r man kan installera de fria mjukvarorna bash, curl och rtmpdump. Absolut mest rekommenderat �r Ubuntu Linux, ett gratis och fritt operativsystem som installeras p� en timme eller s�. Ett annat tips �r att be n�gon datorn�rd i din n�rhet att hj�lpa till.
N�r du anv�nder Linuxmilj�n beh�ver du bara ladda hem scriptet och starta det med en adress till SVT Play:

	$ wget "https://github.com/mmn/svtget/raw/master/bash/svtget"
	$ bash svtget http://svtplay.se/v/2440756/k_special/presspauseplay
	#  Bitrate      Filename
	1. 1400 kbps    GEOSEMOBIL_0603-KSPECIAL-PLAY-mp4-d-v1.mp4
	2. 320 kbps     GEOSEMOBIL_0603-KSPECIAL-PLAY-mp4-b-v1
	3. 850 kbps     GEOSEMOBIL_0603-KSPECIAL-PLAY-mp4-c-v1.mp4

	Which file do you want? [#] 3


H�r anger man sedan vilken kvalitet man ska ladda hem i. De kvaliteter som erbjuds �r samma som erbjuds p� hemsidan, d�r 2400 kbps (som ej syns i detta fall) �r HD 720P, medan 850 kbps �r den lite beh�ndigare 640x360-varianten. Filen sparas sedan i den mapp du befinner dig i (vanligtvis ~/)


Vad �r syftet?
===================

Dels politiskt. Tycker man om fri kultur och mjukvara b�r man g� med i Piratpartiet och k�mpa f�r r�tten att anv�nda, modifiera och distribuera. Alternativt aktivera sig inom ett annat parti och arbeta f�r samma m�l. Det �r informationsamh�llets framtid det handlar om - och ett blivande kunskapssamh�lle.
Fast egentligen �r syftet mest av praktiskt art. Id�n poppade upp n�r jag inte hade en tv f�r att titta p� dokument�ren Press Pause Play, som allts� visades p� SVT. Som tur �r s� har dock SVT fram�tanda i dagens tekniska samh�lle och tillg�ngliggjorde filmen p� sin hemsida, som str�mbar video. Problemet �r att str�mbar video - trots att det �r som vilken videofil som helst - ofta �r kr�ngligare att ladda ner - och detta k�nde jag var n�dv�ndigt eftersom platsen jag ville se filmen p� saknade en stabil internetuppkoppling. Och filmen fanns inte ens p� The Pirate Bay.
Syftet med scriptet �r allts� kort och gott att underl�tta en lokal cache f�r bes�kare p� SVT Play. Video som �r lagligt tillg�nglig i "str�mmande format" kan arkiveras p� den enskilda individens dator av bekv�mlighetssk�l. Rent juridiskt �r detta ett klockrent fall av privatkopiering och d�rmed helt lovligt trots dagens i �vrigt kn�ppa upphovsr�ttslagstiftning:

	Privatkopiering �r en popul�r term f�r den kopiering som �r till�ten att f�reta p� annars upphovsr�ttsligt skyddade verk. F�ruts�ttningarna f�r att f� privatkopiera anges i 12� upphovsr�ttslagen. Exempel p� privatkopiering kan vara att g�ra en kopia av en CD-skiva att anv�nda i bilen, att l�gga �ver musikfiler p� sin MP3-spelare eller dator. Man har inte r�tt att vidare distribuera privatkopierat material mer �n i en mycket begr�nsad omfattning (exempelvis till en enstaka v�n).


Vem utvecklar SVT Get?
===========================

Det ursprungliga bash-scriptet skrevs av Mikael "MMN-o" Nordfeldth, vars diverse skriverier ni kan f�lja p� blog.mmn-o.se. Utvecklingen d�refter kan f�ljas fr�n diverse forkade projekt, f�rhoppningsvis centrerat kring projektet p� GitHub.
Andra n�mnv�rda personer med relevant koppling till projektet �r bl.a. @sikevux.
Den fria mjukvaran SVTGet �r skyddad av upphovsr�ttslagen enligt GPLv3. Samtlig text tillh�rande projektet, hemsidan och s�dant �r licensierat Creative Commons Erk�nnande-DelaLika. Det �r med dessa principer upphovsr�tt b�r fungera automatiskt, men tyv�rr inte g�r. F�rhoppningen f�r framtiden �r v�l att SVT ska satsa mer p� Creative Commons, f�r d� har de r�ttigheterna att sprida vidare filmer och samh�llet beh�ver inte riskera att f�rlora sin kulturhistoria.
