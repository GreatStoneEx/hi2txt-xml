2021-03-13 [FIXED]    "**Bubble Bobble (US)**" (bublboblr, bublboblr1): fixed 'Wrong SPECIAL ITEM COUNTERS value encoding detected' issue seen with mame 0.221+
2020-05-02 [IMPROVED] "**Mars Matrix: Hyper Solid Shooting**" (mmatrix, mmatrixj, mmatrixd): trim SCORE and EXP for easier reading    
2020-05-02 [FIXED]    "**Age Of Heroes - Silkroad 2**" (aoh): decode LEVEL as base 10    
2020-05-02 [ADDED]    "**Tron (Germany)**" (tronger)    
2020-05-02 [ADDED]    "**Tron (5/12)**" (tron5)    
2020-05-02 [FIXED]    "**Tron**" (tron, tron2, tron3, tron4): decode MODE as base 10    
2020-05-02 [FIXED]    "**Black Widow**" (bwidow): nvram content is not emulated correctly    
2020-05-02 [FIXED]    "**Lunar Rescue**" (lrescue, lrescuem, mrescuem2, escmars, desterth): fix 'NAME LENGTH' to be base 10 and add Trim to NAME    
2020-05-02 [FIXED]    "**Narc**" (narc, narc3): decode checksum as base 10    
2020-05-02 [FIXED]    "**Qbert's Qubes**" (qbertqub): decode one data as a RAW intead of an INT      
2020-05-02 [FIXED]    "**Same! Same! Same! (2P set)**" (samesame2): different decoding than samesame    
2020-05-02 [REMOVED]  "**Space Invaders (SV Version rev 1)**": no good known dump      
2020-05-02 [FIXED]    "**Toki**" (toki, tokia, tokib, tokiu, tokiua, juju, jujub, jujuba): fix AREA to be base 10    
2020-05-02 [FIXED]    "**Metal Slug - Super Vehicle-001**" (mslug): fix RANK to be base 10    
2020-05-02 [IMPROVED] "**Super Bobble Bobble (bootleg)**" (sboblbobla, sboblboblb, sboblbobld, sboblboble, sboblboblf): remove special items decoding as they contain wrong values    
2020-05-02 [IMPROVED] "**Bubble Bobble (prototype on Tokio hardware)**" (bublboblp): remove special items decoding as they contain wrong values    
2020-04-29 [IMPROVED] "**Armed Police Batrider**" (batrider and clones): split into 4 tables, one per mode    
2020-04-28 [IMPROVED] "**Gauntlet**" (gauntlet): split into 4 tables and normalize output (with a SCORE column)    
2020-04-28 [IMPROVED] "**Double Dribble**" (ddribble, ddribblep): normalize output (renaming POINTS in SCORE)    
2020-04-28 [IMPROVED] "**Appoooh**" (appoooh): trim scores and normalize output (table, SCORE column)    
2020-04-28 [FIXED]    "**Crazy Kong**" (ckongs, ckongg, ckonggx, ckongmc): get score from the strin part, to avoid reading corrupted content    
2020-04-28 [FIXED]    "**Mad Planets (uk)**" (mplanetsuk): fix score by adding an initial padding different than its parent    
2020-04-28 [IMPROVED] "**Golden Axe**" (goldnaxe and clones): display scores for Tyris and Gilius also and convert strength into score    
2020-04-28 [IMPROVED] "**Rally X**" (dngrtrck, nrallyx, nrallyxb, rallyx, rallyxa, rallyxm, rallyxmr): improve output so that LaunchBox can get the top score    
2020-04-28 [FIXED]    "**Battle of Atlantis (bootleg)**" (atlantisb): keep only 1 score    
2020-04-28 [FIXED]    "**Battle of Atlantis (set 2)**" (atlantis2): add a padding at the start versus atlantis    
2020-04-28 [REMOVED]  "**Black Widow (prototype)**" (bwidowp): nvram content is not emulated correctly    
2020-04-28 [FIXED]    "**The Three Stooges In Brides Is Brides (set 2)**" (3stoogesa): add more additional data at the start than 3stooges    
2020-04-27 [FIXED]    "**Rainbow Island**" (rbisland, rbislande, rbislando): score is decoded from 4 bytes instead of only 3    
2020-04-27 [FIXED]    "**The Three Stooges In Brides Is Brides**" (3stooges, 3stoogesa): decode only 21 entries instead of 22    
2020-04-26 [IMPROVED] "**Alien Sector**" (aliensec, baraduke): names are trimmed and alien face character replaced by smiley for more compatibility    
2020-04-26 [ADDED]    "**Cosmic Chasm**" (cchasm, cchasm1)    
2020-04-25 [FIXED]    "**Zaxxon**" (zaxxon, zaxxonb, zaxxon2, zaxxon3, zaxxonj, szaxxon): scores are fixed using little-endian    
2020-04-23 [ADDED]    "**Complex X**" (complexx)    
2020-04-23 [FIXED]    "**Ghouls'n Ghosts**" (ghouls, ghoulsu, daimakai, daimakair): scores are now ordered correctly    
2020-04-22 game: fix            "G-Darius Ver.2" (gdarius2) with a specific decoding different than gdarius, showing 5 different hiscores tables     
2020-04-21 game: fix            "Sagaia" (sagaia) to add an additional padding at the start versus darius2     
2020-04-20 game: fix            "Zero Team" (zeroteam) and "New Zero Team" (nzeroteam) to take only 4 bits for the score instead of 6     
2020-04-19 game: fix            "Space Invaders" clones are fixed: some of the 31 clones need the score to be *100, other *10, other *1     
2020-04-16 game: fix            "Power Spikes" (pspikes) decoding user name letters encoded differently than the default names     
2020-04-15 game: fix            "Dig Dug" (digdug) decoding all scores from nvram only as .hi file gets corrupted sometimes     
2020-04-15 game: fix            "Alpine ski" (alpine) using correct endianness for the score     
2020-04-12 game: support/decode "Ashura Blaster (World)" (ashura)     
2020-04-12 game: support        "Ashura Blaster (Japan)" (ashuraj)     
2020-04-11 game: fix            "Omega" (omega)     
2020-04-11 game: fix            "Paperboy" (paperboy)     
2020-04-11 game: fix            "Viewpoint" (viewpoin)     
2020-04-11 game: fix            "Western Express" (wexpress)     
2020-04-11 game: fix            "Ghosts'n Goblins (prototype)" (gngprot)     
2020-04-11 game: fix            "Asteroids (rev 1)" (asteroid1)     
2020-04-11 game: fix            "Meteorites (VGG bootleg of Asteroids)" (meteorts)     
2020-04-11 game: support        "Hunchback (DK conversion)" (hunchbkd)     
2020-04-11 game: support        "Hunchback (Galaxian hardware)" (hunchbkg)     
2020-04-11 game: support        "Hunchback (Scramble hardware)" (hunchbks)     
2020-04-11 game: support        "Hunchback (Scramble hardware, bootleg)" (hunchbks2)     
2020-04-11 game: support        "Lode Runner IV - Teikoku Karano Dasshutsu (Japan)" (ldrun4)     
2020-03-30 game: support        "Klax (version 5)" (klax5)     
2020-03-30 game: support        "Klax (version 4)" (klax4)     
2020-03-30 game: support        "Klax (Japan, version 4)" (klaxj4)     
2020-03-30 game: support        "Klax (Japan, version 3)" (klaxj3)     
2020-03-30 game: support        "Klax (Germany, version 2)" (klaxd2)     
2020-03-30 game: fix            "Klax" (klax and clones) for mame 0.219     
2020-03-30 game: support        "Wyvern F-0" (wyvernf0a)     
2020-03-30 game: support        "Verbena (bootleg of Carnival)" (verbena)     
2020-03-30 game: support        "Venture (version 5 set 2, bootleg)" (venture2b)     
2020-03-30 game: support        "Teenage Mutant Ninja Turtles - Turtles in Time (4 Players ver UEA)" (tmnt24pu)     
2020-03-30 game: support        "Vs. Super Mario Bros. (bootleg with Z80, set 1)" (suprmriobl)     
2020-03-30 game: support        "Vs. Super Mario Bros. (bootleg with Z80, set 2)" (suprmriobl2)     
2020-03-30 game: support        "Vs. Super Mario Bros. (bootleg with Z80, set 3)" (suprmriobl3)     
2020-03-30 game: support        "Pipi & Bibis / Whoopee!! (bootleg, set 2)" (pipibibsbl2)     
2020-03-30 game: support        "Pac Man (U.G. bootleg of Puck Man)" (pacmanug)     
2020-03-30 game: support        "P-47 - The Freedom Fighter (World, bootleg)" (p47b)     
2020-03-30 game: support        "Knights of the Round (bootleg with 2xMSM5205, set 2)" (knightsb3)     
2020-03-30 game: support        "Knights of the Round (bootleg, World 911127)" (knightsb2)     
2020-03-30 game: support        "Frogger (Sega set 3)" (froggers3)     
2020-03-30 game: support        "Dragon Breed (Japan, M72 PCB version)" (dbreedm72j)     
2020-03-30 game: support        "Cosmic Alien (version II, set 2)" (cosmica3)     
2020-03-30 game: support        "Commando (bootleg set 3)" (commandob3)     
2020-03-30 game: support        "Crazy Kong Part II (bootleg)" (ckongpt2b2)     
2020-03-29 game: support        "Centipede (revision 1)" (centiped1)     
2020-03-29 game: support        "Block Out (Europe and Oceania)" (blockout3)     
2020-03-29 game: support        "Berzerk (revision RC28)" (berzerkb)     
2020-03-29 game: support        "Berzerk (revision RC31)" (berzerka)     
2020-03-29 game: support        "19XX: The War Against Destiny (USA 951207)" (19xxu)     
2020-03-29 game: fix            "Kangaroo" (kangaroo, kangarooa, kangaroob) for mame 0.219     
2020-03-23 game: support/decode "Flicky (128k Version, 315-5051)" (flicky)     
2020-03-23 game: support        "Flicky (128k Version, 315-5051, larger roms)" (flickya)     
2020-03-23 game: support        "Flicky (64k Version, 315-5051, set 1)" (flickyo)     
2020-03-23 game: support        "Flicky (64k Version, 315-5051, set 2)" (flickys1)     
2020-03-23 game: support        "Flicky (128k Version, not encrypted)" (flickys2)     
2020-03-23 game: support        "Flicky (64k Version, on Up'n Down boardset)" (flickyup)     
2020-03-18 game: support/decode "Avenging Spirit" (avspirit)     
2020-03-18 game: support        "Phantasm (Japan)" (phantasm)     
2020-03-18 game: support/decode "Avengers In Galactic Storm (US/Europe 1.0)" (avengrgs)     
2020-03-18 game: support        "Avengers In Galactic Storm (Japan 1.2)" (avengrgsj)     
2020-03-18 game: support/decode "Avalanche" (avalnche)     
2020-03-18 game: support        "Cascade" (cascade)     
2020-03-17 game: support/decode "Attack UFO" (attckufo)     
2020-03-17 game: support/decode "Atomic Boy (revision B)" (atomboy)     
2020-03-17 game: support        "Atomic Boy (revision A)" (atomboya)     
2020-03-17 game: support        "Wily Tower" (wilytowr)     
2020-03-17 game: support/decode "Asuka & Asuka (World)" (asuka)     
2020-03-17 game: support        "Asuka & Asuka (Japan)" (asukaj)     
2020-03-17 game: support/decode "Astro Flash (Japan)" (astrofl)     
2020-03-17 game: support        "Transformer" (transfrm)     
2020-03-17 game: support/decode "Astro Fantasia (DECO Cassette) (US)" (castfant)     
2020-03-17 game: support/decode "Astro Blaster (version 3)" (astrob)     
2020-03-17 game: support        "Astro Blaster (version 2)" (astrob2)     
2020-03-17 game: support/decode "Astro Battle (set 1)" (abattle)     
2020-03-17 game: support        "Astro Battle (set 2)" (abattle2)     
2020-03-17 game: support        "Astro Combat (newer, CB)" (acombat)     
2020-03-17 game: support        "Astro Combat (older, PZ)" (acombat3)     
2020-03-17 game: support        "Astro Combat (unencrypted)" (acombato)     
2020-03-17 game: support        "Astro Fire" (afire)     
2020-03-17 game: support        "Astro Fighter (set 1)" (astrof)     
2020-03-17 game: support        "Astro Fighter (set 2)" (astrof2)     
2020-03-17 game: support        "Astro Fighter (set 3)" (astrof3)     
2020-03-17 game: support        "Super Star Battle" (sstarbtl)     
2020-03-17 game: support        "Star Fighter (bootleg of Astro Fighter)" (strfight)     
2020-03-16 game: support/decode "Arcadia (NMK)" (arcadian)     
2020-03-16 game: support        "Rapid Hero (NMK)" (raphero)     
2020-03-16 game: support        "Rapid Hero (Media Trading)" (rapheroa)     
2020-03-15 game: modify "1943" (1943) decoding to keep only 5 scores, thanks to contributor T. Busse!     
2020-03-15 game: support/decode "Arbalester" (arbalest)     
2020-03-13 game: support/decode "Altair" (altair)     
2020-03-13 game: support/decode "Alien vs. Predator (Euro 940520)" (avsp)     
2020-03-13 game: support/decode "Alien vs. Predator (Euro 940520)" (avsp)     
2020-03-13 game: support        "Alien vs. Predator (Asia 940520)" (avspa)     
2020-03-13 game: support        "Alien vs. Predator (Euro 940520 Phoenix Edition) (bootleg)" (avspd)     
2020-03-13 game: support        "Alien vs. Predator (Hispanic 940520)" (avsph)     
2020-03-13 game: support        "Alien vs. Predator (Japan 940520)" (avspj)     
2020-03-13 game: support        "Alien vs. Predator (USA 940520)" (avspu)     
2020-03-13 game: support/decode "Alien Arena" (alienar)     
2020-03-13 game: support        "Alien Arena (Stargate upgrade)" (alienaru)     
2020-03-12 game: support/decode "Haunted Castle (version M)" (hcastle)     
2020-03-12 game: support        "Haunted Castle (version E)" (hcastlee)     
2020-03-12 game: support        "Haunted Castle (version K)" (hcastlek)     
2020-03-12 game: support        "Akuma-Jou Dracula (Japan version P)" (akumajou)     
2020-03-12 game: support        "Akuma-Jou Dracula (Japan version N)" (akumajoun)     
2020-03-11 game: support/decode "Akai Katana" (akatana)     
2020-03-06 game: support/decode "Dynablaster / Bomber Man" (dynablst), thanks to contributor T. Busse!     
2020-03-06 game: support        "Dynablaster / Bomber Man (bootleg, set 1)" (dynablstb), thanks to contributor T. Busse!     
2020-03-06 game: support        "Dynablaster / Bomber Man (bootleg, set 2)" (dynablstb2), thanks to contributor T. Busse!     
2020-03-06 game: support        "Dynablaster / Bomber Man (bootleg, set 3)" (dynablstb3), thanks to contributor T. Busse!     
2020-03-06 game: support        "Dynablaster (bootleg)" (dynablsb), thanks to contributor T. Busse!     
2020-03-06 game: support        "Atomic Punk (US)" (atompunk), thanks to contributor T. Busse!     
2020-03-06 game: support        "Bomber Man (Japan)" (bombrman)     
2020-03-06 game: support/decode "Air Rescue (World)" (arescue)     
2020-03-06 game: support        "Air Rescue (Japan)" (arescuej)     
2020-03-06 game: support        "Air Rescue (US)" (arescueu)     
2020-03-06 game: support/decode "The Age of Heroes - Silkroad 2" (aoh)     
2019-09-14 game: support/decode "Cadash (World)" (cadash)     
2019-09-14 game: support        "Cadash (Germany, version 1)" (cadashg)     
2019-09-14 game: support        "Cadash (Italy)" (cadashi)     
2019-09-14 game: support        "Cadash (Spain, version 1)" (cadashs)     
2019-09-14 game: support        "Cadash (US, version 2)" (cadashu)     
2019-09-14 game: support        "Cadash (France)" (cadashf)     
2019-09-14 game: support        "Cadash (Japan, version 2)" (cadashj)     
2019-09-14 game: support        "Cadash (Japan, version 1)" (cadashj1)     
2019-09-14 game: support        "Cadash (Japan, oldest version)" (cadashjo)     
2019-09-14 game: support/decode "Zaviga" (zaviga)     
2019-09-14 game: support        "Zaviga (Japan)" (zavigaj)     
2019-09-14 game: support/decode "B-Wings (Japan new Ver.)" (bwings)     
2019-09-14 game: support/decode "B-Wings (Japan old Ver.)" (bwingso)     
2019-09-14 game: support        "B-Wings (Alt Ver.?)" (bwingsa)     
2019-09-13 game: support/decode "Cloak & Dagger (rev 5)" (cloak)     
2019-09-13 game: support        "Cloak & Dagger (French)" (cloakfr)     
2019-09-13 game: support        "Cloak & Dagger (German)" (cloakgr)     
2019-09-13 game: support        "Cloak & Dagger (Spanish)" (cloaksp)     
2019-09-11 game: support/decode "Act-Fancer Cybernetick Hyper Weapon (World revision 3)" (actfancr)     
2019-09-11 game: support        "Act-Fancer Cybernetick Hyper Weapon (World revision 1)" (actfancr1)     
2019-09-11 game: support        "Act-Fancer Cybernetick Hyper Weapon (World revision 2)" (actfancr2)     
2019-09-11 game: support        "Act-Fancer Cybernetick Hyper Weapon (Japan revision 1)" (actfancrj)     
2019-09-01 game: support/decode "X Multiply (World, M81)" (xmultipl), thanks to contributor T. Busse!     
2019-08-31 game: support/decode "Youjyuden (Japan)" (youjyudn), thanks to contributor T. Busse!     
2019-08-31 game: support/decode "Viewpoint" (viewpoin), thanks to contributor T. Busse!     
2019-08-31 game: support/decode "Rainbow Islands (new version)" (rbisland), thanks to contributor T. Busse!     
2019-08-31 game: support "Rainbow Islands (old version)" (rbislando)     
2019-08-31 game: support "Jumping (set 1)" (jumping)     
2019-08-31 game: support "Jumping (set 2)" (jumpinga)     
2019-08-31 game: support "Rainbow Islands - Extra Version" (rbislande)     
2019-08-31 game: support/decode "Lode Runner (set 1)" (ldrun), thanks to contributor T. Busse!     
2019-08-31 game: support "Lode Runner (set 2)" (ldruna)     
2019-08-31 game: support/decode "Lode Runner IV - Teikoku Karano Dasshutsu (Japan)" (ldrun4), thanks to contributor T. Busse!     
2019-08-31 game: support "Lode Runner II - The Bungeling Strikes Back" (ldrun2)     
2019-08-31 game: support "Lode Runner III - The Golden Labyrinth" (ldrun3)     
2019-08-31 game: support "Lode Runner III - Majin no Fukkatsu (Japan)" (ldrun3j)     
2019-08-31 game: modified "Gorf" (gorf) to match also 0.204     
2019-08-31 game: modified "Space Zap" (spacezap) to match also 0.212     
2019-08-31 game: support "Zero Time (Marti Colls)" (zerotimemc)     
2019-08-31 game: support "X-Men (4 Players ver JEA)" (xmenja)     
2019-08-31 game: support "Xevious 3D/G (World, XV32/VER.A)" (xevi3dga)     
2019-08-31 game: support "West Story (bootleg of Blood Bros., set 2)" (weststrya)     
2019-08-31 game: support "Wonder Boy (system 2, set 2, 315-5176)" (wboysys2a)     
2019-08-31 game: support "Vendetta (World, 4 Players, ver. ?)" (vendettaun)     
2019-08-31 game: support "Turbo Force (World, set 2)" (turbofrco)     
2019-08-31 game: support "Turbo Force (US)" (turbofrcu)     
2019-08-31 game: support "Titan (Pac-Man hack)" (titanpac)     
2019-08-31 game: support "The 26th Z (Japan, location test)" (the26thz)     
2019-08-31 game: support "Teki Paki (location test)" (tekipakit)     
2019-08-31 game: support "Tazz-Mania (Arfyc / Rodmar bootleg)" (tazmani3)     
2019-08-31 game: support "Tazz-Mania - El Trompa (U.R.V. BBCPE bootleg)" (tazmaniet)     
2019-08-31 game: support "Super Invasion (Electromar, Spanish)" (supinvsion)     
2019-08-31 game: support "Sorcer Striker (Korea)" (sstrikerk)     
2019-08-31 game: support "Snow Bros. 2 - With New Elves / Otenki Paradise (bootleg, set 2)" (snowbro2b2)     
2019-08-31 game: support "The Simpsons (4 Players World, set 2)" (simpsons4pe)     
2019-08-31 game: support "Silk Worm (bootleg)" (silkwormb)     
2019-08-31 game: support "Shinobi (set 6, System 16B) (unprotected)" (shinobi6)     
2019-08-31 game: support "Street Fighter II: The World Warrior (World 910204)" (sf2ea)     
2019-08-31 game: support "Street Fighter II: The World Warrior (World 910204, conversion)" (sf2en)     
2019-08-31 game: support "Street Fighter II: The World Warrior (Thunder Edition, bootleg, set 2)" (sf2thndr2)     
2019-08-31 game: support "Street Fighter II: The World Warrior (USA 910522, Rev. H)" (sf2uh)     
2019-08-31 game: support "Scramble (bootleg, set 2)" (scramb3)     
2019-08-31 game: support "Super Cobra (encrypted)" (scobrae2)     
2019-08-31 game: support "Super Cobra (bootleg, set 2)" (scobrag)     
2019-08-31 game: support "Super Cobra (bootleg, set 3)" (scobraggi)     
2019-08-31 game: support "Super Bobble Bobble (bootleg, set 4)" (sboblbobld)     
2019-08-31 game: support "Super Bobble Bobble (bootleg, set 5)" (sboblboble)     
2019-08-31 game: support "Super Bobble Bobble (bootleg, set 6)" (sboblboblf)     
2019-08-31 game: support "Super Bagman (Itisa, Spain)" (sbagmani)     
2019-08-31 game: support "Jiao! Jiao! Jiao! (China, 2P set)" (samesamecn)     
2019-08-31 game: support "Strikers 1945 (World, unprotected)" (s1945n)     
2019-08-31 game: support "Strikers 1945 (Japan, unprotected)" (s1945nj)     
2019-08-31 game: support "Rolling Thunder (oldest)" (rthunder0)     
2019-08-31 game: support "Rolling Thunder (rev 3, hack)" (rthundera)     
2019-08-31 game: support "River Patrol (Japan, unprotected)" (rpatroln)     
2019-08-31 game: support "Defend the Terra Attack on the Red UFO (bootleg, set 2)" (redufob2)     
2019-08-31 game: support "Red Clash (Suntronics)" (redclashs)     
2019-08-31 game: support "Red Clash (Tehkan, set 1)" (redclasht)     
2019-08-31 game: support "Red Clash (Tehkan, set 2)" (redclashta)     
2019-08-31 game: support "Raiden DX (Portugal)" (raidendxpt)     
2019-08-31 game: support "Raiden II (harder, Korea)" (raiden2k)     
2019-08-31 game: support "Popeye (bootleg set 2)" (popeyeb2)     
2019-08-31 game: support "Popeye (bootleg set 3)" (popeyeb3)     
2019-08-31 game: support "Phoenix (G. Universal Video bootleg)" (phoenixgu)     
2019-08-31 game: support "Pengo (Marti Colls bootleg on Pac-Man hardware, set 1)" (pengomc1)     
2019-08-31 game: support "Pengo (Marti Colls bootleg on Pac-Man hardware, set 2)" (pengomc2)     
2019-08-31 game: support "Pinball Action (Tecfri license)" (pbactiont)     
2019-08-31 game: support "Pac-Man (bootleg, Video Game SA)" (pacmanvg)     
2019-08-31 game: support "Pac Man (FAMARE S.A. bootleg of Puck Man)" (pacmanfm)     
2019-08-31 game: support "Pac-Land (Bally-Midway)" (paclandm2)     
2019-08-31 game: support "Omega (earlier)" (omegaa)     
2019-08-31 game: support "Naughty Boy (bootleg, set 2)" (naughtybb)     
2019-08-31 game: support "Come-Cocos (Ms. Pac-Man) (Cocamatic bootleg)" (mspacmanbco)     
2019-08-31 game: support "Ms. Pac-Man (Impeuropex bootleg)" (mspacmanbg2)     
2019-08-31 game: support "Ms. Pac-Man (Impeuropex bootleg)" (mspacmanbi)     
2019-08-31 game: support "Ms. Pac-Man (Marti Colls bootleg)" (mspacmbmc)     
2019-08-31 game: support "Moon Cresta (bootleg set 4)" (mooncrs5)     
2019-08-31 game: support "Shin-ip Sawon - Seok Dol-i" (mikiek)     
2019-08-31 game: support "Mario Bros. (bootleg on Ambush Hardware, set 2)" (mariobla)     
2019-08-31 game: support "Mario Bros. (US, Revision F)" (mariof)     
2019-08-31 game: support "Mandanga (bootleg of Mandinga on Galaxian hardware, set 2)" (mandingac)     
2019-08-31 game: support "Mandanga (bootleg of Mandinga on Galaxian hardware, set 1)" (mandingarf)     
2019-08-31 game: support "Ares no Tsubasa (Japan, rev. A)" (lwingsja)     
2019-08-31 game: support "Karate Champ (US VS version, set 4)" (kchampvs4)     
2019-08-31 game: support "Karate Champ (US VS version, set 3)" (kchampvs3)     
2019-08-31 game: support "Karate Blazers (World, Tecmo license)" (karatblzt)     
2019-08-31 game: support "Kamikaze (Euromatic S.A., Spanish bootleg of Scramble)" (kamikazesp)     
2019-08-31 game: support "Irion" (irion)     
2019-08-31 game: support "UFO Robot Attack (bootleg of Invasion, older set)" (invasiona2)     
2019-08-31 game: support "Halley's Comet (Japan, rev 1)" (halleyscj)     
2019-08-31 game: support "Halley's Comet (Japan)" (halleyscja)     
2019-08-31 game: support "Halley's Comet (Japan, prototype)" (halleyscjp)     
2019-08-31 game: support "Halley's Comet '87" (halleysc87)     
2019-08-31 game: support "Gunbird 2 (set 2)" (gunbird2a)     
2019-08-31 game: support "Gradius (Bubble System)" (gradiusb)     
2019-08-31 game: support "Gorf (program 1, with German Language ROM)" (gorfpgm1g)     
2019-08-31 game: support "G.I. Joe (World, EB8, prototype?)" (gijoeea)     
2019-08-31 game: support "Gemini Wing (Japan)" (geminij)     
2019-08-31 game: support "Gee Bee (UK)" (geebeea)     
2019-08-31 game: support "Galaxy Wars II (Defender bootleg)" (galwars2)     
2019-08-31 game: support "Galaxian Growing Galaxip / Galaxian Nave Creciente" (galaxrcgg)     
2019-08-31 game: support "Fenix (Niemer bootleg of Phoenix)" (fenixn)     
2019-08-31 game: support "Fantasy (Germany, set 2)" (fantasyg2)     
2019-08-31 game: support "Dock Man (set 2)" (dockmanb)     
2019-08-31 game: support "Dock Man (set 3)" (dockmanc)     
2019-08-31 game: support "Donkey Kong: Pauline Edition Rev 5 (2013-04-22)" (dkongpe)     
2019-08-31 game: support "Donkey Kong Junior (US, bootleg?)" (dkongjr2)     
2019-08-31 game: support "DJ Boy (Japan, set 2)" (djboyja)     
2019-08-31 game: support "DJ Boy (US, set 2)" (djboyua)     
2019-08-31 game: support "Crock-Man (Marti Colls bootleg of Rene Pierre Crock-Man)" (crockmnf)     
2019-08-31 game: support "Crash (alt)" (crasha)     
2019-08-31 game: support "Centipede (bootleg, set 2)" (centipdb2)     
2019-08-31 game: support "Centipede (Japan, revision 3)" (centipedj)     
2019-08-31 game: support "Carnival (upright, PIT8253 music)" (carnivalb)     
2019-08-31 game: support "Cabal (UK, Joystick)" (cabalukj)     
2019-08-31 game: support "Blood Bros. (Japan, rev A)" (bloodbroj)     
2019-08-31 game: support "Blood Bros. (Japan)" (bloodbroja)     
2019-08-31 game: support "Blood Bros. (US)" (bloodbrou)     
2019-08-31 game: support "Battlecry (Version C)" (battlcryc)     
2019-08-31 game: support "Battlecry (Prototype)" (battlcryp)     
2019-08-31 game: support "Athena (bootleg)" (athenab)     
2019-08-31 game: modified "Astro Blaster (version 1)" (astrob1) to match also 0.204     
2019-08-31 game: modified "Astro Blaster (version 2a)" (astrob2a) to match also 0.204     
2019-08-31 game: support "Astro Blaster (version 2b)" (astrob2b)     
2019-08-31 game: modified "Meteorites (VGG bootleg of Asteroids)" (meteorts) to match also 0.204     
2019-08-31 game: modified "Meteor (bootleg of Asteroids)" (meteorho) to match also 0.204     
2019-08-31 game: modified "Meteorite (Proel bootleg of Asteroids)" (meteorite) to match also 0.204     
2019-08-31 game: modified "Asteroids (rev 1)" (asteroid1) to match also 0.204     
2019-08-31 game: modified "Asterock (Sidam bootleg of Asteroids)" (asterock) to match also 0.204     
2019-08-31 game: modified "Asterock (Videotron bootleg of Asteroids)" (asterockv) to match also 0.204     
2019-08-31 game: modified "Hyperspace (bootleg of Asteroids)" (hyperspc) to match also 0.204     
2019-08-31 game: modified "Asteroids Deluxe (rev 3)" (astdelux) to match also 0.204     
2019-08-31 game: support "Asteroids Deluxe (rev 1)" (astdelux1)     
2019-08-31 game: support "Asteroids Deluxe (rev 2)" (astdelux2)     
2019-08-31 game: modified "Asteroids (bootleg on Lunar Lander hardware)" (asteroidb) to match also 0.204     
2019-08-31 game: modified "Asteroids (rev 2)" (asteroid2) to match also 0.204     
2019-08-31 game: modified "Asteroids (rev 4)" (asteroid) to match also 0.204     
2019-08-31 game: modified "Aerolitos (Spanish bootleg of Asteroids)" (aerolitos) to match also 0.204     
2019-08-18 game: support/decode "Fire Truck / Smokey Joe" firetrk     
2019-08-18 game: support/decode "The Ninja Warriors (World, later version)" ninjaw     
2019-08-18 game: support "The Ninja Warriors (Japan)" ninjawj     
2019-08-18 game: support "The Ninja Warriors (US, Romstar license)" ninjawu     
2019-08-18 game: support/decode "Gradius III (World, program code R)" gradius3     
2019-08-18 game: support "Gradius III (Asia)" gradius3a     
2019-08-18 game: support "Gradius III (Japan, program code S)" gradius3j     
2019-08-18 game: support "Gradius III (Japan, program code S, split)" gradius3js     
2018-12-10 game: support "Amigo (bootleg of Amidar, set 2)" (amigo2)     
2018-12-10 game: support "Soldier Girl Amazon (Tecfri license)" (amazont)     
2018-12-10 game: support "Alien3: The Gun (Japan)" (alien3j)     
2018-12-10 game: support "Action Fighter (unprotected)" (afightera)     
2018-12-10 game: support "Action Fighter (unprotected, analog controls)" (afighterb)     
2018-12-10 game: support "Action Fighter (FD1089B 317-unknown)" (afighterc)     
2018-12-10 game: support "Action Fighter (FD1089B 317-unknown, analog controls)" (afighterd)     
2018-12-10 game: support "Action Fighter (System 16B, unprotected, analog controls)" (afightere)     
2018-12-10 game: support "Action Fighter (System 16B, FD1089B 317-unknown, analog controls)" (afighterf)     
2018-12-10 game: support "Action Fighter (System 16B, FD1089B 317-unknown)" (afighterg)     
2018-12-10 game: support "Action Fighter (System 16B, FD1089A 317-0018)" (afighterh)     
2018-12-10 game: support "'99: The Last War (bootleg)" (99lstwarb)     
2018-12-10 game: support "800 Fathoms (older)" (800fatha)     
2018-12-09 game: support/decode "Wacko" (wacko)     
2018-12-09 game: support/decode "Two Tigers (Tron conversion)" (twotigerc, twotigrc)     
2018-12-09 game: support "Two Tigers (dedicated)" (twotiger, twotigra)     
2018-12-09 game: support/decode "Time Pilot '84 (set 1)" (tp84)     
2018-12-09 game: support "Time Pilot '84 (set 2)" (tp84a)     
2018-12-09 game: support "Time Pilot '84 (set 3)" (tp84b)     
2018-12-09 game: support "Spy Hunter (Playtronic license)" (spyhuntp)     
2018-12-09 game: support/decode "Spy Hunter" (spyhunt)     
2018-12-09 game: support "Spy Hunter (Playtronic license)" (spyhuntp)     
2018-12-08 game: support/decode "Solar Fox (upright)" (solarfox)     
2018-12-08 game: support/decode "Satan's Hollow (set 1)" (shollow)     
2018-12-08 game: support "Satan's Hollow (set 2)" (shollow2)     
2018-12-02 game: support/decode "Rampage (Rev 3, 8/27/86)" (rampage)     
2018-12-02 game: support "Rampage (Rev 2, 8/4/86)" (rampage2)     
2018-12-02 game: support/decode "Omega Race" (omegrace)     
2018-12-02 game: support "Delta Race" (deltrace)     
2018-12-02 game: support/decode "Kozmik Kroozr" (kroozr)     
2018-12-02 game: support/decode "Espial (US?)" (espialu)     
2018-12-02 game: support "Espial (Europe)" (espial)     
2018-12-02 game: support/decode "Demolition Derby (cocktail)" (demoderbc)     
2018-12-02 game: support "Demolition Derby" (demoderb)     
2018-12-02 game: support "Demolition Derby (MCR-3 Mono Board Version)" (demoderm)     
2018-12-02 game: support/decode "Son Son" (sonson)     
2018-12-02 game: support "Son Son (Japan)" (sonsonj)     
2018-12-01 game: support/decode "Snap Jack" (snapjack)     
2018-12-01 game: support/decode "Zektor" (zektor)     
2018-12-01 game: support/decode "Warlords" (warlords)     
2018-12-01 game: support/decode "Tac/Scan" (tacscan)     
2018-12-01 game: support/decode "Star Trek" (startrek)     
2018-11-30 game: support/decode "Pac & Pal" (pacnpal)     
2018-11-30 game: support "Pac & Pal (older)" (pacnpal2)     
2018-11-30 game: support "Pac-Man & Chomp Chomp" (pacnchmp)     
2018-11-29 game: support/decode "Loco-Motion" (locomotn)     
2018-11-29 game: support "Loco-Motion (bootleg)" (locoboot)     
2018-11-29 game: support "Guttang Gottong" (gutangtn)     
2018-11-29 game: support "Cotocoto Cottong" (cottong)     
2018-11-25 game: support/decode "Exed Exes" (exedexes)     
2018-11-25 game: support "Savage Bees" (savgbees)     
2018-11-25 game: support/decode "Eliminator (2 Players, set 1)" (elim2)     
2018-11-25 game: support "Eliminator (2 Players, cocktail)" (elim2c)     
2018-11-25 game: support "Eliminator (2 Players, set 2)" (elim2a)     
2018-11-25 game: support "Eliminator (4 Players)" (elim4)     
2018-11-25 game: support "Eliminator (4 Players, prototype)" (elim4p)     
2018-11-01 game: support "Scrambled Egg" (scregg)     
2018-11-01 game: support/decode "Eggs (USA)" (eggs)     
2018-11-01 game: support "Space Duel (Prototype)" (spacduel0)     
2018-11-01 game: support "Space Duel (Version 1)" (spacduel1)     
2018-11-01 game: support/decode "Space Duel (Version 2)" (spacduel)     
2018-10-24 game: support "Gravitar" (gravitar)     
2018-10-24 game: support "Gravitar (version 1)" (gravitar1)     
2018-10-24 game: support/decode "Gravitar (version 2)" (gravitar2)     
2018-10-23 game: support "Black Widow (prototype)" (bwidowp)     
2018-10-23 game: support/decode "Black Widow" (bwidow)     
2018-10-21 game: support "The Three Stooges In Brides Is Brides (set 2)" (3stoogesa)     
2018-10-21 game: support/decode "The Three Stooges In Brides Is Brides (set 1)" (3stooges)     
2018-10-21 game: support/decode "Wild Western (set 1)" (wwestern1)     
2018-10-21 game: support "Wild Western (set 2)" (wwestern)     
2018-10-19 game: support/decode "Prehistoric Isle 2" (preisle2)     
2018-10-18 game: support/decode "Prehistoric Isle in 1930 (World)" (prehisle)     
2018-10-18 game: support "Prehistoric Isle in 1930 (US)" (prehisleu)     
2018-10-18 game: support "Prehistoric Isle in 1930 (Korea)" (prehislek)     
2018-10-18 game: support "Genshi-Tou 1930's" (gensitou)     
2018-10-14 game: support/decode "Guardian (US)" (grdian)     
2018-10-14 game: support "Get Star (bootleg set 1)" (getstarb1)     
2018-10-14 game: support "Get Star (bootleg set 2)" (getstarb2)     
2018-10-14 game: support "Get Star (Japan)" (getstarj)     
2017-12-22 game: support/decode "Radar Scope" (radarscp), thanks to contributor T. Busse!     
2017-12-22 game: support "Radar Scope (TRS01)" (radarscp1)     
2017-12-22 game: support/decode "R2D Tank" (r2dtank), thanks to contributor T. Busse!     
2017-12-18 game: support/decode "Star Force" (starforc)     
2017-12-18 game: support "Star Force (encrypted, set 2)" (starforca)     
2017-12-18 game: support "Star Force (encrypted, bootleg)" (starforcb)     
2017-12-18 game: support "Star Force (encrypted, set 1)" (starforce)     
2017-12-18 game: support "Mega Force (World)" (megaforc)     
2017-12-18 game: support "Mega Force (US)" (megaforcu)     
2017-12-18 game: support/decode "Rescue" (rescue)     
2017-12-18 game: support "Apocaljpse Now (bootleg of Rescue)" (aponow)     
2017-12-17 game: support/decode "Mysterious Stones - Dr. John's Adventure" (mystston)     
2017-12-17 game: support "Mysterious Stones - Dr. Kick in Adventure" (myststono)     
2017-12-17 game: support "Mysterious Stones - Dr. Kick in Adventure (Itisa PCB)" (myststonoi)     
2017-12-17 game: support/decode "Hunchback (set 1)" (hunchbak)     
2017-12-17 game: support "Hunchback (Galaxian hardware)" (hunchbkg)     
2017-12-17 game: support "Hunchback (DK conversion)" (hunchbkd)     
2017-12-17 game: support "Hunchback (Scramble hardware)" (hunchbks)     
2017-12-17 game: support "Hunchback (Scramble hardware, bootleg)" (hunchbks2)     
2017-12-17 game: support "Hunchback (set 2)" (hunchbka)     
2017-12-17 game: support/decode "Splat!" (splat)     
2017-12-17 game: support/decode "Space Zap" (spacezap)     
2017-12-17 game: support/decode "Sinistar (revision 3)" (sinistar)     
2017-12-17 game: support "Sinistar (prototype version)" (sinistar1, sinista1)     
2017-12-17 game: support "Sinistar (revision 2)" (sinistar2, sinista2)     
2017-12-15 game: support/decode "Reactor" (reactor)     
2017-12-15 game: support/decode "Jr. Pac-Man (Pengo hardware)" (jrpacmbl)     
2017-12-15 game: support/decode "Jr. Pac-Man (11/9/83)" (jrpacman)     
2017-12-15 game: support "Jr. Pac-Man (speedup hack)" (jrpacmanf)     
2017-12-14 game: support/decode "Bubbles" (bubbles)     
2017-12-14 game: support "Bubbles (Solid Red label)" (bubblesr)     
2017-12-14 game: support "Bubbles (prototype version)" (bubblesp)     
2017-12-12 game: support/decode "Blaster" (blaster)     
2017-12-12 game: support "Blaster (conversion kit)" (blasterkit)     
2017-12-12 game: support "Blaster (location test)" (blastero)     
2017-12-10 game: support/decode "Stargate" (stargate)     
2017-12-10 game: support/decode "Diamond Run" (diamond)     
2017-12-10 game: support/decode "Super Pac-Man" (superpac)     
2017-12-10 game: support "Super Pac-Man (Midway)" (superpacm)     
2017-12-10 game: support/decode "Invader's Revenge (set 1)" (invrvnge)     
2017-12-10 game: support "Invader's Revenge (set 2)" (invrvngea)     
2017-12-10 game: support "Invader's Revenge (set 3)" (invrvngeb)     
2017-12-10 game: support "Invader's Revenge (Dutchford, single PCB)" (invrvngedu)     
2017-12-10 game: support "Invader's Revenge (Game World, single PCB)" (invrvngegw)     
2017-12-10 game: support/decode "Krull" (krull)     
2017-12-05 game: support/decode "Arabian" (arabian)     
2017-12-05 game: support "Arabian (Atari)" (arabiana)     
2017-12-05 game: support/decode "Seicross" (seicross)     
2017-12-05 game: support "Sector Zone" (sectrzon)     
2017-12-05 game: support/decode "Pepper II (version 8)" (pepper2)     
2017-12-05 game: support "Pepper II (version 7)" (pepper27)     
2017-12-05 game: support "Hard Hat" (hardhat)     
2017-12-03 game: support/decode "Space Panic (set 2)" (panic)     
2017-12-03 game: support "Space Panic (set 2)" (panic2)     
2017-12-03 game: support "Space Panic (set 3)" (panic3)     
2017-12-03 game: support "Space Panic (German)" (panicger)     
2017-12-03 game: support "Space Panic (harder)" (panich)     
2017-12-03 game: support/decode "Mouse Trap (version 5)" (mtrap)     
2017-12-03 game: support "Mouse Trap (version 2)" (mtrap2)     
2017-12-03 game: support "Mouse Trap (version 3)" (mtrap3)     
2017-12-03 game: support "Mouse Trap (version 4)" (mtrap4)     
2017-12-03 game: support "Mouse Trap (bootleg)" (mtrapb)     
2017-12-03 game: support "Mouse Trap (version 4, bootleg)" (mtrapb2)     
2017-12-02 game: support/decode "Mad Planets" (mplanets)     
2017-12-02 game: support "Mad Planets (UK)" (mplanetsuk, mplanuk)     
2017-12-01 game: support/decode "Venture (version 5 set 1)" (venture)     
2017-12-01 game: support "Venture (version 5 set 2)" (venture2)     
2017-12-01 game: support "Venture (version 4)" (venture4)     
2017-12-01 game: support/decode "Fantasy (US)" (fantasy)     
2017-12-01 game: support "Fantasy (US)" (fantasyu)     
2017-12-01 game: support "Fantasy (Japan)" (fantasyj)     
2017-12-01 game: support "Fantasy (Germany)" (fantasyg)     
2017-12-01 game: support/decode "Vanguard" (vanguard)     
2017-12-01 game: support "Vanguard (Centuri)" (vanguardc)     
2017-12-01 game: support "Vanguard (Japan)" (vanguardj)     
2017-12-01 game: support/decode "Lost Tomb (easy)" (losttomb)     
2017-12-01 game: support "Lost Tomb (hard)" (losttombh)     
2017-12-01 game: support/decode "Jump Bug" (jumpbug)     
2017-12-01 game: support "Jump Bug (bootleg)" (jumpbugb)     
2017-12-01 game: support/decode "Moon Quasar" (moonqsr)     
2017-11-30 game: support/decode "Moon Base Zeta (set 1)" (moonbase)     
2017-11-30 game: support "Moon Base Zeta (set 2)" (moonbasea)     
2017-11-30 game: support/decode "Space Invaders Deluxe" (invaddlx)     
2017-11-30 game: support "Space Invaders Part II (Taito)" (invadpt2)     
2017-11-30 game: support/decode "Galaxy Wars (Taito?)" (galxwarst)     
2017-11-30 game: support "Galaxy Wars (Universal set 1)" (galxwars)     
2017-11-30 game: support "Galaxy Wars (Universal set 2)" (galxwars2)     
2017-11-30 game: support "Galaxy Wars (Taito)" (galxwarst2)     
2017-11-30 game: support "Star Wars (bootleg of Galaxy Wars, set 1)" (starw)     
2017-11-30 game: support "Star Wars (bootleg of Galaxy Wars, set 2)" (starw1)     
2017-11-30 game: support/decode "Gorf" (gorf)     
2017-11-30 game: support "Gorf (program 1)" (gorfpgm1)     
2017-11-26 game: support "Chuka Taisen (Japan) (P0-025-A PCB)" (chukataija)     
2017-11-26 game: support "Crime Fighters 2 (Japan, 4 Players, ver. N)" (vendettan)     
2017-11-26 game: support "Vendetta (Asia, 4 Players, ver. Z)" (vendettaz)     
2017-11-26 game: support "Port Man (Japan)" (portmanj)     
2017-11-26 game: support "Super Athena (bootleg)" (sathena)     
2017-11-26 game: support "Popeye (Japan, Sky Skipper hardware, Older)" (popeyejo)     
2017-11-26 game: support "DoDonPachi III (World, 2002.05.15 Master Ver)" (ddp3)     
2017-11-26 game: support "Metal Slug 2 Turbo (NGM-9410) (hack)" (mslug2t)     
2017-11-26 game: support "Air Duel (Japan, M72)" (airduelm72)     
2017-11-26 game: support "Donkey Kong Jr. (bootleg on Moon Cresta hardware, set 2)" (dkongjrmc)     
2017-11-26 game: support " Street Fighter II: The World Warrior (Quicken, bootleg)" (sf2qp2)     
2017-11-26 game: support "Ghouls'n Ghosts (World)" (ghouls) new location     
2017-11-26 game: support "Crazy Climber (US set 2)" (cclimbera)     
2017-11-26 game: support "Mega Zone (program code J)" (megazonej)     
2017-11-26 game: support "1943: Midway Kaisen (Japan, no protection hack)" (1943jah)     
2017-11-26 game: support "Crime Fighters 2 (Japan, 2 Players, ver. P)" (vendetta2pp)     
2017-11-26 game: support "Vendetta (World, 2 Players, ver. W)" (vendetta2pw)     
2017-11-26 game: support "Silk Worm (prototype?)" (silkwormp)     
2017-11-26 game: support "Operation Wolf (Japan, SC)" (opwolfjsc)     
2017-11-26 game: support "Mega Zone (program code H)" (megazoneh)     
2017-11-26 game: support "Western Express (bootleg set 3)" (wexpressb3)     
2017-11-26 game: support "Western Express (bootleg set 2)" (wexpressb2)     
2017-11-26 game: support "Western Express (bootleg set 1)" (wexpressb1)     
2017-11-26 game: support "Western Express (Japan, rev 4)" (wexpress)     
2017-11-26 game: support "Express Raider (World, Rev 4)" (exprraid) new location     
2017-11-26 game: support "Express Raider (Italy)" (exprraidi) new location     
2017-11-26 game: support "Street Fighter II: The World Warrior (Japan 911210, CPS-B-17)" (sf2j17)     
2017-11-26 game: support "Bubble Bobble (prototype on Tokio hardware)" (bublboblp)     
2017-11-26 game: support "Mach-9 (bootleg of Vulgus)" (mach9)     
2017-11-26 game: support "Palamedes (Japan)" (palamedj)     
2017-11-26 game: support "Wonder Boy (set 6, 315-5179)" (wboy6)     
2017-11-26 game: support "Nibbler (rev 7)" (nibbler7)     
2017-11-26 game: support "Offensive (Spanish bootleg of Scramble)" (offensiv)     
2017-11-26 game: support "Rastan Saga (Japan, Earlier code base)" (rastsagab)     
2017-11-26 game: support "Danger Track (Rally X bootleg)" (dngrtrck)     
2017-11-26 game: support "Phoenix (Hellomat Automaten bootleg)" (phoenixha)     
2017-11-26 game: support "Pengo (set 5)" (pengo5)     
2017-11-26 game: support "Operation Thunderbolt (Japan, SC)" (othunderjsc)     
2017-11-26 game: support "Jackal (bootleg, Rotary Joystick)" (jackalbl)     
2017-11-26 game: support "Gingateikoku No Gyakushu (bootleg set 1)" (gteikokub)     
2017-11-26 game: support "Gingateikoku No Gyakushu (bootleg set 2)" (gteikokub2)     
2017-11-26 game: support "Gingateikoku No Gyakushu (bootleg set 3)" (gteikokub3)     
2017-11-26 game: support "Mandinga (bootleg of Amidar)" (mandinga)     
2017-11-26 game: support "Spectar (revision 2, bootleg)" (spectarrf)     
2017-11-26 game: support "Burnin' Rubber (DECO Cassette) (Japan)" (cburnrubj)     
2017-11-26 game: support "Cadillacs and Dinosaurs (Asia TW 930223, bootleg?)" (dinoa)     
2017-11-26 game: support "Bagman (Taito)" (bagmanj)     
2017-11-26 game: support "Space War Part 3" (spacewr3) new location     
2017-11-26 game: support "Space War (Leisure and Allied)" (spcewarla)     
2017-11-26 game: support "Space Wipeout" (swipeout)     
2017-11-26 game: support "Rastan (World, Earlier code base)" (rastanb)     
2017-11-26 game: support/decode "Raiden DX" (raidendx) new location from mame 0.186     
2017-11-26 game: support "Up Maguila (bootleg of Donkey Kong Jr.)" (maguila)     
2017-11-26 game: support/decode "The Empire Strikes Back" (esb) new location from mame 0.184, thanks to contributor T. Busse!     
2017-11-26 game: support "Missile Attack" (missilea)     
2017-11-26 game: support "Dungeons & Dragons: Shadow over Mystara (Japan 960223)" (ddsomjr2)     
2017-11-26 game: support/decode "The Pit" (roadf) new location from mame 0.184, thanks to contributor T. Busse!     
2017-11-26 game: support "The King of Fighters '99 - Millennium Battle (Korean release, non-encrypted program)" (kof99ka)     
2017-11-26 game: support "Omega (bootleg?)" (omegab)     
2017-11-25 game: support "Coccinelle (bootleg of Lady Bug, set 2)" (ladybugb2)     
2017-11-25 game: support/decode "Forgotten Worlds (World, newer)" (forgottn)     
2017-11-25 game: support "Forgotten Worlds (USA, B-Board 88621B-2, Rev. C)" (forgottnu)     
2017-11-25 game: support "Forgotten Worlds (USA, B-Board 88618B-2, Rev. A)" (forgottnua)     
2017-11-25 game: support "Forgotten Worlds (USA, B-Board 88618B-2, Rev. AA)" (forgottnuaa)     
2017-11-25 game: support "Forgotten Worlds (USA, B-Board 88618B-2, Rev. C)" (forgottnuc)     
2017-11-25 game: support "Forgotten Worlds (USA, B-Board 88618B-2, Rev. E)" (forgottnuc)     
2017-11-25 game: support "Lost Worlds (Japan)" (lostwrld)     
2017-11-25 game: support "Lost Worlds (Japan Old Ver.)" (lostwrldo)     
2017-11-25 game: support/decode "The Pit" (thepit), thanks to contributor T. Busse!     
2017-11-25 game: support "The Pit (bootleg on Moon Quasar hardware)" (thepitm)     
2017-11-25 game: support "The Pit (Japan)" (thepitj)     
2017-11-25 game: support "The Pit (US set 1)" (thepitu1)     
2017-11-25 game: support "The Pit (US set 2)" (thepitu2)     
2017-11-25 game: support/decode "Mirax (set 1)" (mirax), thanks to contributor T. Busse!     
2017-11-25 game: support "Mirax (set 2)" (miraxa)     
2017-11-25 game: support/decode "Mega Zone (program code L)" (megazone), thanks to contributor T. Busse!     
2017-11-25 game: support "Mega Zone (unknown program code 1)" (megazonea)     
2017-11-25 game: support "Mega Zone (unknown program code 2)" (megazoneb)     
2017-11-25 game: support "Mega Zone (Kosuka set 2)" (megazonec)     
2017-11-25 game: support "Mega Zone (program code I)" (megazonei)     
2017-11-20 game: support/decode "Blasteroids (rev 4)" (blstroid), with help from contributor T. Busse!     
2017-11-20 game: support "Blasteroids (rev 2)" (blstroid2)     
2017-11-20 game: support "Blasteroids (rev 3)" (blstroid3)     
2017-11-20 game: support "Blasteroids (German, rev 2)" (blstroidg)     
2017-11-20 game: support "Blasteroids (with heads)" (blstroidh)     
2017-11-19 game: support/decode "NATO Defense" (natodef), thanks to contributor T. Busse!     
2017-11-19 game: support "NATO Defense (alternate mazes)" (natodefa)     
2017-11-19 game: support/decode "Gaplus (GP2 rev. B)" (gaplus), thanks to contributor T. Busse!     
2017-11-19 game: support "Gaplus (GP2)" (gaplusa)     
2017-11-19 game: support "Gaplus (GP2 rev D, alternate hardware)" (gaplusd)     
2017-11-19 game: support/decode "Galaga 3 (GP3 rev. D)" (galaga3)     
2017-11-19 game: support "Galaga 3 (GP3 rev. C)" (galaga3a)     
2017-11-19 game: support "Galaga 3 (GP3)" (galaga3b)     
2017-11-19 game: support "Galaga 3 (set 4)" (galaga3c)     
2017-11-19 game: support "Galaga 3 (set 5)" (galaga3m)     
2017-11-19 game: support "Gaplus (Tecfri PCB)" (gaplust)     
2017-11-19 game: support/decode "Dawin 4078 (Japan)" (darwin), thanks to contributor T. Busse!     
2017-11-19 game: support/decode "Vs. Battle City" (btlecity), thanks to contributor T. Busse!     
2017-11-19 game: support/decode "Halley's Comet (US)" (halleys), thanks to contributor T. Busse!     
2017-11-19 game: support "Halley's Comet (Japan, Newer)" (halleysc)     
2017-11-19 game: support "Halley's Comet (Japan, Older)" (halleycj)     
2017-11-19 game: support "Halley's Comet '87" (halley87)     
2017-11-19 game: support/decode "Horizon" (horizon), thanks to contributor T. Busse!     
2017-11-19 game: minor improvement to astdelux     
2017-11-19 game: minor improvement to gyruss     
2017-02-18 game: support/decode "Ghostlop (prototype)" (ghostlop)     
2017-02-18 game: support/decode "Ghost Pilots (NGM-020 ~ NGH-020)" (gpilots)     
2017-02-18 game: support "Ghost Pilots (NGH-020, US)" (gpilotsh)     
2017-02-18 game: support/decode "Eightman" (eightman)     
2017-02-18 game: support/decode "Cyber-Lip" (cyberlip)     
2017-02-18 game: support/decode "Crossed Swords 2 (bootleg of CD version)" (crswd2bl)     
2017-02-14 game: support/decode "Choutetsu Brikin'ger - Iron Clad (prototype)" (ironclad)     
2017-02-14 game: support "Choutetsu Brikin'ger - Iron Clad (prototype, bootleg)" (ironclado)     
2017-02-14 game: support/decode "Bang Bang Busters (2010 NCI release)" (b2b)     
2017-02-12 game: support/decode "Zero Hour (set 1)" (zerohour), thanks to contributor T. Busse!     
2017-02-12 game: support "Zero Hour (set 2)" (zerohoura)     
2017-02-12 game: support "Zero Hour (Inder)" (zerohouri)     
2017-02-12 game: support/decode "Space Fury (revision C)" (spacfury), thanks to contributor T. Busse!     
2017-02-12 game: support "Space Fury (revision A)" (spacfurya)     
2017-02-12 game: support/decode "Space Bird (bootleg)" (spacefb), thanks to contributor T. Busse!     
2017-02-12 game: support "Space Firebird (bootleg)" (spacefbb)     
2017-02-12 game: support "Space Firebird (rev. 03-e set 1)" (spacefbe)     
2017-02-12 game: support "Space Firebird (Nintendo, set 2)" (spacefbu)     
2017-02-12 game: support "Space Firebird (rev. 03-e set 2)" (spacefbe2)     
2017-02-12 game: support "Star Warrior" (starwarr)     
2017-02-12 game: support/decode "Space Cruiser" (spacecr), thanks to contributor T. Busse! (not yet into official hiscore.dat)     
2017-02-12 game: support/decode "Pitfall II (315-5093)" (pitfall2), thanks to contributor T. Busse!     
2017-02-12 game: support "Pitfall II (315-5093, Flicky Conversion)" (pitfall2a)     
2017-02-12 game: support "Pitfall II (not encrypted)" (pitfall2u)     
2017-02-12 game: support/decode "Vs. The Goonies (set E)" (goonies), thanks to contributor T. Busse!     
2017-02-12 game: support/decode "Mr. Do's Castle (set 1)" (docastle), thanks to contributor T. Busse!     
2017-02-12 game: support "Mr. Do's Castle (set 2)" (docastle2)     
2017-02-12 game: support "Mr. Do's Castle (older)" (docastleo)     
2017-02-12 game: support "Mr. Do vs. Unicorns" (douni)     
2017-02-11 game: support/decode "Depthcharge" (depthch), thanks to contributor T. Busse!     
2017-02-11 game: support "Depthcharge (older)" (depthcho)     
2017-02-11 game: support "Sub Hunter (Gremlin / Taito)" (subhunt)     
2017-02-11 game: support/decode "Cosmic Avenger" (cavenger), thanks to contributor T. Busse!     
2017-02-11 game: support/decode "Astro Blaster (German)" (astrobg), thanks to contributor T. Busse!     
2017-02-11 game: support "Astro Blaster (version 1)" (astrob1)     
2017-02-11 game: support "Astro Blaster (version 2a)" (astrob2a)     
2017-01-24 game: support/decode "Turtles" (turtles)     
2017-01-24 game: support "600" (600)     
2017-01-24 game: support "Turpin" (turpin)     
2017-01-24 game: support "Turpin (bootleg on Scramble hardware)" (turpins)     
2017-01-24 game: support/decode "Rally X (32k Ver.?)" (rallyx)     
2017-01-24 game: support "Rally X" (rallyxa)     
2017-01-24 game: support "Rally X (Midway)" (rallyxm)     
2017-01-24 game: support "Rally X (Model Racing bootleg)" (rallyxmr)     
2017-01-24 game: support "New Rally X" (nrallyx)     
2017-01-24 game: support "New Rally X (bootleg?)" (nrallyxb)     
2017-01-22 game: support/decode "Star Wars (set 1)" (starwars), thanks to contributor T. Busse!     
2017-01-22 game: support "Star Wars (set 2)" (starwars1)     
2017-01-22 game: support "Star Wars (set 3)" (starwarso)     
2017-01-22 game: support/decode "Road Fighter (set 1)" (roadf), thanks to contributor T. Busse!     
2017-01-22 game: support "Road Fighter (set 2)" (roadf2)     
2017-01-22 game: support "Road Fighter (set 3, conversion hack on Hyper Sports PCB)" (roadf3)     
2017-01-22 game: support/decode "The Empire Strikes Back" (esb), thanks to contributor T. Busse!     
2017-01-22 game: support/decode "Bosconian (new version)" (bosco), thanks to contributor T. Busse!     
2017-01-22 game: support "Bosconian (Midway, new version)" (boscomd)     
2017-01-22 game: support "Bosconian (Midway, old version)" (boscomdo)     
2017-01-22 game: support "Bosconian (old version)" (boscoo)     
2017-01-22 game: support "Bosconian (older version)" (boscoo2)     
2017-01-22 game: support/decode "Solomon's Key (US)" (solomon), thanks to contributor Japi!     
2017-01-22 game: support "Solomon no Kagi (Japan)" (solomonj), thanks to contributor Japi!     
2017-01-22 game: support/decode "Nibbler (rev 9)" (nibbler), thanks to contributor Japi!     
2017-01-22 game: support "Nibbler (rev 6)" (nibbler6), thanks to contributor Japi!     
2017-01-22 game: support "Nibbler (rev 8)" (nibbler8), thanks to contributor Japi!     
2017-01-22 game: support "Nibbler (rev 3)" (nibblerb), thanks to contributor Japi!     
2017-01-22 game: support "Nibbler (rev ?)" (nibblera), thanks to contributor Japi!     
2017-01-22 game: support "Nibbler (Olympia - rev 8)" (nibblero), thanks to contributor Japi!     
2017-01-22 game: support "Nibbler (Pioneer Balloon conversion)" (nibblerp), thanks to contributor Japi!     
2017-01-22 game: support/decode "Vs. Dr. Mario" (drmario), thanks to contributor Japi!     
2017-01-16 game: support "War of the Bugs or Monsterous Manouvers in a Mushroom Maze (US)" (warofbugu)     
2017-01-16 game: support/decode "War of the Bugs or Monsterous Manouvers in a Mushroom Maze" (warofbug)     
2017-01-16 game: support "Wizard of Wor (with German Language ROM)" (wow)     
2017-01-16 game: support/decode "Wizard of Wor" (wow)     
2017-01-16 game: support "Pirates (set 1)" (pirates) new location form hiscore.dat 2017-01-04     
2017-01-16 game: support "Truxton" (truxton) new location form hiscore.dat 2017-01-04     
2017-01-16 game: support "The Final Round (version L)" (froundl)     
2017-01-16 game: support "The Final Round (version M)" (fround)     
2017-01-16 game: support "Majestic Twelve - The Space Invaders Part IV (Japan)" (majest12j)     
2017-01-16 game: support "SWAT (315-5048)" (swat)     
2017-01-16 game: support "Vector Galaga" (vgalaga)     
2017-01-16 game: support "Galaga '99" (galaga99)     
2017-01-16 game: support "Killipede (Centipede Hack)" (killiped)     
2017-01-16 game: support "Pacipede (Centipede Hack)" (pacipede)     
2017-01-16 game: support "Vectipede (Centipede Hack)" (vectiped)     
2017-01-16 game: support "Vectorpede (Centipede Hack)" (vectrped)     
2017-01-16 game: support "Burgertime (Vector sim)" (vecbtime)     
2017-01-16 game: support "Galaxian (Bug sprites)" (buglaxn)     
2017-01-16 game: support "Mr. Do! (Dig Dug sprites)" (mrdigdo)     
2017-01-16 game: support "Donkey Kong (Atari 2600 graphics)" (kong2600)     
2017-01-16 game: support "Fighting Soccer (Joystick hack bootleg)" (fsoccerb)     
2017-01-16 game: support "Penta" (penta)     
2017-01-16 game: support "Pop Flamer (bootleg on Naughty Boy PCB)" (popflamen)     
2017-01-16 game: support "Pop Flamer (hack?)" (popflameb)     
2017-01-16 game: support "Pop Flamer (not protected)" (popflamea)     
2017-01-16 game: support/decode "Pop Flamer (protected)" (popflame)     
2017-01-16 game: support "Martial Champion (ver JAA)" (mtlchampj)     
2017-01-16 game: support "Super Cobra (Sega)" (scobrase)     
2017-01-16 game: support "Super Cobra (Stern Electronics)" (scobras)     
2017-01-16 game: support "Super Cobra (bootleg)" (scobrab)     
2017-01-16 game: support "Super Cobra" (scobra)     
2017-01-16 game: support/decode "Omega" (omega)     
2017-01-16 game: support/decode "Space Thunderbird" (spctbird)     
2017-01-16 game: support/decode "Side Trak" (sidetrac)     
2017-01-16 game: support "Street Fighter II: The World Warrior (USA 910318)" (sf2ud)     
2017-01-16 game: support "Red Baron" (redbaron)     
2017-01-16 game: support "Yellow Cab (Japan)" (yellowcbj)     
2017-01-16 game: support "Yellow Cab (bootleg)" (yellowcbb)     
2017-01-16 game: support "Vendetta (World, 2 Players, ver. ?)" (vendetta2pun) since mame 0.180     
2017-01-16 game: support "Vapor Trail - Hyper Offence Formation (US)" (vaportrau)     
2017-01-16 game: support "Teenage Mutant Ninja Turtles (US 4 Players, version H)" (tmntub) since mame 0.177     
2017-01-16 game: support "Teenage Mutant Ninja Turtles (Asia 4 Players, version ?)" (tmnta) since mame 0.179     
2017-01-16 game: support "Strider (USA, B-Board 90629B-3, buggy Street Fighter II conversion)" (strideruc) since mame 0.170     
2017-01-16 game: support "Sol Divide - The Sword Of Darkness (Korea)" (soldividk) since mame 0.180     
2017-01-16 game: support "Space Invaders (CV Version, smaller roms)" (sicv1) since mame 0.175     
2017-01-16 game: support "Same! Same! Same! (1P set, NEW VER! hack)" (samesamenh) since mame 0.181     
2017-01-16 game: support "Raiden (Korea, bootleg)" (raidenkb) since mame 0.181     
2017-01-16 game: support "Popeye (Japan, Sky Skipper hardware)" (popeyej) since mame 0.178     
2017-01-16 game: support "Pirates (set 2)" (piratesb) since mame 0.169     
2017-01-16 game: support "Pinguinos (Spanish bootleg on Pac-Man hardware)" (pinguinos) since mame 0.178     
2017-01-16 game: support "New Zero Team (V33 SYSTEM TYPE_B hardware, China?)" (nzeroteama) since mame 0.177     
2017-01-16 game: support "Mutant Warrior (Altered Beast - Datsu bootleg)" (mutantwarr) since mame 0.175     
2017-01-16 game: support "Ms. Pac-Man (bootleg, set 2)" (mspacmab) since mame 0.178     
2017-01-16 game: support "Ms. Pac-Man (bootleg, set 1)" (mspacmab)     
2017-01-16 game: support "Knock Out!! (bootleg, set 3)" (knockoutc) since mame 0.172     
2017-01-16 game: support "Knock Out!! (bootleg, set 2)" (knockoutb) since mame 0.169     
2017-01-16 game: support "Ghox (joystick)" (ghoxj)     
2017-01-16 game: support "Gemini Wing (bootleg)" (geminib) since mame 0.178     
2017-01-16 game: support "Gauntlet (Spanish, rev 15)" (gauntlets)     
2017-01-16 game: support "Gauntlet (rev 9)" (gauntletr9)     
2017-01-16 game: support "Gauntlet (rev 7)" (gauntletr7)     
2017-01-16 game: support "Gauntlet (rev 5)" (gauntletr5)     
2017-01-16 game: support "Gauntlet (rev 4)" (gauntletr4)     
2017-01-16 game: support "Gauntlet (2 Players, rev 6)" (gauntlet2p)     
2017-01-16 game: support "Devil Fish (Galaxian hardware, bootleg?)" (devilfsg)     
2017-01-16 game: support "UniWar S (bootleg)" (uniwarsa) since mame 0.179     
2017-01-16 game: support "Multi Wars (bootleg of UniWar S)" (mltiwars) since mame 0.181     
2017-01-16 game: support "Galaxian (bootleg, set 4)" (galaxianbl2) since mame 0.175     
2017-01-16 game: support "Escape from Mars (bootleg of Lunar Rescue)" (escmars) since mame 0.177     
2017-01-16 game: support "Elevator Action (4 pcb version, 1.1)" (elevator4) since mame 0.178     
2017-01-16 game: support "DonPachi (Japan)" (donpachij)     
2017-01-15 game: support "Cosmic Invaders (bootleg of Space Invaders) " (cosmicin) since mame 0.180     
2017-01-15 game: support "Phoenix (Amstar, set 2)" (phoenix2) since mame 0.178     
2017-01-15 game: support "Condor (S C Novar bootleg of Phoenix)" (conforn) since mame 0.178     
2017-01-15 game: support "Bubble Bobble: Lost Cave V1.2 (for Bobble Bobble PCB)" (boblcave) since mame 0.167     
2017-01-15 game: support "Bubble Bobble: Lost Cave V1.2" (bublcave) since mame 0.167     
2017-01-15 game: support "Bubble Bobble: Lost Cave V1.0" (bublcave10) since mame 0.167     
2017-01-15 game: support "Bubble Bobble: Lost Cave V1.1" (bublcave11) since mame 0.167     
2017-01-15 game: support "Super Bobble Bobble (bootleg, set 2)" (sboblbobla) since mame 0.155     
2017-01-15 game: support "Super Bobble Bobble (bootleg, set 3)" (sboblboblb) since mame 0.155     
2017-01-15 game: support "Dream Land / Super Dream Land (bootleg of Bubble Bobble)" (dland)     
2017-01-14 game: support "Bombjack Twin (prototype? with adult pictures, set 2)" (bjtwinpa) since mame 0.179     
2017-01-14 game: support "Air Gallet (older, Europe)" (agalleta) since mame 0.177     
2017-01-14 game: support "Air Gallet (older, Hong Kong)" (agalletah) since mame 0.177     
2017-01-14 game: support "Akuu Gallet (older, Japan)" (agalletaj) since mame 0.177     
2017-01-14 game: support "Air Gallet (older, Korea)" (agalletak) since mame 0.177     
2017-01-14 game: support "Air Gallet (older, Taiwan) " (agalletat) since mame 0.177     
2017-01-14 game: support "Air Gallet (older, USA)" (agalletau) since mame 0.177     
2017-01-14 game: support "1945k III (older, OPCX1 PCB)" (1945kiiio) since mame 0.173     
2017-01-14 game: support "1945k III (newer, OPCX1 PCB)" (1945kiiin) since mame 0.180     
2017-01-14 game: support "1943: The Battle of Midway Mark II (US)" (1943mii) since mame 0.175     
2017-01-14 game: support "The NewZealand Story (US, old version) (older PCB)" (tnzsuo)     
2017-01-14 game: support "The NewZealand Story (World, unknown version) (older PCB)" (tnzsoa) since mame 0.181     
2017-01-14 game: support "Hyper Olympic (bootleg, set 2)" (hyprolymba) renamed in mame 0.166     
2016-04-24 game: support/decode "Fighting Soccer" (fsoccer, ftsoccer)     
2016-04-24 game: support/decode "Touch Down Fever" (tdfever, tdfeverj, tdfever2)     
2016-04-24 game: support/decode "Psycho Soldier" (psychos, psychosj)     
2016-04-24 game: support/decode "Fighting Golf" (fitegolf, fitegolfu)     
2016-04-24 game: support/decode "T.N.K III" (tnk3)     
2016-04-23 game: support/decode "Alpha Mission 2" (alpham2)     
2016-04-22 game: support/decode "Armored Scrum Object" (aso), "Arian Mission" (arian), "Alpha Mission" (alphamis)     
2016-04-22 game: support/decode "Andro Dunos" (androdun)     
2015-12-10 game: support "Crouching Tiger Hidden Dragon 2003" (cthd2003 = 2001 bootleg)     
2015-12-10 game: support "Crouching Tiger Hidden Dragon 2003 Super Plus" (ct2k3sp, ct2k3sa = 2001 bootleg)     
2015-12-08 game: support "King of Fighters 2001" (kof2001, kof2001h)     
2015-12-03 game: support "King of Fighters 2000" (kof2000, kof2000n)     
2015-11-26 game: support "King of Fighters '99" (kof99, kof99e, kof99h, kof99k, kof99kp)     
2015-11-26 game: support "King of Fighters '98" (kof98, kof98a, kof98h, kof98k, kof98ka)     
2015-11-26 game: support "King of Fighters '97" (kof97, kof97h, kof97k, kof97oro, kof97pls)     
2015-11-25 game: support "King of Fighters '96" (kof96, kof96h)     
2015-11-23 game: support "King of Fighters '95" (kof95, kof95a, kof95h)     
2015-11-23 game: support "King of Fighters '94" (kof94)     
2015-11-23 game: support "Welltris" (welltris, welltrisj)     
2015-11-22 game: support "Power Spikes II" (pspikes2)     
2015-11-22 game: support "Power Spikes" (pspikes, spikes91, pspikesb, svolly91, spikes91b, pspikesc, pspikesk, pspikesu)     
2015-11-22 game: support "Hatris" (hatris, hatrisj) and improve it to save the last score     
2015-11-22 game: add "Tao Taido" (taotaido, taotaidoa, taotaido3) in hiscore.dat and support it     
2015-11-22 game: support "Pipe Dream" (pipedrm, pipedrmj, pipedrmu, pipedrmt)     
2015-11-22 game: support "F-1 Grand Prix Part II" (f1gp2)     
2015-11-20 game: support "F-1 Grand Prix" (f1gp) and improve hiscore.dat entry to save GP records     
2015-11-19 game: support "Lethal Crash Race" (crshrace, crshrace2)     
2015-11-19 game: support "Karate Blazers" (karatblz, karatblzu, karatblzj)     
2015-11-19 game: support "Turbo Force" (turbofrc)     
2015-11-19 game: support "Aero Fighters Special / Sonic Wings Limited" (aerofgts, sncwgltd)     
2015-11-18 game: support "Aero Fighters 3 / Sonic Wings 3" (sonicwi3)     
2015-11-18 game: support "Aero Fighters 2 / Sonic Wings 2" (sonicwi2)     
2015-11-17 game: support "Aero Fighters / Sonic Wings" (aerofgt, aerofgtb, aerofgtc, aerfboot, aerfboo2, sonicwi)     
2015-11-15 game: support "Shinobi" (shinobi, shinobl, shinobi1, shinobi2, shinobi3, shinobi4, shinobi5, shinobld, shinobls)     
2015-11-15 game: support "Shark Attack" (sharkatt)     
2015-11-15 game: support "Vasara 2" (vasara2, vasara2a) => unable to identify kanji, only katakana... help...     
2015-11-15 game: support "Vasara" (vasara) => unable to identify kanji, only katakana... help...     
2015-11-11 game: support "Xevious 3D/G" (xevi3dg)     
2015-11-11 game: support "Xevious" (xevious, sxevious, sxeviousj, xevios, xeviousa, battles, xeviousb, xeviousc)     
2015-10-04 game: support "Strider" (strider, striderj, stridrjr, striderua)     
2015-10-04 game: support "Wyvern F0" (wyvernf0)     
2015-10-04 game: support "Ghouls'n Ghosts" (ghouls, ghoulsu, daimakair, daimakai)     
2015-10-03 game: support "Golden Axe" (goldnaxe, goldnaxa, goldnaxej, goldnaxeu, goldnaxeb2, goldnaxeb1, goldnaxe1, goldnaxe2, goldnaxe3)     
2015-09-26 game: support "Side Arms" (sidearms, sidearmsr, sidearmsur1, sidearmsu, sidearmsj)     
2015-09-26 game: support "Zero Team" (nzeroteam, zerotm2k, zeroteam, zeroteamd, zeroteamc, zeroteams, zeroteamsr, zeroteama, zeroteamb)     
2015-09-26 game: support "Dragon World II" (drgw2, dw2v100x, drgw2hk)     
2015-09-25 game: support "Ace Attack" from native nvram (aceattac, aceattaca)     
2015-09-25 game: support "A.B. Cop" from native nvram (abcop, abcopj)     
2015-09-24 game: support "Cyvern" from native nvram (cyvern, cyvernj)     
2015-09-21 game: add "Crypt Killer" in hiscore.dat and support it (cryptklr). This is my first tentative to add a new game inside hiscore.dat :)     
2015-09-20 game: support "Twin Hawk" (twinhawk, twinhawku, daisenpu)     
2015-09-20 game: support "Legion" (legiono, legion, legionj, legionjb)     
2015-09-20 game: support "Chopper" (chopper, choppera, chopperb, legofair)     
2015-09-20 game: support "Change Air Blade" (cairblad)     
2015-09-20 game: support "Dyger" (dyger, dygera)     
2015-09-19 game: support "MX5000" (mx5000, flkatck, flkatcka)     
2015-09-19 game: support "Fire Battle" (firebatl)     
2015-09-16 game: support "Final Star Force" (fstarfrc, fstarfrcj)     
2015-09-15 game: support "Nebulas Ray" (nebulray, nebulrayj)     
2015-09-15 game: support "Operation Thunderbolt" (othunder, othunderu, othunderj, othunderuo)     
2015-09-14 game: support "Operation Wolf" (opwolf, opwolfb, opwolfu, opwolfa, opwolfj)     
2015-09-13 game: support "Dungeons & Dragons: Tower of Doom" (ddtod, ddtodu, ddtodhr1, ddtodjr1, ddtodj, ddtodur1, ddtodjr2, ddtodd, ddtoda, ddtodar1, ddtodr1, ddtodhr2, ddtodh)     
2015-09-13 game: support "Dungeons & Dragons: Shadow over Mystara" (ddsom, ddsoma, ddsomar1, ddsomr1, ddsomjr1, ddsomj, ddsomur1, ddsomu, ddsomb, ddsomr3, ddsomr2, ddsomud, ddsomh)     
2015-09-13 game: support "After Burner", "After Burner II" (aburner, aburner2, aburner2g)     
2015-09-13 game: support "Armored Warrior" (armwar, armwaru, armwara, armwarar1, armwar1d, armwarr1, armwaru1, pgearr1, pgear)     
2015-09-13 game: support "Dragon Spirit" (dspirit, dspirit1, dspirit2, dspirito, dspirita)     
2015-09-10 game(s): support 'tigeroad', 'tigeroadu', 'tigeroadb', 'toramich'     
2015-09-01 game(s): support 'raidendx', 'raidendxu', 'raidendxk', 'raidendxj', 'raidendxa2',     
                            'raidendxa1', 'raidendxnl', 'raidendxg', 'raidendxch'     
