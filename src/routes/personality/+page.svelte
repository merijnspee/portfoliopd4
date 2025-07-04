<script lang="ts">
	import bigfive from '../../assets/Bigfive.png';
	import caluwe from '../../assets/Caluwe.png';
</script>

<div class="min-h-screen overflow-auto bg-gradient-to-b from-[#BEE9E8] to-[#CAE9FF] px-4 py-12">
	<div class="mx-auto max-w-3xl space-y-10 rounded-2xl bg-white p-10 text-[#1B4965] shadow-2xl">
		<h1 class="text-center text-4xl font-bold">Opdracht Reflectie & Kleurentest</h1>

		<section>
			<h2 class="mb-4 border-b border-[#62B6CB] pb-1 text-2xl font-semibold">
				Persoonlijkheidsreflectie (Big Five)
			</h2>
			<img alt="Big Five test resultaten" src={bigfive} class="mb-4 rounded-lg shadow-md" />
			<p>
				Ik herken mezelf goed in deze uitslag. Vooral de hoge meegaandheid klopt: ik ben vaak
				vriendelijk, wil anderen helpen en vermijd ruzie. Ook de extraversie past bij me ik praat
				makkelijk met mensen en voel me op mijn gemak in gezelschap.
			</p>
			<h3 class="mt-4 font-semibold">Twee voorbeelden:</h3>

			<ul class="mt-4 list-inside list-disc space-y-2">
				<li>
					Meegaandheid: In groepswerk probeer ik altijd goed mee te denken en anderen te steunen.
					Ook ben ik flexibel. Toen de onderzoeksfase twee keer werd verlengd, ging ik daar in mee,
					ook al wilde ik liever al programmeren.
				</li>
				<li>
					Gewetensvolheid: Ik vind plannen soms lastig. Ik stel dingen uit en werk vaak op het
					laatste moment. Ook bij deze opdracht leverde ik onderdelen laat in, zoals de stepping
					stones en PD.
				</li>
			</ul>
			<p class="mt-4">
				Ik wil me verbeteren in plannen en organiseren (gewetensvolheid), zodat ik rustiger kan
				werken en minder stress ervaar. Mijn meegaandheid wil ik blijven benutten in samenwerkingen.
			</p>
		</section>

		<section>
			<h2 class="mb-4 border-b border-[#62B6CB] pb-1 text-2xl font-semibold">
				Kleurentest Reflectie
			</h2>
			<img alt="Kleurentest resultaten" src={caluwe} class="mb-4 rounded-lg shadow-md" />
			<p><strong>Hoogste kleur:</strong> Wit</p>
			<p class="mt-2">
				Deze kleur gaat ervan uit dat veranderingen vanzelf ontstaan. Je helpt door kleine duwtjes
				te geven of blokkades weg te nemen.
			</p>
			<p class="mt-4">
				<strong>Voorbeeld van een verandering:</strong><br />
				In sprint 2 besloten we om nog een sprint onderzoek te doen. Ik was er niet heel blij mee, maar
				ik vertrouwde op de groep en ging mee in de beslissing.
			</p>
		</section>

		<section>
			<h2 class="mb-4 border-b border-[#62B6CB] pb-1 text-2xl font-semibold">
				Eerste Werkdag (Toekomstbeeld)
			</h2>
			<p>
				Op mijn allereerste werkdag als afstudeerstagiair of junior app developer kom ik met gezonde
				spanning en veel enthousiasme binnen bij het bedrijf. Ik zorg dat ik op tijd ben, netjes
				gekleed en klaar om te leren. Na een korte introductie door mijn begeleider krijg ik een
				rondleiding, ontmoet ik het team en word ik geïntroduceerd in de werkwijze, tools en
				projecten van het bedrijf.
			</p>
			<p>
				Ik krijg toegang tot de systemen, mijn werkplek wordt ingericht en ik maak kennis met de
				codebase waar ik mee ga werken. De eerste dag staat vooral in het teken van kennismaken,
				oriënteren en begrijpen hoe het bedrijf werkt. Misschien lees ik mee in bestaande code,
				probeer ik zelf een kleine bug op te lossen of installeer ik de benodigde tools en
				frameworks. Ik stel vragen, maak notities, en laat zien dat ik gemotiveerd ben om aan de
				slag te gaan.
			</p>
			<p class="mt-4">
				Mijn doel voor deze dag: een goede eerste indruk maken en een helder beeld krijgen van wat
				er van mij verwacht wordt de komende tijd.
			</p>
			<h3 class="mt-4 font-semibold">Vijf tips aan mezelf:</h3>
			<ul class="mt-2 list-inside list-decimal space-y-1">
				<li>Wees op tijd en goed voorbereid</li>
				<li>Stel vragen en wees nieuwsgierig</li>
				<li>Luister en observeer goed</li>
				<li>Wees jezelf, maar blijf professioneel</li>
				<li>Maak notities</li>
			</ul>
		</section>

		<section>
			<h2 class="mb-4 border-b border-[#62B6CB] pb-1 text-2xl font-semibold">
				Kleur en Veranderen
			</h2>
			<p>
				Een persoon die geel scoort, betrek je door hem mee te laten denken. Geef hem inspraak en
				laat het voordeel zien — niet alleen voor het team, maar ook voor hemzelf. Als hij voelt dat
				zijn mening telt, zal hij sneller meewerken aan de verandering.
			</p>
		</section>
	</div>
</div>

<style lang="postcss">
	@reference "tailwindcss";
</style>
