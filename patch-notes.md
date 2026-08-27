

# Patch Notes

# 0.24

## Balance changes
  - simplified these debuffs by removing the scaling so they simply on or off so they easier to understand
  - Adjusted the unqiue constantinople building icons to be a bit more smooth to be closer to the texture of vanilla. Hagia Sophia still a bit squeshed 

## Map changes
### Cultures
  - adjusted the Lur/Farsi cultural/religion border to blend a bit better and be more shia and less zorastrian.
### Countries
  - The Morean Slavs and the Hellenized Turkic tags moved to releasable.
  - moved theme of Thessalonki to a releabable. Moved the city and Gold/Gem mines to ERE and the rest split between Strymon and Beroia
  - misc map changes in west HRE and iberia

## Events
  - Opening flavor event for both the Elysian tags.
  - Moved the Iberia crusade target to the balerics since I changed Zaragoza to just be a city state.


# 0.23.3
- Balance pass on ERE modifiers especally ones active at game start.
- various changes to bureaucracy_impact_modifier
- Fix the geography trigger for the IO subjugate action
- Changed the age 1 artillery to only upgrade to age 2 artillery to prevent accidently upgrading trebuchets to ballistae since they for different things.
- small amount of antagonism for the cb/subjugate actions
- Fix: POK, VBK, SMO & KIE missing their starting tech

# 0.23.2
## Oikoumenē and Auctoritas
  - bureaucracies now affect Auctoritas scaling with funding.
  - Added three new categories to spend Auctoritas on. Currently they are idendical to the Middle Kingdom actions they are based on.
    - Reorganize the Logothesia
    - Strengthen Logothesion
    - Issue Chrysobull
  - Lots more UI and localization improvements.
## Other
  - New Anatolian dynasties for the newer tags: Dalassenos , Taronites, Kamateros,  Petraliphas,  Choumnos, Kallergis, Xiphilinos.

# 0.23.1
## Improved the Oikoumenē and Auctoritas
 - Oikoumenē given new descriptions and tooltips thoughout.
 - Auctoritas completely revamped it now functions as I intended with clean understandable UI and clear methods to gain etc.
## New Tags added to Western Anatolia
  - AN29: "Boukellariōn"
  - AN30: "Bithýnion"
  - AN31: "Thrakēsíon"
  - AN32: "Amórion"
## Improved the Golden Horde
  - Asjusted the population of the steppe. Higher pop near main rivers.
  - Startng Culture changed to Astrakhani
## Hellenic Relgion should now function.
  - Small event at start of the game (Localization not done) for Elysiara that converts them to Hellenic even though they already are Hellenic this should fix the game not thinking Hellenism exists preventing pop conversion. 

# Update 23 0.21-0.23
 * Have not been keeping proper notes.
 
## Main Features
  ### Events
  - 100+ new events mostly revolving around the expansion of the Romans and growing external resistance to it. Even Potential Crusades and Jihads. 
  ### Reforms and Privilages
  - Dozens of new estate privilages and government reforms for various countries.
  ### Buildings
  - 10 new Buildings for Latinoi Trade Companies
  - ERE: Upgrade to Constantinoples Shipyard and Military focus addition to the University.
  - 12 new buildings for the roman world for culture, religion, assimilation, military and uniques. 
  ### Diplomatic features
  - 3 New Subject types
  - 5 New diplomatic actions
  ### Advances
  - 100+ new advances for various tags, regions and cultures.
  ### Modifiers
  - Added various decaying modifiers often tied to events.

## Balance
  - Many new countries and map/balance changes.
 

# Update 20
- 0.20
## Balance
This update has been entirely focused on balance and polishing both the content and overall difficulty. Since the ERE is the main tag the mod focuses on, it is the benchmark all other powers are measured against. If they become too strong and their potential rivals too weak, campaigns can start to feel boring after the first 100 years.

I have changed many things to make the ERE in particular a more challenging playthrough, including reintroducing BR-edited versions of the corruption privileges for estates, now dynamically scaling with stability and legitimacy, alongside starting modifiers that worsen during succession crises. Other powers, such as the Turks and the HRE, have also been greatly improved through various privileges, reforms, and a new scaled modifier somewhat similar to lucky nations in EUIV.


0.19.1

# Update 19
- Updated Compatibly to 1.2.2

## New content
  ### Subject types
  - Includes two new unique subject types for the romans
    - Théma, created via regular dipo and also via the unique enforce authority diploaction for the emperor.
    - Nautikē Théma is a naval version currently only available at start for the two naval themes.

  ### Buildings
  - Includes four new military/admin building the roman world, which is kinda like an upgrade path for Thema HQs (give increased benefit and decreased malus at each tier) also added new techs for unlocking.
    - Doukate
    - Katapanate
    - Despotate
    - Dioikesis

  ### Cultures
  - new cultures for the unique banks in the roman world.
    -  Bankariotai
    -  Makrembolitai
    -  Chrysotrapeziōtai

  ### Reforms and Privileges
  - New Government reform and Noble estate privilege for Carolingian tags.
    - Carolingian Heritage government reform.
    - The estate privilage is a unique version of noble armies just for the LOT tag

  ### Town rights
  - These can only be place in provencial capitals and give unique bonuses but empower the nobility.
    - Naval Theme Rights
    - Land Theme Rights

## Balance changes
  - edited the DLC Pronoia to give much less free legitimacy and a slight stability decay malus
  - most themes and pronoia as well as new ones when created changed to dynastic_elective_succession let me know how this is working in your games.
  - rebalanced the population of anatolia to be lower in the east/north and higher in the west.
  - changed development to make frontiers like eastern anatolia/armenia more devastated and western anatolia more developed being the safest portion of the empire generally.
  - HRE starts with Foreign Imperial armories thoughout the cities of the HRE
  - re-added most subject relationships so more larger regional powers form by mid game because I need some big guys to fight as the ERE.
  - lots of smaller tweaks to try and balance the ERE down a tad.