2015-09-01 game(s): support 'r2dx_v33_r2', 'r2dx_v33'     
2015-09-01 game(s): support 'raiden2', 'raiden2dx', 'raiden2nl', 'raiden2hk', 'raiden2i', 'raiden2j',     
                            'raiden2u', 'raiden2sw', 'raiden2f', 'raiden2g', 'raiden2ea', 'raiden2e', 'raiden2eua', 'raiden2eu'     
2015-09-01 game(s): support 'kamikaze', 'kosmokil', 'astinvad' [thanks to Piergiorgio G.]     
2015-08-30 game(s): support 'scramce', 'spaceatt2k', 'spaceattbp', 'spf2tu', 'xmen2pu' [new clones from hiscore.dat 20150701]     
2015-08-30 game(s): support 'paradise', 'paradisea', 'paradisee' [new format and new clones from hiscore.dat 20150701]     
2015-08-30 game(s): support 'berzerkf', 'berzerks', 'bgareggabla', 'blswhstla', 'btlkroadk', 'contrae', 'madalienb' [new clones from hiscore.dat 20150701]     
2015-08-30 game(s): support 'vigilanta', 'vigilantbl', 'vigilantc', 'vigilantd', 'vigilantg', 'vigilanto' [new clones from hiscore.dat 20150701]     
2015-08-30 game(s): support 'headon2' [modified by hiscore.dat 20150131, from hi2txt report]     
2015-05-26 game(s): support 'dondokod', 'dondokodu', 'dondokodj'     
2015-05-26 game(s): support 'piratpet'     
2015-05-26 game(s): support 'gunfront', 'gunfrontj'     
2015-05-22 game(s): support 'liquidk', 'liquidku', 'mizubaku'     
2015-05-22 game(s): support 'metalb', 'metalbj'     
2015-05-22 game(s): support 'ssi', 'ssia', 'majest12'     
2015-05-21 game(s): support 'spcinv95', 'spcinv95u', 'akkanvdr'     
2015-05-21 game(s): support 'bublbob2', 'bubsymphj', 'bubsymphu', 'bubsymphe', 'bubsymphb'     
2015-05-18 game(s): support 'gseeker', 'gseekerj', 'gseekeru'     
2015-05-12 game(s): support 'rayforce', 'rayforcej', 'gunlock'     
2015-05-12 game(s): support 'ktiger2', 'tcobra2', 'tcobra2u'     
2015-05-11 game(s): support 'nemesis', 'nemesisuk', 'truxton' [modified by hiscore.dat 20150131, from hi2txt report]     
2015-05-11 game(s): support 'kangaroo', 'kangarooa', 'kangaroob' [modified by hiscore.dat 20150131, from hi2txt report]     
2015-05-10 game(s): support 'gallop', 'grindstm', 'grindstma' [modified by hiscore.dat 20150131, from hi2txt report]     
2015-05-09 game(s): support 'fixeight', 'futaribl' [modified by hiscore.dat 20150131, from hi2txt report]     
2015-05-08 game(s): support 'arabfgt', 'argus', 'bchopper', 'mrheli, 'dariusj', 'deathsml', 'arkanoidj' [modified by hiscore.dat 20150131, from hi2txt report]     
2015-05-05 game(s): support 'appoooh' [modified by hiscore.dat 20150131, from hi2txt report]     
2015-05-05 clone(s): support 'zerotimed', 'vigilantb', 'vendetta2peba', 'tmhtb', 'tazzmang2',     
  'solrwarr', 'skysharka', 'simpsons2p3', 'sf2ebbl2', 'sf2ebbl3', 'sboblbobl', 'quaak',     
  'punchouta', 'plgirls2b', 'phoenixdal', 'pleiadsi', 'pleiadss', 'pengojpm', 'pengopac',     
  'pacmaniao', 'mspacmanbcc', 'mspacmanbgd', 'pacmanjpm', 'mariobl', 'joust2r1', 'invadersem',     
  'hexaa', 'gunsmokeb', 'galmonst', 'futariblj', 'froggeram', 'fixeighta', 'fixeightat',     
  'fixeighth', 'fixeightht', 'fixeightj', 'fixeightjt', 'fixeightk', 'fixeightkt', 'fixeightt     ',
  'fixeighttw', 'fixeighttwt', 'fixeightu', 'fixeightut', 'firebarr', 'dariusu', 'ckongdks',     
  'circusc4', 'centiped3', 'brkblast', 'blktigera', 'blktigerb3', 'avefenixrf', 'arkretrnu',     
  'arkanoidja', 'arkanoidjbl', 'arkanoidjbl2', '19xxar1' [added by hiscore.dat 20150131]     
