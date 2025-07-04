<script lang="ts">
	import coc from '../../assets/coc.png';
	import begrepen from '../../assets/begrepen.png';
</script>

<div class="min-h-screen overflow-auto bg-gradient-to-b from-[#BEE9E8] to-[#CAE9FF] px-4 py-12">
	<div class="mx-auto max-w-3xl space-y-6 rounded-2xl bg-white p-10 text-[#1B4965] shadow-2xl">
		<h1 class="text-center text-4xl font-bold">Persoonlijk Leiderschap</h1>
		<section>
			<h2 class="mb-2 text-2xl font-semibold">1. Wees proactief</h2>
			<h3 class="text-xl font-semibold">
				Hoe kan je reactieve uitspraken omzetten naar proactief gedrag?
			</h3>
			<div class="mt-4 space-y-4 text-lg">
				<div>
					<p><span class="font-semibold">Reactief:</span> “Ik krijg geen goede feedback.”</p>
					<p>
						<span class="font-semibold">Proactief:</span> Ik vraag zelf actief om feedback en stuur mijn
						werk mee om gerichte reacties te krijgen.
					</p>
				</div>
				<div>
					<p>
						<span class="font-semibold">Reactief:</span> “Het lukt niet om een fasegesprek in te plannen.”
					</p>
					<p>
						<span class="font-semibold">Proactief:</span> Ik neem verantwoordelijkheid en stel zelf alternatieve
						dagen voor, zodat het gesprek doorgaat.
					</p>
				</div>
				<div>
					<p>
						<span class="font-semibold">Reactief:</span> “Mijn begeleider reageert niet op mijn e-mail.”
					</p>
					<p>
						<span class="font-semibold">Proactief:</span> Ik probeer via andere kanalen contact te leggen,
						plan een meeting in of loop even langs.
					</p>
				</div>
			</div>
		</section>

		<section>
			<h2 class="mb-2 text-2xl font-semibold">
				Wat zijn jouw cirkel van invloed en cirkel van betrokkenheid?
			</h2>
			<img src={coc} alt="circle of concern" />
		</section>
		<section>
			<h2 class="mb-2 text-2xl font-semibold">Begin met het einde voor ogen</h2>
			<h3 class="text-xl font-semibold">
				Wat zou je willen dat jouw docent zegt bij de diploma-uitreiking?
			</h3>
			<blockquote class="mt-2 border-l-4 border-[#1B4965] pl-4 italic">
				Vandaag zetten we Merijn in het zonnetje. Hij rondde zijn afstudeeropdracht af met een 8,5.
				Hij was zelfstandig, proactief en combineerde techniek met gebruiksvriendelijkheid. Hij
				vroeg actief feedback, dacht mee, programmeerde mooie dingen en toonde een professionele
				houding. We gaan nog veel van hem horen!
			</blockquote>
		</section>

		<section>
			<h2 class="mb-2 text-2xl font-semibold">Belangrijke zaken eerst</h2>
			<h3 class="text-xl font-semibold">
				Welke activiteiten doe je en waar passen ze in de matrix?
			</h3>
			<div class="mt-4 grid grid-cols-1 gap-4 text-lg sm:grid-cols-2">
				<div>
					<h4 class="mb-1 font-semibold underline">Belangrijk & urgent</h4>
					<ul class="list-inside list-disc space-y-1">
						<li>Stage vinden</li>
						<li>MKO/PD afronden</li>
						<li><strong>Challenge goed afronden</strong></li>
						<li>Stepping stones</li>
					</ul>
				</div>
				<div>
					<h4 class="mb-1 font-semibold underline">Belangrijk & niet urgent</h4>
					<ul class="list-inside list-disc space-y-1">
						<li><strong>Sociale contacten behouden</strong></li>
						<li>Netwerken</li>
						<li>AI</li>
						<li>Afstuderen</li>
						<li>Alvast werk zoeken</li>
						<li>Drone afmaken</li>
						<li>Wandelen</li>
						<li><strong>Goed slapen</strong></li>
					</ul>
				</div>
				<div>
					<h4 class="mb-1 font-semibold underline">Niet belangrijk & urgent</h4>
					<ul class="list-inside list-disc space-y-1">
						<li>LinkedIn bijwerken</li>
					</ul>
				</div>
				<div>
					<h4 class="mb-1 font-semibold underline">Niet belangrijk & niet urgent</h4>
					<ul class="list-inside list-disc space-y-1">
						<li>Rijbewijs halen</li>
						<li>Doomscrollen</li>
					</ul>
				</div>
			</div>
		</section>

		<section>
			<h2 class="mb-2 text-2xl font-semibold">5. Eerst begrijpen, dan begrepen worden</h2>
			<h3 class="text-xl font-semibold">
				Hoe communiceer jij? Begrijp jij eerst of wil jij begrepen worden?
			</h3>
			<img src={begrepen} alt="begrepen of begrijpend luisteren" />
			<p class="mt-2 text-lg">
				Ik heb dit met Wouter besproken en hij was het met me eens, hij zag dat ik vaker meer
				instructies gaf en dingen uitlegde dan dat ik naar mensen luister. Dit heb ik gemerkt uit de
				feedback tijdens retro's en reviews, hier kwamen vaak dingen naarboven die ik niet gemerkt
				had en er kwam naar boven dat zij zich af en toe niet naar geluisterd voelden. Eerder had ik
				juist het probleem dat ik vooral luisterde maar in de toekomst wil ik hier een midden tussen
				vinden.
			</p>
		</section>

		<section>
			<h2 class="mb-2 text-2xl font-semibold">6. Creëer synergie</h2>
			<h3 class="text-xl font-semibold">
				Wanneer heb jij samengewerkt op een manier die tot een beter resultaat leidde?
			</h3>
			<p class="mt-2 text-lg">
				Binnen onze challengegroep benutten we elkaars sterke kanten goed. David werkte aan de
				embedded onderdelen van het project, terwijl ik de communicatie met de rest van het systeem
				verzorgde. Daardoor konden we beiden doen waar we goed in zijn.
			</p>
		</section>

		<section>
			<h2 class="mb-2 text-2xl font-semibold">7. Houd de zaag scherp</h2>
			<h3 class="text-xl font-semibold">Wat doe jij om jezelf scherp en actueel te houden?</h3>
			<ul class="mt-2 list-inside list-disc space-y-1 text-lg">
				<li>IT-nieuws volgen</li>
				<li>Op de hoogte blijven van programmeertalen</li>
				<li>Online cursussen volgen</li>
				<li>Certificaten behalen</li>
			</ul>
		</section>
	</div>
</div>

<style lang="postcss">
	@reference "tailwindcss";
</style>