## Bug fixes
  - Should now be able to correctly invite into the roman organization
  - 100s of bug fixes




.17

# Patch Notes

## Estates & Privileges
- Added **Latin Occupiers** estate privilege (`br_latin_occupiers`)
  - Includes cultural requirements, buffs/debuffs, and revoke conditions
  - Enabled for select countries at game start
- Added **Tsar Bulgars & Romans** nobles privilege (`br_tsar_bulgars_romans`)
  - Modifies levy size, culture capacity, assimilation, and humanist shift
- Added **Elysian Foederati** advance and corresponding tribal estate privilege
- Updated **Dynatoi Magnates**
  - Now requires `government_power > 75` to revoke
  - Added peasant enfranchisement modifier
- Reworked **Frontier Expansion privilege**
  - Reordered modifiers and separated conditional effects
  - Enabled native subjugation and automatic slave raiding
  - Moved aggressiveness and war-related modifiers into country scope
- Updated icons and localization across estate privileges

## Events
- Reworked **ERE Event Chain**
  - Removed redundant high-reward options from `br_ere_events.1`
  - Moved rewards to annexation event branch (`br_ere_events.4`)
- Added **Varangian Reform Event Chain**
  - Reform event with follow-up Varangian backlash
  - Includes ruler risks, stability impact, revolt outcomes, and modifiers
- Added **Sardinia startup event** and **Sicilian startup content**
- Added **B0L (Doukai/Bulgarian) startup event**
- Disabled problematic instant annexation and mass unit spawning in Indikes events
- Fixed multiple event localization key mismatches and duplicates

## Countries & Setup
- Added new countries:
  - **Sardinia (SAR)**
  - **B0L (Doukai/Bulgarian state)**
- Reworked **Ottoman (TUR) setup**
  - Updated laws, removed steppe mechanics, increased starting gold
- Assigned **historical rulers** instead of random ones across multiple countries
- Added and integrated **new dynasties** (Maleinos, Hexakionites, Maniakes, Boioannes, Vatatzes, Laskaris, Tornikios, Bryennios, Botaneiates, Armenopoulos, Rangabes, Rogerios, Hauteville)
- Expanded **HRE Elector system**
  - Increased both secular and ecclesiastical electors
- Added **border war CBs** for key regional conflicts at game start
- Updated international organization memberships and diplomacy setups
- Applied **pronoia template** and refined laws, court language, and culture setups
- Ensured consistent starting rulers with fixed `ruler_term` dates (replacing random rulers)

## Mechanics & Balance
- Reworked **advance progression paths**
  - Updated prerequisites across Roman, Varangian, Elysian, and Rhos advances
- Added **trade range modifiers** to infrastructure and advances
- Introduced **Varangian Custodianship** country modifier
- Replaced legacy modifiers with `br_levy_size_modifier` where applicable
- Expanded **Roman world mechanics**
  - Italy now counts toward Roman systems and ownership
  - Added power projection to Roman world entity
- Adjusted **Romaiokratia law**
  - Now applies monthly complacency effects
- Updated **Elysian foothold template**
  - Rebalanced political axis (less centralized/belligerent)
  - Enabled and adjusted multiple laws and societal presets

## Cultures
- Migrated content focus from `greek_group` → `roman_group`
  - Elysians added to Roman group
- Added and rebalanced **culture-specific modifiers**
  - Military, attrition, trade, and conversion bonuses across multiple cultures
- Enhanced **Greek culture modifiers**
  - Added negative relations with Sclavene and Bulgarian cultures
- Updated **Italian and Elysian culture modifiers**
  - Trade range, port cost scaling, sailors, and cultural influence
- Added **location-based modifiers**
  - Assimilation, conversion, separatism, and regional effects
- Removed redundant or duplicated culture entries (e.g., Sicilian merge)

## Characters
- Added large sets of **new dynasties and characters**
  - Includes Byzantine, Italian, and regional families
- Updated **character data**
  - Fixed birthdates, cultures, family links, and parent relationships
- Adjusted **character tags and estate assignments**
- Standardized **ruler assignments**
  - Replaced random rulers with scripted historical characters
  - Added consistent `ruler_term` start dates

## Map, Pops & Visuals
- Updated **coat of arms**
  - Adjusted colors, scaling, and replaced redundant entries
- Consolidated **North American population setup**
  - Merged smaller pop groups and rebalanced sizes
- Added extensive **new coat of arms definitions**
  - Covers Italy, Anatolia, Balkans, and more

## Systems & Files
- Moved `br_country` modifiers to proper directory and expanded functionality
- Split **formable countries** into:
  - Base definitions
  - Mod-specific overrides
- Updated **scripted effects** (HRE elector mechanics)
- Cleaned up file structure, formatting, and redundant code

## Localization
- Added extensive English localization for:
  - New privileges, events, countries, dynasties, and modifiers
- Fixed spacing, formatting, and duplicate keys across multiple files

## Miscellaneous
- Disabled unintended behaviors (instant annexation, unit spawning)
- Improved consistency across triggers, scopes, and conditions
- General cleanup and optimization across all modified files

# .16

## International organizations
### Oikoumenē
- Renamed the organization to Oikoumenē, with Romaiokratía now serving as the primary law framework.
- Added a new IO action granting a subjugation CB against disloyal Strategoi.
- Added a new diplomatic action allowing the Basileus to subjugate certain disloyal Strategoi.

- Added the first category of organization laws.
- Began reworking the starting event, including an optional "easy" setup that grants all members as subjects.

## Society Values
### Logothetai vs. Stratiōtai
- Added a set of society values to represent the internal struggle between the military and the bureaucracy. Most BR mechanics, including reforms, laws, privileges, and buildings, now contribute to one side or the other.