2014-10-08 game(s): support 'fhawk', 'fhawkj'     
2014-10-08 game(s): support 'palamed'     
2014-10-08 game(s): support 'plgirls2'     
2014-10-04 game(s): support 'tnzs', 'tnzsb', 'tnzsj', 'tnzsjn', 'tnzsjo', 'tnzso', 'tnzsop', 'tnzs2'     
2014-10-04 game(s): support 'gemini'     
2014-10-04 game(s): support 'thief'     
2014-10-04 game(s): support 'scontra', 'scontraj'     
2014-10-04 game(s): support 'blswhstl', 'detatwin'     
2014-10-04 game(s): support 'chukatai', 'chukataij', 'chukataiu'     
2014-10-04 game(s): support 'drtoppel', 'drtoppelj', 'drtoppelu'     
2014-10-04 game(s): support 'insectx', 'insectxj'     
2014-10-04 game(s): support 'plumppop'     
2014-10-04 game(s): support 'topspeed', 'topspeedu', 'fullthrl'     
2014-10-04 game(s): support 'liblrabl'     
2014-10-04 game(s): support 'toypop'     
2014-09-28 game(s): support 'tumblep', 'tumblepba', 'tumblepj', 'tumbleb', 'tumbleb2'     
2014-09-28 game(s): support 'tutankhm', 'tutankhms'     
2014-09-25 game(s): support 'hpuncher'     
2014-09-24 game(s): support 'vulcan', 'vulcana', 'vulcanb', 'gradius2', 'gradius2a', 'gradius2b'     
2014-09-24 game(s): support 'ultraman'     
2014-09-24 game(s): support 'vulgus', 'vulgusj', 'vulgusa'     
2014-09-24 game(s): support 'warpwarp', 'warpwarpr', 'warpwarpr2'     
2014-09-24 game(s): support 'hotchase'     
2014-09-24 game(s): support 'rugrats', 'wiping'     
2014-09-24 game(s): support 'scion', 'scionc'     
2014-09-23 game(s): support 'gdarius', 'gdarius2', 'gdariusb'     
2014-09-23 game(s): support 'darius2', 'darius2d', 'darius2do', 'sagaia'     
2014-09-23 game(s): support 'stinger', 'stinger2'     
2014-09-23 game(s): support 'wiz', 'wizt', 'wizta'     
2014-09-23 game(s): support 'p47aces'     
2014-09-23 game(s): support 'p47', 'p47j', 'p47je'     
2014-09-23 game(s): support 'stdragon', 'stdragona'     
2014-09-23 game(s): support 'acrobatm'     
2014-09-19 game(s): support 'darius', 'dariuse', 'dariusj', 'dariuso'     
2014-09-18 game(s): support 'mmatrix', 'mmatrixj', 'mmatrixd'     
2014-09-18 game(s): support 'wardner', 'wardnerj', 'pyros'     
2014-09-18 game(s): support 'tigerh', 'tigerhj', 'tigerhb1', 'tigerhb2', 'tigerhb3'     
2014-09-17 game(s): support 'rtypeleo', 'rtypeleoj'     
2014-09-17 game(s): support 'nspirit', 'nspiritj'     
2014-09-17 game(s): support 'lethalth', 'thndblst'     
2014-09-17 game(s): support 'inthunt', 'inthuntu', 'kaiteids'     
2014-09-16 game(s): support 'gunforce', 'gunforcej', 'gunforceu'     
2014-09-16 game(s): support 'gunforc2', 'geostorm'     
2014-09-15 game(s): support 'dbreed', 'dbreedm72'     
2014-09-13 game(s): support 'demoneye'     
2014-09-13 game(s): support 'cosmccop', 'gallop'     
2014-09-11 game(s): support 'battroad'     
2014-09-11 game(s): support 'bchopper', 'mrheli'     
2014-09-11 game(s): support 'airass'     
2014-09-11 game(s): support 'agallet', 'agalleth', 'agalletk', 'agallett', 'agalletu', 'agalletj'     
2014-09-10 game(s): support 'dimahoo', 'dimahoou', 'dimahoud', 'gmahou'     
2014-09-10 game(s): support 'repulse', '99lstwar', '99lstwara', '99lstwra', '99lstwak', '99lstwark', 'sonofphx'     
2014-09-10 game(s): support 'pprobe'     
2014-09-10 game(s): support 'gyrodine', 'gyrodinet', 'buzzard'     
2014-09-09 game(s): support 'mushitam', 'mushitama'     
2014-09-05 game(s): support 'uopoko'     
2014-09-01 align 'espgal', 'nitd' to hiscore.dat 2014-08-22, fixing issue reported with hi2txt@1.1     
2014-09-01 align 'mhavoc', 'ket', 'dazzler', 'vfive' to hiscore.dat 2014-08-22, fixing issue reported with hi2txt@1.1     
2014-08-31 support 'guwange', 'guwanges' games     
             including full name decoding as hiragana, as well as the romanji transliteration using the Hepburn romanization system     
             note: it was a great pleasure to learn sokuon, youon, dakuten, handakuten, Hepburn romanization and the Iroha poem :)     
