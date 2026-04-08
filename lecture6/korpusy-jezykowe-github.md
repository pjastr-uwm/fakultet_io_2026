# Korpusy językowe na GitHubie — według formatu

> Wszystkie linki zweryfikowane 2026-04-08 (status HTTP 200).

---

## Plain text

- [google/corpuscrawler](https://github.com/google/corpuscrawler) — crawler budujący korpusy językowe z publicznie dostępnych stron, wynik w plikach .txt
- [dariusk/corpora](https://github.com/dariusk/corpora) — kolekcja statycznych korpusów w JSON, przydatnych przy prototypowaniu
- [Phylliida/Dialogue-Datasets](https://github.com/Phylliida/Dialogue-Datasets) — korpusy dialogowe w plain text (BNC, Twitter)
- [uwgraphics/VEP2_TCP_SimpleText](https://github.com/uwgraphics/VEP2_TCP_SimpleText) — 61 315 dokumentów .txt z Text Creation Partnership (8,1 GB)
- [niderhoff/nlp-datasets](https://github.com/niderhoff/nlp-datasets) — alfabetyczna lista darmowych zbiorów tekstowych do NLP

## JSONL

- [facebookresearch/XNLI](https://github.com/facebookresearch/XNLI) — korpus cross-lingwalny w JSONL i TSV, 15 języków
- [DFKI-NLP/MobIE](https://github.com/DFKI-NLP/MobIE) — 3 232 niemieckie dokumenty z anotacjami NER w AVRO i JSONL
- [oscar-project](https://github.com/oscar-project) — organizacja OSCAR; Schema v2 używa formatu JSONLines
- [allenai/c4-documentation](https://github.com/allenai/c4-documentation) — dokumentacja C4 (Colossal Clean Crawled Corpus), dane w JSON Lines
- [jojonki/NLP-Corpora](https://github.com/jojonki/NLP-Corpora) — uporządkowana lista korpusów NLP (QA, dialogi, NER itd.)

## CoNLL / CoNLL-U

- [UniversalDependencies/UD_English-EWT](https://github.com/UniversalDependencies/UD_English-EWT) — 254 818 słów, 16 622 zdań w CoNLL-U (Universal Dependencies)
- [flairNLP/CleanCoNLL](https://github.com/flairNLP/CleanCoNLL) — poprawiona wersja CoNLL-03 z niemal bezbłędnymi anotacjami NER
- [synalp/NER](https://github.com/synalp/NER) — dane CoNLL-2003 w oryginalnym formacie kolumnowym
- [natasha/nerus](https://github.com/natasha/nerus) — duży rosyjski korpus z POS, składnią i NER w CoNLL-U
- [UniversalDependencies/tools](https://github.com/UniversalDependencies/tools) — narzędzia do walidacji i przetwarzania plików CoNLL-U

## Parquet

- [huggingface/datasets](https://github.com/huggingface/datasets) — biblioteka HF obsługująca CSV, JSON, Parquet, HDF5 i inne
- [huggingface/dataset-viewer](https://github.com/huggingface/dataset-viewer) — backend automatycznie konwertujący datasety do Parquet
- [oscar-project/ungoliant](https://github.com/oscar-project/ungoliant) — pipeline OSCAR; dane na HuggingFace dostępne też w Parquet

## TEI/XML

- [COST-ELTeC/ELTeC](https://github.com/COST-ELTeC/ELTeC) — European Literary Text Collection, powieści 1840–1920 w TEI XML
- [COST-ELTeC/ELTeC-eng](https://github.com/COST-ELTeC/ELTeC-eng) — 100 angielskich powieści w TEI XML
- [ELTE-DH/poetry-corpus](https://github.com/ELTE-DH/poetry-corpus) — kompletne wiersze 53 węgierskich poetów w TEI XML
- [ELTE-DH/regenykorpusz](https://github.com/ELTE-DH/regenykorpusz) — węgierski korpus powieściowy w TEI XML
- [ELTE-DH/folk-song-corpus](https://github.com/ELTE-DH/folk-song-corpus) — 2 390 węgierskich pieśni ludowych w TEI XML
- [TEIC/TEI-Simple](https://github.com/TEIC/TEI-Simple) — podzbiór TEI dla książek nowożytnych (EEBO TCP)

---

## Polskie korpusy językowe

### Listy zbiorcze

- [ksopyla/awesome-nlp-polish](https://github.com/ksopyla/awesome-nlp-polish) — wyselekcjonowana lista zasobów NLP dla polskiego
- [sdadas/polish-nlp-resources](https://github.com/sdadas/polish-nlp-resources) — pretrenowane modele i zasoby językowe dla polskiego NLP

### Plain text (polskie)

- [speakleash/speakleash](https://github.com/speakleash/speakleash) — inicjatywa budowy dużego korpusu do trenowania polskich LLM-ów
- Polski podzbiór OSCAR (~49–109 GB polskiego tekstu)
- Polish Wikipedia dump (>4 GB tekstu)
- Polish OpenSubtitles v2018 (45,9 mln zdań, 287,1 mln tokenów)

### JSONL / Parquet (polskie podzbiory wielkich korpusów)

- `allenai/c4` (konfiguracja `pl`) — ~180 GB skompresowanego polskiego tekstu (HuggingFace)
- `oscar-corpus/OSCAR-2301` (konfiguracja `pl`) — polski OSCAR w JSONL/Parquet (HuggingFace)
- `uonlp/CulturaX` — połączenie mC4 + OSCAR, wyczyszczone i zdeduplikowane (HuggingFace)

### CoNLL-U (polskie)

- [UniversalDependencies/UD_Polish-PDB](https://github.com/UniversalDependencies/UD_Polish-PDB) — 22 152 zdań (350 tys. tokenów) z NKJP, Europarl i in. w CoNLL-U
- [UniversalDependencies/UD_Polish-LFG](https://github.com/UniversalDependencies/UD_Polish-LFG) — ~17 200 zdań z NKJP w CoNLL-U (enhanced dependencies)
- [kawu/nkjp](https://github.com/kawu/nkjp) — biblioteka do manipulowania danymi NKJP

### TEI/XML (polskie)

- [COST-ELTeC/ELTeC-pol](https://github.com/COST-ELTeC/ELTeC-pol) — 100 polskich powieści (1840–1920) w TEI XML
- NKJP (Narodowy Korpus Języka Polskiego) — milionowy podkorpus w TEI P5 XML, dostępny z http://nkjp.pl/

---

## Przydatne strony tematyczne na GitHubie

- [github.com/topics/text-corpus](https://github.com/topics/text-corpus)
- [github.com/topics/conll-2003](https://github.com/topics/conll-2003)
- [github.com/topics/universal-dependencies](https://github.com/topics/universal-dependencies)
- [github.com/topics/tei-xml](https://github.com/topics/tei-xml)