## Balance/Setup Changes
- Added new families in Anatolia.
- Removed free starting CBs, as they are now replaced by the Oikoumenē CB system.

## New starting countries
- AN12: "Argyropronoitai" — named after the ruling family and the pronoia system.
- P2N: "Sinōpē" — named after the city it is centered on.

## GFX
- Added a dozen custom flags, replacing several previously auto-generated ones.

## Fixes
- Fixed Constantinople buildings being removed when moving the capital.

## Localization
- Expand Elysian language location names by @DavidMiltos

# 0.15

# International organizations
## Romaiokratía special statuses
	-	Basileus
	-	Domestikos of the West
	-	Domestikos of the East
	-	Imperial Loyalist
	-	Defiant Strategos

# Many new formable/releasable countries.
 ## New formable countries
  - IT0: "Italias"
  - IT1: "Ravenna"
  - P0N: "Póntos"
  - P1N: "Taurikē"
  - AGY: "Aigyptios"
  - AFK: "Afrikí"
  - SY3: "Syría"
  - AN0: "Armenikon"
  - ANA: "Anatolía"
  - KAP: "Kappadokía"

  - IMP: "IMPERIUM"

 ## New starting countries
  - AN6: "Amisós"
  - AN7: "Koron"
  - AN8: "Kaisáreia"
  - AN9: "Pisidía"
  - AN10: "Amáseia"
  - AN11: "Gángra"

# Many new buildings

  - Pyrgoi: "Chains of fortified watchtowers guard the frontiers, roads, and passes of the realm. These pyrgoi serve as observation posts, signal stations, and rallying points for local soldiers, extending the reach of imperial authority into even the most remote countryside."

 - Kleisourai: "Strategic mountain passes are sealed by fortified defenses known as kleisourai. Garrisons stationed in these narrow defiles control the approaches into the interior, forcing invaders to advance through deadly choke points where defenders can inflict heavy losses and halt entire armies."
 br_kleisourai_maintenance: "Kleisourai Garrison"

 - Rural Brigands: "In regions where imperial authority is weak, bands of brigands and outlaws gather in the hills and forests. Often drawn from impoverished peasants, deserters, and displaced villagers, these groups prey upon travelers and local settlements. While some villagers quietly support them as a form of resistance against distant authorities, their presence disrupts agriculture, trade, and the restoration of order."

 - Holy Mountain of Athos: "The Holy Mountain of Athos stands as the greatest monastic center of the Orthodox world. For centuries its secluded monasteries have drawn monks from across the Roman lands and beyond, forming a spiritual republic devoted entirely to prayer, contemplation, and the preservation of sacred tradition. Though removed from worldly affairs, its spiritual authority carries immense influence among the faithful."

 - Church of the Holy Apostles: "The venerable Church of the Holy Apostles is one of the most sacred shrines of Constantinople and the traditional resting place of Roman emperors. Raised in honor of the Twelve Apostles and rebuilt by the great emperors of the past, it stands as a symbol of the divine mission of the Basileía Romaíon. Within its halls imperial ceremony and sacred tradition intertwine, reinforcing the bond between throne and altar."

 - Apothēkai: "Imperial storehouses known as apothēkai serve as logistical depots for the state. Here grain, equipment, and other supplies are gathered and distributed along the roads and ports of the realm, ensuring that garrisons remain provisioned and that imperial authority can be sustained even in distant provinces."

 - Stationes: "Imperial road stations established along the highways of the realm. These posts house patrols, officials, and messengers who supervise trade, maintain order, and ensure the steady movement of goods and travelers along the empire’s roads."

 - Praitoria: "Provincial headquarters from which imperial officials administer taxation, justice, and the enforcement of imperial law. Staffed by soldiers, clerks, and magistrates, these offices extend the authority of the throne into the cities and provinces of the realm."
 br_praitoria_building_maintenance: "Praitoria Administration"
 
 - Latin Fondaco: "Merchant compounds maintained by Italian trading companies, serving as warehouses, residences, and commercial offices for Latin merchants operating in foreign ports."
 br_latin_trading_post_maintenance: "Fondaco Administration"

# Balance/Setup Changes
- The Majority of the games subjects made independent at game start to create a more exciting dynamic playthough. 
- Added Italiōtai and replaced Sikelianoi except for Sicily.
- Vinlands subjects moved to tribuaries from dominions
- Many starting wars replaced with CBs
- Some small balance tweaks to Estate privileges
- reverted Golden Horde back to Mongol
- Made tribal buildings use the same production methods as villages.
- Made it so they also require tribal government to build

# Localization
- Updated all the roman countries prefix names to not be tied to being a subject.
- Added Kleisoura as unique county tier March subject for ERE.
- Gave Varangian, Gothic and Rhos unique name lists.
## LOC changes to HRE cultures
- gascon: "Aquitanien"
- lorrain: "Austrasien" - Made Primary of Austrasia

# Fixes
- Fixed Varangian cap to be tied to the amount of Varangian recruitment buildings as intended.
- Varangian recruitment building finally has the intended location restrictions.
- Added ai_weight  to the mods unique techs
- unique constantinople buildings should no longer show up in buildings ui

# 0.14

Dozens of new laws, estate privileges, advances, government reforms, buildings and more. Majority for the Romans but new content for the Elysium tags and Armenia along with all the minors attached to those countries.
Many new tags and releasable tags in Russia and Iberia.
Rebalanced most of New Romes buildings.

increased Elysian and Vinlandic populations

Increased the mods unique roman cultured laws by 4
few tweaks to tribal buildings
increased nessisary tribesmen for tribal buildings to be 1000 to match the amount required to employee the building
Moved the non ruling line of the Komnenoi from Khalidia to Antioch.

