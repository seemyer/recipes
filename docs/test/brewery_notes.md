## 📋 tasks
- [ ] Increase initial β step to hit gelatinization?
- [ ] Increase boil-off rate (currently 0.4 gal/hr)
- [ ] Vitality starter: Add yeast to 1.040 wort 2 hrs before pitch on stirplate, no O₂ added
- [ ] 3.4:1 l/kg WTG mash ratio
- [ ] Better blow off cane (https://crafthardware.de/en/product/nc-keg-blow-off-cane/)
- [ ] Find Great Western American Distillers malt

## ✏️ notes
	Ideal open fermentation tank dimensions (42x30x24/hwl)
	Forum Discord: https://discord.gg/3zm2FCu2Zz
	FAA Dose: 0.1ml/gal
	Fermenter slurry in mason jar: 1.5B cells/mL
	5.0-5.1 is the optimal effective pH for carrageenan
	0.055 grain mill gives 68% @ #14
	0.049 grain mill gives 60% @ #14
	Imperial A30 - Cloudburst house yeast
	Ca > 50ppm for good floculation
	https://www.morebeer.com/products/briess-distillers-malt.html

## 🎛️ auber DSPR320 cheatsheet
mPRG (short-press knob ➤ RESET=Y ➤ press RUN to start M1)  
```
1	S=151	T=HOLD (press RUN to advance)
2	S=143	T=HOLD (press RUN to advance)
3	S=152	T=HOLD (press RUN to advance)
4	S=162	T=HOLD (press RUN to advance)
5	S=169	T=HOLD (press RUN to advance)
6	S=69	T=END
7	
8	
9	
```
Settings (long-press knob ➤ MSET)  
```
tSP=1 (mash step-timer start-point)
EO=OFF (ending option)
oScr=0 (overshoot correction)
mOUT=100 (mash acceleration max output)
AttE=0 (attenuation constant)
```

## 🧮 recipe template
* Copy to new batch
	* Update formula references
		- [ ] Copy sheets
		- [ ] Data -> Edit Links -> Change Source...
		- [ ] Change source to new filename

## 🌡️ hochkurz mash schedule *(modified - V.2)*
```
58°C/136.4°F dough-in at 0.6 GPM
Stir mash, then rest 5 mins
Recirc at 0.6 GPM for 5 mins to set grain bed
Raise to 66°C/150.8°F β at 2.0 GPM until mash core reaches temp (~10 mins)
Coast down β rest (min 62°C/143.6°F) at 0.6 GPM
	Target %FWG of >90% (~30 - 60 minutes)
Stir mash, then recirc for 10 mins at 0.6 GPM
Raise to 67°C/152.6°F at 2.0 GPM
	Target %FWG of >95% (~10 - 15 mins)
Stir mash, then recirc for 5 mins at 0.6 GPM
Raise to 72°C/161.6°F α at 2.0 GPM
	Target %FWG of ~100% FWG (~30 - 45 mins)
Add boiling sparge infusion to top of grain bed for mash out
Raise to 76°C/168.8°F mash out at 2.0 GPM for 10 mins
```

## 🦠 yeast storage
* Minimal viability loss to at least 30-45 days
* 2% KH2PO4 storage solution in a 2:1 ratio to slurry with beer
	* 14g KH2PO4 to 700 mL distilled water mixed with 350 mL slurry/beer
* 2ml / 1/6 bbl keg sunflower oil, diluted in distilled
	* 1 drop per 350 mL slurry/beer
	* sunflower/safflower/grape seed
* Yeast Freezing
	- [ ] Let yeast settle and decant
	- [ ] Prepare 40% glycerol solution in 1.020 wort
	- [ ] Mix 1:1 with yeast slurry to resuspend
	- [ ] Portion in sterile tubes (20ml:100ml starter)

## 🫧 spunding/carbonation
* Using Speise
	1. Fill qt jar with no headspace.
	2. At spund, add tbsp yeast, transfer to fermentor at high krausen, tranfer beer for spund.
* Using sugar syrup
	1. Purge serving keg during fermentation.
	2. 3-4 days before transfer, open serving keg, drop in hot invert sugar, and close lid.
	3. Fill serving keg from bottom.
	5. Fill keg to brim.
	6. Flip keg daily to assist fermentation at 20C. (10 days lagers, 14 days ales/high ABV).

## ⚗️ sauergut production
1. Add 100 grams of DME to around 900 mL of water and heat pasteurize/boil (1.040).
2. Cool the DME wort to the desired incubation temperature.
3. Add 100 mL of pasteurized apple juice, 0.5 grams of chalk (CaCO3), and half a teaspoon of yeast nutrients.
*Buffer pH reduction and allow extra acid production with chalk*  
Use 8 drops (0.4 ml) of phenolphtalein for acid testing?  

## 🍺 private landbrauerei schönram SOP
**Mash**  
1. Mash in at 118F
2. Short rest at 140F
3. Long beta rest at 149F
4. Only Pils malt and single decoction to raise mash temp from beta to mash out
5. Hell/Pils, 0 min decoction boil
6. Dunkel/Festbier/Stout, 10 min decoction boil
7. Mash out at 170F for 5 min
**Hops**  
* Prefer aroma varieties, avoid high alpha bittering
* >50% late hopping
* Helles, 20 IBU (50/30/15)
* Pils, 40 IBU (FWH/55/15/3/WP)
**Fermentation**  
* Pitch at 44F, ferment at 49F
* Open fermentation during high krausen
* Ferment close to FG, add Speise, agitate fermenter to restart fermentation
* Transfer to serving keg, slowly reduce temperature to 37F
	* Hell/Pils/Dunkel, 6 wk lager/spund
	* Festbier/Bock, 10 wk lager/spund
| Style  | AA    |
| ------ | :---: |
| Hell   | 86%   |
| Pils   | 86%   |
| Dunkel | 77%   |

## 📜 recipes
**Italian Pilsner**  
| Beer               | Gravity | IBU   | Notes                                      |
| ------------------ | :-----: | :---: | ------------------------------------------ |
| Tipopils           | 12-2°P  | 30-40 | Hops: 75/45/WP/DH <br> 
													  Ferment at 52°F (W-34/70) <br> 
													  DH during primary (30 g/hL) <br> 
													  DH during maturation (70 g/hL)             |
| Unlmtd Breadsticks | 5.5%    | 35    | Pils malt <br> 
													  Tettnang/Saphir                            |
| Terrifico          | 4.7%    | 42    | Boil, 2 lb/bbl (Spalt Select/Tettnang) <br>
													  DH (Polaris/Tettnang)                      |
| Glass Dolls        | 4.5%    | n/a   | Floor-malted pils <br> 
													  Ariana/Mittelfruh/Magnum                   |
| Chuckanut          | 4.9%    | 42    | Pils malt <br>
													  Boil (Perle/Hallertau) <br> 
													  DH (Tettnang/Saaz)                         |

**Cellarmaker *Kilning Me Softly***  
West Coast Hazy IPA  
> According to Connor Casey, cofounder of Cellarmaker, “This West Coast Hazy IPA is brewed with the best hop varieties America has to offer: Mosaic, Citra, Strata, and Simcoe. Brilliant aromatics match saturated hop flavor, balanced by a soft mouthfeel. It’s supremely drinkable due to the slender body, semidry finish, and avoidance of sweet esters.”

| Method               | All-Grain   |
| -------------------- | ----------- |
| Batch size           | 5.5 gallons |
| Brewhouse efficiency | 75%         |
| OG                   | 1.064       |
| FG                   | 1.010       |
| IBUs                 | 50          |
| ABV                  | 7%          |

MALT/GRAIN BILL  
- [ ] 5.3 kg two-row pale
- [ ] 794 g flaked oats
- [ ] 91 g Crystal 15
HOPS & ADDITIONS SCHEDULE  
- [ ] 7 g Citra (13% AA) at 30 minutes
- [ ] 43 g Citra (13% AA) at whirlpool (see below)
- [ ] 85 g Mosaic (13.5% AA) at whirlpool (see below)
- [ ] 85 g Simcoe, dry hop on Day 7
- [ ] 85 g Mosaic, dry hop on Day 7
- [ ] 57 g Strata, dry hop on Day 8
- [ ] 57 g Citra, dry hop on Day 8
YEAST  
- [ ] Gigayeast GY001 NorCal Ale #1

DIRECTIONS  
1. Mash the grains at 152°F (67°C) for 45 minutes. Vorlauf for a few minutes to remove most of the big chunks of grain but otherwise stay turbid, then run off into the kettle. Lauter and sparge to obtain about 7.5 gallons (28 liters) of wort. Boil for 75 minutes and whirlpool, adding hops according to the schedule. Add whirlpool hops once the wort is below 200°F (93°C) but above 180°F (82°C). After whirlpooling, chill the wort to slightly below fermentation temperature, about 63°F (17°C). Aerate the wort and pitch healthy yeast. (If possible, make a yeast starter the day before.)
2. Ferment at 66°F (19°C) and no higher than 68°F (20°C). Raise the temperature to 72°F (22°C) once the beer is about two-thirds through fermentation (at about 1.028), typically on Day 3 or 4. Dry hop until the beer passes a forced diacetyl test, then cold-condition until it is less turbid but still hazy and soft.

!!! tip BREWER’S NOTES
    At Cellarmaker, we’ve had very little trouble keeping beers hazy with the NorCal strain, but that has not been true for others. If you experience minimal haze with this recipe, you could experiment with hazier strains, but ferment on the cooler side to restrain ester production.

**Beechwood *American Black Ale***
Cascadian Dark Ale   
> Julian Shrago, cofounder and brewmaster of Beachwood BBQ & Brewing in Huntington Beach, California, shares this homebrew recipe for a hoppy dark IPA similar to their award-winning Beachwood Hoppa Emeritus.

| Method               | All-Grain |
| -------------------- | --------- |
| Batch size           | 5 gallons |
| Brewhouse efficiency | 72%       |
| OG                   | 1.062     |
| FG                   | 1.008     |
| IBUs                 | 60        |
| ABV                  | 7.1%      |

MALT/GRAIN BILL  
- [ ] 11 lb (5 kg) pale two-row
- [ ] 8 oz (227 g) Weyermann Carafa Special III
- [ ] 6 oz (170 g) British Crystal 45L
- [ ] 3 oz (85 g) Weyermann LME Sinamar, at whirlpool
HOPS SCHEDULE  
- [ ] 0.25 oz (7 g) Ekuanot [14% AA] at FWH
- [ ] 0.25 oz (7 g) Warrior [15% AA] at 60 minutes
- [ ] 0.25 oz (7 g) Ekuanot [14% AA] at 15 minutes
- [ ] 2 oz (57 g) Citra [13% AA] at whirlpool
- [ ] 2 oz (57 g) each Citra, Simcoe, Mosaic at dry hop, Day 5
YEAST  
- [ ] White Labs WLP001 California Ale

DIRECTIONS  
1. Mill the grains and mash at 150°F (66°C) for 30 minutes. Vorlauf until the runnings are clear, then run off into the kettle. Sparge and top up as necessary to obtain about 6.8 gallons (26 liters) of wort — or more, depending on your evaporation rate. Boil for 90 minutes, following the hops schedule. After the boil, conduct a whirlpool, add the Sinamar LME and whirlpool hops, and whirlpool for 30 minutes. Chill the wort to about 67°F (19°C), aerate well, and pitch the yeast.
2. Ferment at 67°F (19°C), adding dry hops after primary (typically 4–5 days), then continue to ferment until complete. Cold crash, package, and carbonate.

!!! tip BREWER'S NOTES
    You can substitute other types of debittered black malts for the Carafa.

**Bent Brewstillery *Fi Dem Stout***
Jamaican Stout  

| Method               | All-Grain |
| -------------------- | --------- |
| Batch size           | 5 gallons |
| Brewhouse efficiency | 72%       |
| OG                   | 1.075     |
| FG                   | 1.018     |
| IBUs                 | 28        |
| ABV                  | 7.5%      |

MALT/GRAIN BILL  
- [ ] 5.5 lb (2.5 kg) six-row pale
- [ ] 2.8 lb (1.3 kg) pilsner
- [ ] 1.5 lb (680 g) white wheat malt
- [ ] 1.35 lb (612 g) cane sugar
- [ ] 13 oz (368 g) dark crystal (120L–155L)
- [ ] 11 oz (312 g) Porterine or blackstrap molasses
- [ ] 6.5 oz (184 g) chocolate malt
- [ ] 6.5 oz (184 g) roasted barley
HOPS SCHEDULE  
- [ ] 1 ml isomerized hop extract [60% AA] at 75 minutes (or any bittering hops to get 25–30 IBUs)
YEAST  
- [ ] Fermentis SafLager W-34/70 or equivalent strain

DIRECTIONS  
1. Mill the grains and mash at 153°F (67°C) for about 45 minutes (or, alternatively, only until it passes an iodine test for starch conversion). Sparge and top up as necessary to get about 6.7 gallons of wort—or more, depending on your evaporation rate. Boil for 75 minutes, adding the hop extract (or bittering hops) at the start. After the boil, chill the wort to about 68°F (20°C), aerate, and pitch the yeast. (Do not overpitch.)
2. Ferment at 70°F (21°C) for about 5 days, or until fermentation is complete. Cold crash and condition for 2 weeks. Package and carbonate to about 2.6 volumes.
