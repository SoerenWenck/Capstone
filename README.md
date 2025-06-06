# Capstone

Ziel Projektes ist es einen Zusammenhang zwischen Ernährung und Gesundheit herzustellen. Hierfür werden verschieden Datenquellen aus verschiedenen Ländern verwendet.

https://www.kaggle.com/datasets/cdc/national-health-and-nutrition-examination-survey


# Analysis Question:
1.Is there a relationship between average national sugar consumption, calorie intake, or meat consumption and health indicators such as obesity, diabetes, or life expectancy?

2.Which countries or regions have the healthiest (or unhealthiest) eating habits?

How has the consumption of sugar, meat, or plant-based foods changed over the last (10) years?


# Hypotheses (EDA)
Patterns, Trends and Outliers 
1. Länder mit höherem Obst- und Gemüseverbrauch haben geringere Raten an Herz-Kreislauf-Erkrankungen.
2. Ein höherer Anteil an verarbeiteten Lebensmitteln korreliert mit einer höheren Adipositasrate.
3. Der Fleischkonsum pro Kopf steht im Zusammenhang mit bestimmten Krebsarten (z. B. Darmkrebs).
4. Länder mit traditioneller Ernährung (z. B. Mittelmeerdiät, asiatische Ernährung) haben eine höhere Lebenserwartung.
5. Der Zuckerkonsum pro Kopf ist positiv mit der Diabetesprävalenz korreliert.
6. Der Body-Mass-Index (BMI) steigt mit zunehmendem Konsum von Softdrinks oder Fast Food.
7.  Vegetarische oder pescetarische Ernährungsweisen gehen mit geringeren Raten chronischer Krankheiten einher (Ländervergleich möglich).
8. Welche Länder haben die höchste/niedrigste Lebenserwartung bei ähnlichen Ernährungsprofilen?
9. Wie unterscheiden sich Ernährungsgewohnheiten zwischen einkommensstarken und einkommensschwachen Ländern – und welche gesundheitlichen Folgen sind sichtbar?
10. Gibt es Cluster von Ländern mit ähnlichen Ernährungs- und Gesundheitsprofilen?
11. Wie wirken sich kulturelle Essgewohnheiten (z. B. Fasten, vegetarische Küche) auf bestimmte Gesundheitsparameter aus?




Traditionell gesund -	Japan, Italien, Griechenland, Vietnam	hohe Lebenserwartung, mediterran/asiatisch

Hochverarbeitet - USA, UK, Australien	viel Fast Food, hohe Adipositasrate

Schwellenländer - 	Indien, Südafrika, Mexiko	starke Ernährungstransformation

Vegetarisch/kulturell anders -Indien, Israel, Äthiopien	vegetarisch/pescetarisch, religiös geprägt

Ärmere Länder -	Nigeria, Bangladesh, Kambodscha	wenig verarbeitete Nahrung, geringe Gesundheitsversorgung



# Link collection

https://www.who.int/data/gho/whs-annex \


https://www.statista.com/statistics/249681/total-consumption-of-sugar-worldwide/

https://www.statista.com/statistics/274522/global-per-capita-consumption-of-meat/

https://www.who.int/data/gho/whs-annex/

https://www.statista.com/topics/12722/the-health-effects-of-ultra-processed-food/#topicOverview

obesity:
https://ourworldindata.org/obesity

diabetes:
https://ourworldindata.org/grapher/diabetes-prevalence

cancer:
https://ourworldindata.org/cancer

meat:
https://ourworldindata.org/meat-production

sugar und fruit:
https://ourworldindata.org/diet-compositions


# Projekt Struktur (Vorschlag)

___Titel___:

“Global Diets, Health & Wealth – How What We Eat Affects How We Live”


___Business Question___ :

How do different national dietary patterns across income levels and cultures relate to health outcomes such as obesity, diabetes, cancer, and life expectancy?


___Modul 1 – Ernährung vs. Krankheit___

Do higher intakes of sugar, meat, or processed food correlate with higher obesity, diabetes, and cancer rates?

___Modul 2 - Tradition vs Modern___


Do countries with traditional diets (e.g. Japan, Italy) have better health than highly industrialized food cultures?


___Modul 3 – Einkommen & Ernährung___

Can low-income countries afford to eat healthy? Or are rich countries unhealthier than expected?




# Projekt Struktur Vorschlag 2

How does nutrition relate to key health biomarkers in the NHANES 20212023 dataset?

___INTRO___
- Why is nutrition and health an important topic?
- Data source: Brief explanation of NHANES
- Goal: Using NHANES data, we investigate how different aspects of nutrition are associated with health indicators like
blood sugar, inflammation, and cardiovascular risk.


___Module 1 Sugar Intake, Insulin Resistance & Body Weight___
- Sugar intake: DR1TOT_G
- Blood markers: HbA1c (HBA1C_G), Insulin (INS_G)
- Body composition: BMI, waist circumference (BMX_G)

___Module 2 Vitamin D: Intake vs. Blood Levels___
- Dietary & supplemental Vitamin D: DR1TOT_G, DSQTOT_G
- Blood levels: VID_G
- Factors: BMI, race/ethnicity (BMX_G, DEMO_G)

___Module 3 Fat Intake & Cardiovascular Health___
- Fat types: total, saturated, unsaturated (DR1TOT_G)
- Blood lipids: Total cholesterol, HDL, LDL, triglycerides (CHOL_G, TRIGLY_G)
- Blood pressure: BPX_G

___Conclusion & Recommendations___
- What do the data suggest about diet and health?
- Key findings and trends
- Practical takeaways or health recommendations


# Projektstruktur 3
___1. Einleitung___
-Relevanz von Ernährung und Lebensstil für chronische Krankheiten


Ziel des Projekts

___2. Modul 1: Zuckeraufnahme, Diätverhalten und Blutzucker___
-Frage: Wie hängen Zuckerzufuhr, Frühstücksverhalten und Softdrinkkonsum mit HbA1c und BMI zusammen?
-Gruppenvergleiche und Regressionsmodelle

___3. Modul 2: Vitamin D, Supplemente und Schlaf___
-Frage: Haben Supplementnutzer höhere Vitamin-D-Blutwerte? Gibt es Unterschiede je nach Schlafverhalten?

-Vitamin D vs. Schlafdauer, Supplement-Status


___4. Modul 3: Körperliche Aktivität und Entzündung___
-Frage: Haben aktive Personen niedrigere Entzündungswerte (CRP)?
-Bewegung in METs oder Minuten pro Woche, CRP-Quintile

___5. Modul 4 (optional): Psychische Gesundheit und Blutwerte__
-Frage: Haben Personen mit Depressionen schlechtere Blutwerte (Vitamin D, CRP, Blutbild)?
-Selbstberichtete Gesundheit vs. objektive Werte