New Tags:
 RH1: "Tula"
 RH2: "Kursk"
 RH3: "Donets"
 S5C: "Loukanía"
New Releasable tags.
SE4: "Illyria"
Couple new Andalusi releasables in iberia

adjusted the constantinople building modifiers

# 0.13 

## New roman_world international organization:
roman_world_desc: "Romaiokratía is the system through which Roman supremacy is recognized and upheld. It encompasses all realms and authorities that acknowledge the Basileus as the ultimate source of legitimacy, whether directly ruled or bound by obligation. Each member strengthens imperial authority, while failure to honor duties weakens the cohesion of the Roman order."

- Currently pretty bare-bones; will be expanded in future updates. Members send money to Constantinople via a slider — the more paid, the greater the benefits. Paying less than 50% of the expected amount applies penalties. Members will unite against external aggressors.  
  # TO-DO add tiered membership types  
  #special_statuses_implemented = {  
  #}  

  #TO-DO add unique laws  
  #laws = {  
  #}  

## Starting Balance
- Moved Papal capital back to Avignon  
- Placed a local_governor in Rome  
- Added a few free_village holdings to Albania, Ruthenia and the Peloponnese  
- Changed Golden Horde culture to Astrakhani (they should shift to Tatar primary shortly after game start)  
- Renamed and enlarged NAX to Kykládes  
- Relocated historical countries that were in non-existent map areas to appropriate existing locations  
- Created the Cossack Hetmanate  
- Added Cossack tribesmen to the Zaporizhia area  
- Added buildings in Russia  
- Trade company tags now have their land assigned to subjects so they function as proper building-based countries  
- Moved Ruthenia from direct Golden Horde tributaries to members of the Tatar Yoke  
- Removed the starting Teuton–Lithuania war  
- More countries now have access to unique advances  
- Italians receive Italian advances  
- Fatimids and Umayyads granted Empire rank and the title of Caliphate  

## Additions:
- NSE: "North Sea Empire"  
- N0R: "Finnmark"  
- N1R: "Nordland"  
- N2R: "Jämtland"  
- N3R: "Trøndelag"  
- BA0: "Pruthenia"  
- BA1: "Latvia"  
- BA2: "Tartu"  
- A0A: "Samarra"  
- A2A: "Mosul"  
- SY2: "Damascus"  

## Internal code
- Added three templates for Roman-cultured tags and cleaned up their country files:  
  - br_naval_theme_template  
  - br_pronoia_template  
  - br_thema_template  
- Refactored and simplified on_game_start on_actions  
- Added a unique piracy law available only if set at game start  
- Renamed russian_group from "East Slavic" to "Rus"  
- Removed unused code from various sources  
- Changed Bulgaria to green (matching HOI4 color)  
- Updated BR units to follow new 1.1 size standards  

## Building code improvements
- Updated base game building edits to use INJECT instead of replace in most cases  
- Made unique Constantinople buildings indestructible  


# 0.12

## 1.1 additions
- Added new 1.1 starting history content into our map

## Balance
### East HRE
- Various decentralized duchy hiarchies established
  - Saxony
  - Swabia
  - Franconia (Might rename to East Franconia)
  - Hesse (Might rename to West or Central Franconia)
  - Nassau
- New HRE Duchies given vllage, rural and estate buildings.

### Balkans
- New Bulgaran subjects
  - Severin–Olt
  - Arges–Dambovita
  - Ialomita
  - Braničevo
  - Smederevo
  - Niš
  - Mitrovica (Hungarian Subject)

- Ṣiqilliyya created as a subject of Tunis

### New Releasables
- SY0: Palaestina
- SY1: Edessa

### misc balance
- Pop adjustments in Balkans and Anatolia including tribesmen pops thoughout the mountiouns regions particularly
- Substainsal pop work in the Anatolia, Armenia, Turko-Persian frontier.
- More starting laws for Elysians
Building, country, diplomacy and opinion changes
- Georgia and Armenia tributaries of the Seljuk remnants. This should actually benefit them as they shouldn't be targeted for annexation
- Added tribesmen to the Baltic region
- balanced the Constantinople buildings down a tad.
- more pirates
- adjusted various Caucasia and Balkan countries starting reforms and privileges
- akritai_privilege switched peasant estate privilege instead of noble estate
- Gave fishing boats one cannon up from zero.
- Switched Kerman to Zoroastrian so there is a playable Zoroastrian tag.

### New Advances
- Ecumenical Patriarchate: "The Ecumenical Patriarch stands as the foremost bishop of the Roman world, exercising recognized authority through councils, canon law, and custom. From the imperial capital, the Church provides spiritual unity and guidance to the oikouménē, closely entwined with the institutions of the state."

### New privileges
- Prerogatives of the Ecumenical Patriarch: "By ancient custom and recognized canon, the Ecumenical Patriarch exercises wide authority within the imperial church. These prerogatives strengthen the influence of the clergy in public life, extend the Church’s hand into diplomacy, and ensure the spiritual alignment of newly incorporated lands and subjects."

### Dynasties and characters
- Put a Premyslid back on the Bohemian Throne
- Made the Hungarian royal dynasty Arpad arpad_dynasty
- Split Bagratuni from Bagrationi
- Fixed Fatamid dynasty

### Buildings
- Added more weapons and supporting buildings.
- added a small garrison bonus to city guard
- Added a bunch of Noble Villa's to Anatolia to represent the great magnate estates.

## Localization
- Localization fix for the Romans that should also fix the rank being behind name when combined with certain mods.

## GFX
- Varangians will use the age 2 icon.
- Icons added for mod added estate privileges and government reforms

## Bug Fixes
- Lots of various bug fixes and file refactors for better organization.


# 0.11 Énteka

## Art
- 59 additional works of art have been added, bringing the total collection to 110.

