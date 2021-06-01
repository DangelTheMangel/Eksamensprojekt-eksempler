# Eksamensprojekt-eksempler

Dette er opgaver inden for Begreber og fagtermer vi skal kunne i programmering til eksamen d. 	7/6-21 - 8/6-21

<h1 class="c0"
  				id="h.grlvlphpnxba">
				<span class="c5 c17">Begreber:</span>
			</h1>
			<p class="c6">
				<span class="c2">polymorfi</span>
				<span class="c4">: - Polymorfisme er et objekts evne til at antage mange former. Den mest almindelige brug af polymorfisme i OOP opst&aring;r, n&aring;r en for&aelig;ldreklassereference bruges til at henvise til et underordnet objekt. Alts&aring; som eksempel overklassen b&aelig; har underklassen tyndskid:</span>
			</p>
			<p class="c6">
				<span class="c4">B&aelig; b&aelig; = new Tyndskid();</span>
			</p>
			<p class="c6">
				<span class="c8">dette er polymorfi</span>
			</p>
			<p class="c6">
				<span class="c2">Objekt</span>
				<span class="c4">&nbsp;- Objekt er en central del af objektorienteret programmering. Et objekt er en datastruktur.</span>
			</p>
			<p class="c20">
				<span class="c14">Referencer</span>
				<span class="c3">&nbsp;- I Java er der fire typer referencer:</span>
			</p>
			<ol class="c9 lst-kix_oo6yy5woqdty-0 start"
  				start="1">
				<li class="c13 li-bullet-0">
					<span class="c3">St&aelig;rke referencer: standardtypen / klassen for referenceobjekt. Det er ethvert brugt objekt som ikke peger p&aring; null. en n&oslash;ddeskal indsamles st&aelig;rkt refererede objekter (almindelig sag, f.eks. &#39;String s = &quot;abc&quot;)</span>
				</li>
				<li class="c13 li-bullet-0">
					<span class="c3">Svage referencer: Svage referenceobjekter er ikke standardtypen / klassen for referenceobjekt, og det er dem der skal angives eksplicit, mens de bruges. Det er alts&aring; obejkter som nomalt ikke er beskyttet mod java skralde indsamleren</span>
				</li>
				<li class="c13 li-bullet-0">
					<span class="c3">Bl&oslash;de referencer: Bl&oslash;de referencer ser s&aring;dan ud : SoftReference&lt;String&gt; softRef = new SoftReference&lt;&gt;(&ldquo;abc&rdquo;). De er gode at bruge vis man ikke altid skal bruge objekter s&aring; java skraldeindsamleren kan ryde herpen</span>
				</li>
				<li class="c13 li-bullet-0">
					<span class="c3">Phantom-referencer: Objekterne, der henvises til med fantomreferencer, er kvalificerede til affaldsindsamling. Men inden JVM fjerner dem fra hukommelsen, placerer de dem i en k&oslash; kaldet &#39;referencek&oslash;&#39;. I mods&aelig;tning til bl&oslash;de og svage referencer ryddes fantomreferencer ikke automatisk af affaldssamleren, da de er indkapslet. Et objekt, der kan n&aring;s via fantomreferencer, forbliver det, indtil alle s&aring;danne referencer er ryddet eller i sig selv ikke kan n&aring;s.</span>
				</li>
			</ol>
			<p class="c6 c10">
				<span class="c4"/>
			</p>
			<p class="c6">
				<span class="c2">V&aelig;rdier-</span>
				<span class="c8">&nbsp;er den v&aelig;rdi du giver en variabel </span>
			</p>
			<p class="c6">
				<span class="c2">Objekter </span>
				<span class="c4">- Se: Objekt. Men flere af dem. Alts&aring; instans af en klasse </span>
			</p>
			<p class="c6">
				<span class="c2">Instans </span>
				<span class="c4">- En instans af et objekt, er et bestemt objekt, der befinder sig i programmet. Alts&aring; en enhed af bestemt klasse </span>
			</p>
			<p class="c6">
				<span class="c2">Klasser - </span>
				<span class="c4">Klasser er kategorier, og objekter er elementer inden for hver kategori.</span>
			</p>
			<p class="c6">
				<span class="c4">Alle klasseobjekter skal have de grundl&aelig;ggende klasseegenskaber.</span>
			</p>
			<p class="c6 c10">
				<span class="c2 c5"/>
			</p>
			<p class="c6">
				<span class="c2">Konstrukt&oslash;rer </span>
				<span class="c4">- Den m&aring;de man oftes fremstiller objekter p&aring; fra en klasse. <br>Kan have argumenter = variabler.</span>
				</p>
				<p class="c6">
					<span class="c2">typer -</span>
					<span>Java-programmeringssprogets typer er opdelt i to kategorier: primitive typer og referencetyper. De primitive typer er booleantypen og de numeriske typer. De numeriske typer er de integrerende typer byte, short, int, longog char, og floating-point typer floatog double. Referencetyperne er </span>
					<span>klassetyper</span>
					<span class="c3">&nbsp;, interface-typer og array-typer. Der er ogs&aring; en s&aelig;rlig null-type. Et objekt er en dynamisk oprettet forekomst af en klassetype eller en dynamisk oprettet matrix. V&aelig;rdierne for en referencetype er referencer til objekter. Alle objekter, inklusive arrays, underst&oslash;tter klassemetoderne Object . Strengbogstaver er repr&aelig;senteret af Stringobjekter.</span>
				</p>
				<p class="c6">
					<span class="c2">ikke-primitive typer - </span>
					<span class="c4">Ikke-primitive datatyper kaldes reference types, fordi de henviser til objekter.Hovedforskellen mellem primitive og ikke-primitive datatyper er:</span>
				</p>
				<ul class="c9 lst-kix_ajl4ahj66lbx-0 start">
					<li class="c1 li-bullet-0">
						<span class="c4">Primitive typer er foruddefinerede (allerede definerede) i Java. Ikke-primitive typer oprettes af programm&oslash;ren og defineres ikke af Java (undtagen String).</span>
					</li>
					<li class="c1 li-bullet-0">
						<span class="c4">Ikke-primitive typer kan bruges til at kalde metoder til at udf&oslash;re bestemte operationer, mens primitive typer ikke kan.</span>
					</li>
					<li class="c1 li-bullet-0">
						<span class="c4">En primitiv type har altid en v&aelig;rdi, mens ikke-primitive typer kan v&aelig;re null.</span>
					</li>
					<li class="c1 li-bullet-0">
						<span class="c4">En primitiv type starter med sm&aring; bogstaver, mens ikke-primitive typer starter med et stort bogstav.</span>
					</li>
					<li class="c1 li-bullet-0">
						<span class="c4">St&oslash;rrelsen p&aring; en primitiv type afh&aelig;nger af datatypen, mens ikke-primitive typer har samme st&oslash;rrelse.</span>
					</li>
				</ul>
				<p class="c6">
					<span class="c4">Eksempler p&aring; ikke-primitive typer er strenge , arrays , klasser, interface osv. Du vil l&aelig;re mere om disse i et senere kapitel.</span>
				</p>
				<p class="c6">
					<span class="c2 c5">&nbsp;</span>
				</p>
				<p class="c6">
					<span class="c2">primitive typer </span>
					<span class="c8">- Variabler der ikke kan returnere null. Floats, ints, chars blandt andet.</span>
				</p>
				<p class="c6">
					<span class="c2">variabel deklaration </span>
					<span class="c8">- Oftest i starten af koden vil man deklarere sine variabler. Dette betyder at man skriver alle sine variabler op. <br>float </span>
						<span class="c8">ugaBuga</span>
						<span class="c4">&nbsp;= 420.69;<br>boolean erThomasL&aelig;kker = true;</span>
						</p>
						<p class="c6">
							<span class="c2">v&aelig;rdi-tildeling </span>
							<span class="c8">- </span>
							<span class="c8 c11 c12">n&aring;r man tildeler variabler v&aelig;rdier?</span>
						</p>
						<p class="c6">
							<span class="c2">konvertering </span>
							<span class="c8">- </span>
							<span class="c8 c11">det er n&aring;r man for eksempel laver </span>
							<span class="c8 c11">int</span>
							<span class="c8 c12 c11">&nbsp;om til float?</span>
						</p>
						<p class="c6">
							<span class="c2">algoritme </span>
							<span class="c4">- er en &nbsp;sekvens af veldefinerede , instrukser, typisk til at l&oslash;se en klasse af problemer eller til at udf&oslash;re en beregning . </span>
						</p>
						<p class="c6">
							<span class="c2">pseudokode </span>
							<span class="c4">- Dette er ikke rigtige kode men en m&aring;de at &nbsp;planl&aelig;gge det p&aring;. alts&aring; Pseudokode er et kunstigt og uformelt sprog, der hj&aelig;lper programm&oslash;rer med at udvikle algoritmer. Pseudocode er et &quot;tekstbaseret&quot; design (algoritmisk) designv&aelig;rkt&oslash;j. Reglerne for Pseudocode er rimeligt ligetil. Alle udsagn, der viser &quot;afh&aelig;ngighed&quot;, skal indrykkes.</span>
						</p>
						<p class="c6">
							<span class="c2">klassediagram - </span>
							<span class="c4">Dette er et diagram klasser og deres enbyrdes sammenh&aelig;ng. </span>
						</p>
						<p class="c6">
							<span class="c2">flowdiagram </span>
							<span class="c8">- </span>
							<span class="c18">Et flowchart er en type diagram, der repr&aelig;senterer en workflow eller proces.</span>
							<span class="c2">&nbsp;</span>
						</p>
						<p class="c6">
							<span class="c2">rekursion - </span>
							<span class="c4">REKURSION &nbsp;betyder gentagelse. s&aring; det er en funktion som kalder sig selv.</span>
						</p>
						<p class="c6">
							<span class="c2">loop eller l&oslash;kke - </span>
							<span class="c4">&nbsp;En l&oslash;kke er en gentagelse udf&oslash;relse af en kommando igen og igen. hvor mange gange l&oslash;kken udf&oslash;res er afh&aelig;nger af et logisk udtryk</span>
						</p>
						<ul class="c9 lst-kix_up4nlp53qgxx-0 start">
							<li class="c1 li-bullet-0">
								<span class="c2">ren funktion (eng. &quot;pure function&quot;) </span>
								<span class="c4">- En funktion der ikke tager noget der udefra funktionen.</span>
							</li>
						</ul>
						<p class="c6">
							<span class="c2">Flow Control </span>
							<span class="c8">- Som Anders sagde: &ldquo;alle de steder hvor en kode ikke bare eksekveres linje efter linje - </span>
							<span class="c8">feks</span>
							<span class="c4">. loop.&rdquo;</span>
						</p>
						<p class="c6">
							<span class="c2">betingelser </span>
							<span class="c4">- Det man putter i et if statement. For eksempel en boolean.</span>
						</p>
						<p class="c6">
							<span class="c2 c5">forgrener- n&aring;r koden forgrener sig fx n&aring;r man bruger else</span>
						</p>
						<p class="c6">
							<span class="c2">sammenligningsoperatorer</span>
							<span class="c4">- &nbsp;Sammenlignings operatorer f.eks. &amp;&amp; || &lt;&gt; eller == og Sammenligninger </span>
						</p>
						<p class="c6">
							<span class="c2 c5">funktion eller metode: &nbsp;</span>
						</p>
						<ul class="c9 lst-kix_4cruzvexycpp-0 start">
							<li class="c15 li-bullet-0">
								<span class="c3">Funktion - et s&aelig;t instruktioner, der udf&oslash;rer en opgave.</span>
							</li>
							<li class="c15 li-bullet-0">
								<span class="c3">Metode - et s&aelig;t instruktioner, der er knyttet til et objekt.</span>
							</li>
						</ul>
						<p class="c6 c10 c19">
							<span class="c2 c5"/>
						</p>
						<p class="c20">
							<span class="c14">metode-krop</span>
							<span class="c3">&nbsp;- Metodekroppen er, hvor hele handlingen af &#8203;&#8203;en metode finder sted; metodekroppen indeholder alle de juridiske Java-instruktioner, der implementerer metoden. Inden for metodekroppen kan du bruge this til at henvise til det aktuelle objekt . Det aktuelle objekt er det objekt, hvis metode kaldes. Derudover kan du erkl&aelig;re flere variabler inden for metoden til eksklusiv brug inden for denne metode.</span>
						</p>
						<p class="c7">
							<span class="c3"/>
						</p>
						<p class="c6">
							<span class="c2 c5">input-parametre - det man giver en metode ogs&aring; kaldt agrumenter</span>
						</p>
						<p class="c6">
							<span class="c2">retur-type scope </span>
							<span class="c4">- Er den datatype som en funktion forventes at returnere.</span>
						</p>
						<p class="c6">
							<span class="c2">strategy-pattern </span>
							<span class="c4">- Strategi er et adf&aelig;rdsm&aelig;ssigt designm&oslash;nster, der forvandler et s&aelig;t adf&aelig;rd til objekter og g&oslash;r dem udskiftelige i det originale kontekstobjekt. Alts&aring; det er en funktion som kan omskrives til hvert objekt</span>
						</p>
						<p class="c6">
							<span class="c2">IDE (eller i processing PDE) </span>
							<span class="c4">- En IDE er et udviklingsmilj&oslash;. Dette betyder at der for eksempel b&aring;de er en editor og en compiler. IntelliJ er en IDE.</span>
						</p>