2014-08-29 support 'feversos', 'dfeveron' games     
2014-08-27 support 'donpachi', 'donpachj', 'donpachihk', 'donpachikr' games     
2014-08-25 support 'gnbarich' game     
2014-08-24 support 'tgm2', 'tgm2p' games     
2014-08-20 support 'soldivid' game     
2014-08-20 support 'sbomber', 'sbombera' games     
2014-08-19 support 's1945iii' game     
2014-08-18 support 'gunbird2' game     
2014-08-12 support 'tengai', 'tengaij' games     
2014-08-12 support 'samuraia', 'sngkace' games     
2014-08-12 support 's1945', 's1945a', 's1945bl', 's1945j', 's1945jn', 's1945k' games     
2014-08-11 support 'gunbird', 'gunbirdj', 'gunbirdk' games     
2014-08-11 support 'btlkroad', 'btlkrodj' games     
2014-08-11 support 'zerowing', 'zerowing1', 'zerowingw' games     
2014-08-11 support 'truxton' game     
2014-08-10 support 'rallybik' game     
2014-08-10 support 'samesame', 'samesame2' games     
2014-08-09 support 'hellfire', 'hellfire1', 'hellfire3', 'hellfire1a', 'hellfire2', 'hellfire2a' games     
2014-08-09 support 'fireshrk', 'fireshrka', 'fireshrkd', 'fireshrkdh' games     
2014-08-09 support 'demonwld', 'demonwld1', 'demonwld2', 'demonwld3', 'demonwld4' games     
2014-08-05 support 'truxton2', 'tatsujn2' games     
2014-08-05 support 'tekipaki' game     
2014-08-05 support 'pipibibs', 'pipibibsbl', 'pipibibsa', 'pipibibsp', 'whoopee' games     
2014-08-05 support 'pang', 'pangb', 'pompingw', 'bbros', 'pangbold', 'pangba', 'pangb2' games [thanks William L.!]     
2014-08-04 support 'sstriker', 'sstrikera', 'mahoudai' games     
2014-08-04 support 'kingdmgp', 'shippumd' games     
2014-08-03 support 'kbash', 'kbash2' games     
2014-08-03 support 'ghox', 'ghoxa' games     
2014-08-03 support 'fixeight', 'fixeightbl' games     
2014-08-03 support 'dogyuun', 'dogyuuna', 'dogyuunt' games     
2014-08-03 support 'bgareggabl' game     
2014-08-01 support 'bgaregga', 'bgareggahk', 'bgareggatw', 'bgaregganv', 'bgareggacn', 'bgareggat2' games     
2014-07-29 support 'bbakraid', 'bbakraidj', 'bbakraidja' games     
2014-07-28 support 'batrider', 'batriderc', 'batriderja', 'batriderk', 'batrideru', 'batriderj', 'batridert' games     
2014-07-27 support 'spcforce', 'meteor', 'spcforc2' games     
2014-07-27 support 'vaportra', 'vaportru', 'kuhga', 'vaportra3' games     
2014-07-27 support 'msisaac' game     
2014-07-27 support 'jin' game     
2014-07-27 support 'mrflea' game     
2014-07-27 support 'vangrd2' game     
2014-07-27 support 'vimana', 'vimanan', 'vimana1', 'vimanaj' games     
2014-07-27 support 'vfive', 'grindstm', 'grindstma' games     
2014-07-25 support 'xexex', 'xexexa', 'xexexj' games     
2014-07-25 support 'xybots' game     
2014-07-25 support 'jackrabt', 'jackrabt2', 'jackrabts' games     
2014-07-24 support 'razmataz' game     
2014-07-24 support 'spiders', 'spiders2', 'spiders3' games     
2014-07-24 support 'zerozone' game     
2014-07-24 support 'shangha3', 'shangha3u', 'shangha3j' games     
2014-07-24 support 'megaphx' game     
2014-07-24 support 'progear', 'progeara', 'progearj', 'progearjbl', 'progearjd', 'progearud' games     
2014-07-23 support 'mmpork' game     
2014-07-23 support 'ibara', 'ibarablk', 'ibarablka' games     
2014-07-22 support 'pinkswts', 'pinkswtsa', 'pinkswtsb', 'pinkswtsx' games     
2014-07-21 support 'deathsml', 'dsmbl' games     
2014-07-21 support 'ket', 'keta', 'ketb' games     
2014-07-20 support 'ddpdfk', 'ddpdfk10' games     
2014-07-20 support 'ddpdoj', 'ddpdoja' 'ddpdojb', 'ddpdojblk', 'ddpdojblka' games     
2014-07-19 support 'futari10', 'futari15' 'futari15a' games     
2014-07-19 support 'mushisam', 'mushisama', 'mushisamb' games     
2014-07-19 support 'espgal2' game     
2014-07-19 support 'espgal' game     
2014-07-17 support 'futaribl' game     
(not recorded)     