## 6 New Unique Constantinople Buildings
- 6 unique buildings have been added for Constantinople.

- **Méga Palátion**:  
  "The principal imperial residence and ceremonial heart of the Roman state, comprising audience halls, chapels, residences, and gardens where emperors governed and enacted the rituals of empire."

- **Hagia Sophia**:  
  "$hagia_sophia$ was originally constructed c. 346 during the reign of Emperor Constantius II, burned down during the Nika Revolt in 532, and fully reconstructed and consecrated in 537 by Emperor Justinian, becoming the largest cathedral in Christendom. Designed by Anthemius of Tralles and Isidore of Miletus, it is renowned for its immense dome, innovative engineering, and detailed mosaics that reflect the grandeur of Orthodox Christianity."  
  - br_hagia_sophia_building_maintenance: "Hagia Sophia Maintenance"

- **The Sénaton**:  
  "The hall in which the Sýnklētos (Senate) convenes, preserving the unbroken civic tradition of the Roman people from the ancient Republic, through Constantine, and into the present age."

- **Pandidakterion**:  
  "Founded to preserve and cultivate the totality of Roman knowledge, the Pandidakterion stands as the foremost center of learning in the empire. Here, law, philosophy, rhetoric, medicine, and theology are taught in an unbroken tradition stretching back to Late Antiquity. Scholars trained within its halls shape the imperial administration, the courts, and the conscience of the Roman world itself."  
  - br_constantinople_university_maintenance: "Pandidakterion Maintenance"

- **Kontoskalion & Prosphorion**:  
  "The twin harbors of the Queen of Cities, where the lifeblood of the Roman world flows in and out with the tides. From the sheltered basins of the Kontoskalion to the bustling quays of the Prosphorion, grain fleets, merchants, and war galleys alike have sustained Constantinople since its founding. Fortified, regulated, and ceaselessly active, these ports bind the capital to every sea under Roman influence."

- **Hippodrome of Constantinople**:  
  "The great arena of the capital, where sport, ceremony, and politics converge before the eyes of the people. More than a place of spectacle, the Hippodrome has long served as a public forum through which popular will, factional rivalry, and imperial authority are expressed. Its crowds have celebrated emperors, condemned ministers, and shaped the rhythm of civic life in the Queen of Cities."

## Balance / Map Changes
- Mesopotamia improvements, including higher population and Samarra starting as a town.
- Balance changes have been split into a separate mod:  
  https://steamcommunity.com/sharedfiles/filedetails/?id=3646909192
- A few changes to the NSE region, and the North Sea Empire has been made a historical formable with reasonable requirements.
- HRE German map changes, including the addition of a decentralized Swabia. More changes are planned in the future.
- Minor government reform and estate privilege tweaks.
- Furniture guilds added to Balkan and Carpathian towns.
- Hellas changes, including a starting war to reconquer Euboea and Thebes made the capital.
- Epiros capital and town moved to Arta.
- Crete and Cyprus can now enact the Naval Theme reform.
- New World countries now start with the `new_world_advance`, removing the need to wait for the institution to reach them.

## Bug Fixes
- Fixed an issue where the new Golden Horde reforms would fall off.
- Fixed various other bugs.

**Full changelog:**  
https://github.com/Basileia-Romaion/BR-1337/compare/0.10...0.11


# 0.10 Déka

## New countries
### Balkans
- B1L: Skopje–Ohrid
- Bulgarian Releasables
  - B0L: "Dobrudja"
  - B2L: "Melnik"
- Roman Bulgarian Releasables
  - B3L: "Serdika"
  - B4L: "Philippópolis"
  - B5L: "Boulgaría"

### Anatolia
- AN0: "Armenikon"
- AN1: "Lykándou"
- AN2: "Sebásteia"
- AN3: "Koloneia"
- AN4: "Kharsianon"
- AN5: "Seleukeía"

### Previously Releaseable now on map at start
- K1B: Kibyrrhaiōtai

## New Estate Privleges
- The following flavored naval debuff has been given to the Basileia Romaion in place of the base game's Burgher Corruption privilege.
  - Latin Maritime Reliance: "Imperial naval administration has grown dependent upon Latin merchant fleets and their capital. In return for sustained access to ships and maritime expertise, the state has granted extensive commercial privileges, shifting naval costs outward while eroding native levies, sailors, and imperial control of the seas."

## New Country Ranks:
- 'Dioíkēsis' replacing fiefdoms in the ERE.
- 'Nautikē Strategía' rank, ruled by a Strategós unless using the overlord’s ruler, for Kibyrrhaiōtai and Aigaíon Pélagos.
- 'Hetaireía' for certain trade company tags and any new ones that are subjects of a Hellenic culture. They are ruled by a Logothétēs.

## Government reform
- Kibyrrhaiōtai and Aigaíon Pélagos have been given the following naval-themed government reform, which boosts their naval potential.
  - Naval Theme Administration: "Coastal and island districts are organized into naval themes, where land, service, and fleet obligation are bound together. Through regulated levies and permanent maritime infrastructure, the state sustains large galley forces, rapid embarkation, and disciplined control of the frontier seas."

- Steppe Tolerance: "Ruling over a vast and diverse steppe realm, the state governs through pragmatism rather than enforced unity. Customs, faiths, and peoples are permitted to coexist so long as tribute flows and order is maintained. This tolerance eases cultural administration but slows efforts at assimilation and religious conversion."

## Balance changes
- Anatolia and the Balkans have had various border adjustments.
- Changed the starting towns in Bulgaria and Anatolia.
- Anatolian and Balkan population adjustments.
- Anatolian and Balkan building adjustments.
- Skopje–Ohrid set as a Bulgarian subject.
- Albanian tags moved to being subjects under Skopje–Ohrid.
- Given extra ships at game start:
  - Kibyrrhaiōtai given 20 galleys.
  - Aigaíon Pélagos given 10 galleys.
- Added 7 random characters to the ERE in its naval subjects.
- Added 26 random female characters to the three main tags in Elysium.
- Adjusted isles country size.
- small pop growth increase for elysium
- Gave mamluks light ships in the red sea to hopefully pull more trade toward egypt
- Moved my assimilation decrease to about 25-35% slower than vanilla down from 50% less. Once we get 1.1 from PDX will move the assimilation debuff to Complacency mechanic. 

## Localization changes
- Changed many Greek location names to be more based on historic spelling and less on phonetics.

## Bug and compatibility fixes
- changed the country base value edits to INJECT instead of replace to make it more compatible with other mods that add effects to the base country values.
- Fixed tribal promotion bug I introduced.
- Last updated I increased the amount of pops required for towns and cities this was my attempt to balance AI turning everything into towns and cities.   Anyway I have decreased towns to 10k required pops from 15 and cities to 40k from 45k.
- Increased town and city control bonus from 0.05 to 0.1 and from 0.1 to 0.15.

**Full Changelog**: https://github.com/Basileia-Romaion/BR-1337/compare/0.9...0.10

# Version 0.9 Ennéa

## Added
- Added Age One artillery units:
  - **Ballistai**  
    An evolution of classical Roman siegecraft adapted for the battlefield. These torsion-powered engines hurl bolts and stones to break enemy cohesion, favoring open ground and disciplined support from infantry formations.
  - **Trebuchets**  
    Large counterweight-driven siege engines designed to batter fortifications and undermine enemy morale. Trebuchets are powerful but slow to deploy, requiring secure positions and extensive logistical support to operate effectively.
- Added Viking Longship unit as an early light ship for Vinland
- Added a second formation option for Elysium that preserves current culture and capital
- Added Italian republics with three locations or fewer as HRE Free Cities
- Added three new Andalusi tags
- Added development to Elysia and Vinland, with additional regional adjustments
- Added forts to Order Strongholds
- Rebalanced towns in Iberia and Anatolia
- Added market villages to every location where a town was removed
- Added two new Roman advances:
  - **Pronoial Administration**  
    The empire formalizes the granting of pronoiai, codifying the rights and obligations of landholders who rule in the Emperor’s name. By binding local rulers to Roman law, service, and fiscal oversight, the state strengthens loyalty while preserving flexibility in provincial governance.
  - **Akritic Reforms**  
    The empire restores the military theme system along its frontiers, uniting civil authority, land grants, and permanent military service under imperial command. Soldier-settlers are bound to their districts by law and obligation, ensuring that the borderlands remain defended, governed, and unmistakably Roman.

## Balance & Gameplay Changes
- Increased Roman and Elysian assimilation unique advances from 25% to 50%
- Added more starting units for several countries
- Adjusted Iberian pops, development, cities, buildings, and country setups
- Set Baltic pops to mostly pagan (region planned for future rework)
- Cities now require 45k population; towns require 15k
- March subjects are now annexable
- Downgraded Kaffa to a town
- Aragon now starts with trebuchets
- Adjusted diplomacy values across multiple regions
- Removed the Meritocracy institution outside of Asia  
  - Intended countries now start with the Meritocracy tech instead
- New flag for Asturias, thanks to Capon doing the work on this.

## Roman / ERE Changes
- Fixed ERE subject rank localizations:
  - Exarchate
  - Katepaníkion
  - Apoikía

## Fixes
- Fixed Bulgaria estate law being available to all countries
- Fixed Varangian building issues
- Fixed Venice having art it shoulden't.

## Technical & Cleanup
- Removed the base localization file



# Hotfix 0.8.1

## Fixes
- HUGE FIX: Our New World countries will now colonize and expand outward.
- Empire rank fix thanks to Azrael
- Combined the Caroling and Carolingian dynasty history. Now uses the Historical dynasty and Coart of Arms.
- Simplified the new ERE unit names
- Increase to Elysians population a bit to offset the black death.


# Update 0.8 októ

## Art Expansion
- 51 additional works of art added to the Roman World From my Treasures of the Roman World Mod: https://steamcommunity.com/sharedfiles/filedetails/?id=3628883955

## New Countries & Subjects
- Added four new ERE minor states.
  - Strymōn, Beroia, and Aigaíon Pélagos created as country-tier subjects.
  - Kibyrrhaiōtai added as a new releasable nation.

## Events & Mechanics
- Added a dynamic event to subjugate the Hetaireía Indikēs when the Suez is acquired.
  - TODO: Test and restrict the event to only fire when Hetaireía Indikēs is AI-controlled.
- Removed Meritocracy from Elysians at game start.
  - Meritocracy is now granted upon forming the Elysium tag.
- Added start Up events to Kykladia, Hagiou Vládymirou, Hagion Taphon and Hetaireía Indikēs. These are not major tags and these events are primarily to spawn additional units/resources via hidden effects to boost these nations.
### New World Events
- Added Events for Black Death and Standing Armies to spread to Vinland.
- Added a follow-up event intended to spread the Bubonic Plague from Vinland to Elysium.


## Culture Groups
- Added new culture groups:
egypt_group: "Egyptian"  
egypt_group_desc: "Cultures linked through a shared regional heritage shaped by the Nile, the eastern Mediterranean, and millennia of continuous settlement. Drawing from native Egyptian traditions, Greco-Roman administration, and later Arab influences, these societies developed layered identities rooted in long-standing institutions, trade networks, and religious diversity."

syria_group: "Syrian"  
syria_group_desc: "Cultures linked through a shared regional heritage formed at the crossroads of Anatolia, Mesopotamia, and the eastern Mediterranean. Influenced by indigenous Levantine traditions, Roman-era institutions, and Arab cultural continuity, these societies reflect enduring urban life, commercial exchange, and religious plurality."

## Theme System
- Expanded the theme system to be available to all Roman and Hellenic Cultures:

## Map Changes
- Moved the city of Elysium from the west bank of the Doeg River to the east bank at Anacostia.
- Adjusted the New World starting road network to account for Elysium’s new location.

## Units
- Added unique Age I Roman units:
  - Skoutatoi (Heavy Infantry)
  - Toxotai (Ranged Infantry)
- Edited Akritai and Katáphraktoi to be available to all countries with a Roman or Hellenic culture.
- Varangian units size increased and allowed 4 units by default without buildings or techs that add additional capacity.

*Some Units are redundant when You have the PM mod active. Will edit the compatch to prioritize their units to avoid duplicates when both active.

## Buildings
- Added the Varangian Commandery.
  "Imperial offices and compounds maintained by Roman envoys for the enlistment of hardy foreign warriors from the northern lands. From these offices, seasoned Varangians are inducted into imperial service, pledging their strength, loyalty, and martial skill in return for pay, privilege, and honor under the Emperor’s banner."

## Balance Changes
- Granted Knights additional military sponsorships.
- Removed Morocco’s starting war.
- Adjusted Ethiopian vassal setup.
- Minor population adjustments in Egypt.
- Continued rebalancing of New World RGOs.
- Moved the Rise of the Turks situation out of Anatolia; it now should only apply to the Persia and Crescent regions.
- Reworked Noble Fortifications:
  - Now provide a small fort with a garrison of 25.
  - Removed the previous 25% modifier bonus.
- Added a 10-year truce between Norway and Sweden to reduce early-game annexation.
- Further standardized Akritai and Katáphraktoi availability across Hellenic cultures.

## Assimilation Overhaul
- May be split into a separate mod depending on feedback.
- Reduced base assimilation and conversion rates by 50%.
- Rural settlements receive an additional 50% assimilation penalty.
- Reduced strength of the Assimilate Area cabinet action by roughly half.
- Reduced strength of the Promote Culture cabinet action by roughly half.

## Building Distribution
- Added additional fishing villages to Aigaíon Pélagos-controlled land to support sailor pops.
- Added more market buildings to Egypt and the Levant.
- Added additional sand production buildings across ERE territory.
- Temporarily removed coastal forts.
- Added several other minor buildings.

## Localization
- Renamed Mizrahi to Musta'arabi.
- Renamed Cataphracts to Katáphraktoi.
- Various minor localization and flavor improvements.

## Bug Fixes
- Seljuk Mint can no longer be built in Anatolia; valid locations are now limited to Tabriz and Mosul.
- Fixed Hellenism conversion logic.
- Resolved several encoding-related errors.
- Dozens of other small bugs fixed.


# Update 0.7 eptá

## Core Mechanics & Reforms
- Added Meritocracy to Elysia. Ideally this should unlock after Elysium forms, but that trigger still needs to be figured out.
- Set Elysium formation to upgrade the country to Kingdom rank.
- Added a 100% assimilation modifier when Elysium is formed.
- Changed the New World colony reform to use `colonial_maintenance_cost = -0.50` instead of exploration cost reduction.
- Adjusted mod advances modifiers.
- Switched Vinlandic advances from culture-based to tag-based.
- Added icons to mod advances.

## Trade, Economy & Buildings
- Added `br_special_trade_companies`: “Chartered Trade Companies”
  - Description: By granting expansive privileges to powerful trade companies, the state entrusts overseas commerce and naval logistics to mercantile elites. In return, these companies sustain trade dominance, expand maritime reach, and shoulder much of the burden of naval upkeep.
- Updated trade and pirate buildings.
- Founding Elysium now changes the local RGO to silk.
- Added startup effects to change certain RGOs.
- Added several coal and tar buildings to Anatolia.
- Added fruit orchards to Vinland to support mead production.
- Added various buildings to New World tags.
- Added Basileion Astronomikon.

## Infrastructure & Map Changes
- Converted more major Roman Roads to start as paved roads.
- Added more gravel roads across Persia.
- Created new New World town templates.
- Gave Helluland additional locations for cleaner borders.

## Cultures, Languages & Dynasties
- Created 14 Elysium dynasties. No unique characters yet; each country will generate 4 random dynasties at game start.
- Temporarily changed the Elysian language to Elysian Latin due to location name loading issues.
- Made all cultures in the Elysian Group view Elysian as Kindred.
- Fixed Helluland having the wrong culture.
- David began updating location names for Elysian (Latin and Greek).

## Population & Balance
- Increased `peasants_training_grounds` manpower from `0.001` to `0.005`.
- Added peasants’ training grounds to areas without noble versions to emphasize stronger peasant power and freedom.
- Rebalanced Vinland pops.

## Countries & Diplomacy
- Updated Anglo-Norse cultural opinion modifiers.
- Made Helluland and Markland Dominions of Vinland.
- Gave Vinland the Norwegian advances.
- Gave Andalusia all unique Granada advances.
- Edited the HRE Free Cities policy so the HSA no longer loses its subjects.


# update éxi - 0.6

## Changes
- Refactored the Morea tag to avoid conflicts with PM’s Moesia.
Going forward, numeric characters will be used in tags where possible to reduce the likelihood of conflicts.
- Moved the Innulanders to the mainland, freeing the island for Vinland.
- Added Bulgaria to the Rhōs Crusade against the Golden Horde.
- Improved starting technologies for Knights and Orthodox Holy Orders to make them more viable early on.
- Added 12 new advances to the Hellenic culture group.
- Enabled the 12 Colonial Subject advances for New World nations, even when they are not subjects.
- Further improved Trade Company starting technologies and buildings, making them more playable and better subjects for Merchant Republic overlords.
- Adjusted population distribution across Anatolia.
- Fixed several advancement-related errors.

# 0.5

## Setup Changes
- Added three new trade companies:
  - Genoese Trade Guild
  - Venice Trade League
  - Hetaireía Indikēs
- Added Indikē and Sōkōtría to the India region.
- Assigned appropriate enclave holdings to trade company overlords in their respective regions.

## New Advances
- Added 12 new Advances for the Rhôs culture (2 per age).
- Added 12 new Advances for the Vinlander culture (2 per age).
- Added 12 new Advances for the Elysian culture group (2 per age).

## Localization
- Incorporated *Greek Dynamic Names – Expansion and Fixes*.  
  https://steamcommunity.com/sharedfiles/filedetails/?id=3602832678

## Bug Fixes
- Various minor bug fixes.

# 0.4

## Estate privileges
- Added new estate privilege: Boiárski Voĭski  
  The traditional levy of the Bulgarian boyars forms the backbone of our armies. These noble households maintain armed retainers and provide large contingents of horsemen in times of war. By reaffirming their martial rights and obligations, we strengthen our military capacity—though at the cost of granting the boyars greater influence within the realm.
- Restored and reworked consolidated_corruption_of_the_nobles for BYZ.

## Rhôs Additions
- Added Rhôs culture as a Greco-Rus hybrid.
- Added Tágma tou Hagiou Vládymirou (Order of Saint Vladimir).
- Set up all Holy Order buildings, relationships, and pops.
- Implemented a starting “Crusade” of the Rhôs supported by the Ruthenians.
- AI currently loses, but the scenario remains interesting.

## Southern Italy Adjustments
- Added Capua and Neapolis tags.

## Buildings
- Improved Sergeantry and City Watch setups.

## Andalusia & Egypt Population Changes
- Added Berber tribesmen to Andalusia.
- Added Berber Shia tribesmen to Egypt.
- Increased total Shia population in Egypt.

## Culture Tweaks
- Gothic moved into the German group with its own dialect.  
  (Crimean Gothic ideally fits as a German dialect, but this setup prevents persecution mechanics.)

## Bug Fixes
- Moved Iberian Holy Order buildings out of the Andalus region.
- Corrected Orthodox Holy Orders converting into bishoprics.  
  (The required estate law was previously restricted to Catholics; now correctly applies to Catholic OR Orthodox.)


# 0.3.3
- Changed the Elysium formation to happen on country formation. The trigger I tried to use earlier wasn't firing.

# 0.3.2
- Created an event for Elysium to move your capitol and change your culture. Should be save game compatible and automatically fire.

# 0.3.1
- Reverted a file refactor that broke the Greek Language

# 0.3

# Unique government added.
- Thema, Prónoia, Autonomía and Exarchate added.
- Katepaníkion (Kingdom Tier subject in Italy or the Adriatic) and Apoikía (Colonial Subjects) will be added in a future update.

# New and Edited Estate Privileges
- Edited the French noble estate privileges to be available to Austrasia.
- Edited Ghazi to be open to any Muslim country and made it allow slave raiding.
- Created Akritai privilege to function similar to Ghazi, allowing Orthodox countries to raid religious enemies.

## Culture
roman_group added
- roman_group: "Romaiokratía"  #Roman Commonwealth
- roman_group_desc: "Cultures linked through the evolving legacy of the Roman Commonwealth, shaped by centuries of shared institutions, law, and governance. Though diverse in language and heritage, these societies reflect traditions formed under Roman influence, separate from but often adjacent to the older Hellenic world."

## Map adjustments
- Kykladia added as a small naval republic owning a couple islands in the Bahamas.
- Adjusted the Turko-Roman border.
- Danish Estonia given to Sweden.
- Adjusted buildings in the New World colonies.

# New Gov Reforms
- Added a New World Colony reform for Vinlandic and Elysian cultures.

# misc
- Various minor adjustments.

# 0.2

## Elysium changes
- Created elysian_culture, elysian_language, and elysian_group.
- Forming Elysium now switches to the unified Elysian culture. All Elysian cultures moved to the new Elysian group, and the Elysian language now merges Latin and Greek naming conventions.
- Added a one-province Elyrics country: Elyriquassa.
- Added more Elyric pops.

## Vinland
- Added additional pops, buildings, and states to Vinlandic countries.

## HRE Organization
- Organization creation date changed to 800 to reflect Charlemagne’s coronation by Pope Leo III.
- Updated HRE color.

## Localization
- Updated all Roman province names (up to the borders of Basil II) to use consistent Greek endonyms.
- Updated Theme and Pronoia subject names to follow the same conventions.

## Balance changes
- Added more farming villages to Egypt, Tunis, and Anatolia to help with grain shortages.
- Added a few additional weapon workshops to Cairo.
- Increased pottery production in Egypt and the Levant.
- Minor population adjustments in South Italy.

## Fixes
- Added missing banks to the Patriarchate.


# 0.1.2

## Culture update/fixes
- Changes the Elysian cultures colors to roughly match the tone of their vicky 3 counterpart.
- fixes the localization for all Roman cultures to use their Anglic-Greek transliteration names.
- Adds in regional Kilikioi as another Romaioi sub culture and Dialect.
- Added in Elyrics culture and dialect as an Elysian/Native Mixed culture.

## Added a few more provinces to Vinland
- Added a few more provinces to Vinland
- Added some Vinlandic pops at stadacona and uashat they are the best ports in the area so made sense they would take for themselves

## Location Names
- renamed more locations to use Elysian names by default. Goal is too expand and move to unique dynamic names for both Latin and Greek.



# Small Hotfix Update 0.1.1 released on steam.
• Resolved an issue preventing Elysium from being properly formable (Should be save game compatible.)
• Updated the formable Elysium flag
• Updated the formable HRE flag

