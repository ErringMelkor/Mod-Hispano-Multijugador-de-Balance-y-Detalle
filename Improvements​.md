Improvements​

Bugfixes​

    [GDFIX] Fixed an issue where various left-wing ideologies would not properly weight Serfdom in political party calculations (thank you CaesarVincens for the suggestion)
    [GDFIX] The Fascist leader ideology now requires Political Agitation instead of Mass Propaganda, to bring it in line with the requirements for the Fascist Movement (thank you CaelReader for the suggestion)
    [GDFIX] Fixed an issue where Moderniser characters could not support Moderniser movements (thank you to CaesarVincens for the suggestion)
    [GDFIX] Juan Silvano Godoi and Rafael Barrett will now correctly spawn for Paraguay (thank you to CaesarVincens for the suggestion)
    [GDFIX] Fixed an issue where releasing Russia or Belarus would give the Devout ideology redundant Moralist ideologies (thank you to CaesarVincens for the suggestion)
    [GDFIX] Fixed an issue where power bloc join calculations used an incorrect scope for assessing identity/principle scores (thank you to CaesarVincens for the suggestion)
    [GDFIX] Corrected Asa Thurston's culture to Yankee (thank you both Dryhad and CaesarVincens)
    [GDFIX] Fixed several issues with subject flags for United Tribes, Tibet, Jamaica, Bretagne, and Brunei (thank you to CaesarVincens for the suggestion)
    [GDFIX] Corrected localisation for the has_commander_order trigger to display the relevant order (thank you to CaesarVincens for the suggestion)
    [GDFIX] Fixed some japanese loc formatting to allow showing data (thanks maruta for the suggestion)
    [GDFIX] Fixed errors in the names of Pakubuwana IX and George Strickland Kingston (thank you to CaesarVincens for the suggestion)
    Fixed an Out of Sync from Scripted additional Radicalism for cultural movements
    Austrian Upper Silesian Poles have been properly instructed to go back to Austria when they lose their secession war (Fixed so Secession wars keep track of what provinces belonged to who for split states)
    Fixed an issue that caused Korean clothing to be overridden by Manchu and Han clothes
    Made Armies stationed at an HQ also be able to defend Fronts in the HQ's strategic region and made them visible in all relevant contexts like in the calculation for front advantage
    Fixed so we use all primary cultures shared heritage to calculate acceptance on cultures
    Pops part of a Secession are now redistributed when state is split back to original owners
    Buildings part of a seceding state are now given back to the original owners
    Fixed a crash caused by dead pops in political movements
    Fixed stuttering that occurred with too many countries existing on the map
    Fixed an issue where the Koreanic language trait group was unlocalised
    Fixed an issue where country-specific traits for the Petit-Bourgeoisie would be overridden by generic ones
    Fixed an issue where momentum set in history would not correctly impact historical elections, resulting in issues such as the Whigs incorrectly being calculated as having won the 1836 elections
    Fixed an issue where Serbia would gain Dynastic Loyalty from improved relations with the Ottomans, rather than the reverse
    Fixed improve/damage relations description being broken when the progress is exactly 0% due to opposing actions
    Gave the Labour Movement a stance on Labour Associations
    Fixed a bug that blocked acquiring the "David Slays Goliath" achievement as a Yugoslavia formed from Montenegro
    The "Prussia of the Balkans" achievement now accounts for the North German Confederation
    The Dual Monarchy will no longer annex a player Croatia upon formation
    Changed French movement stances to match those of their corresponding character ideologies
    Fixed an issue where the Positivist Movement would appear too early in the game, possibly causing a no-win scenario during the Springtime of the Peoples
    Fixed a bug in cross-country secessions where secondary targets of the uprising would get a 'Crush Secession' wargoal targeting the wrong country
    When 'inheriting' radicals from conquered states, this is now correctly shown as the reason for those radicals being added to your total amount
    Removed top hat from Dordije Petrović-Njegos
    The has_potential_resource and num_potential_resources triggers now work correctly for buildings that use arable land. This should fix some issues the AI had with establishing agricultural companies which use these trigger for their construction targets.
    Fixed and removed a jarring jumping around of the State Trait map markers in the Production map mode when you hover any Market
    Removed doubled Activism modifier from Springtime of the Peoples on Cultural Minority movements
    Fixed an issue where the Megali Idea Journal Entry could disappear before a completion criteria was selected
    The Reunify China Journal Entry will no longer appear for non-Chinese countries
    Fixed an issue where the Liberal Movement had incorrect stances on land reform
    Fixed a typo in a loc reference that resulted in company_category_bureaucrat_owned not showing its correct text
    Fixed an issue that interfered with the calculation of liberty desire from pro- and anti-overlord lobbies
    Alaska can no longer be sold more than once
    Fixed a bug on pop details panel showing two religion icons
    Removed one of the duplicated goods icons in the Pop Need fancy tooltip
    Owning all of Upper Silesia is no longer a requirement to form Czechoslovakia
    Corrected the country flavour text for Ogaden, Anuak, Borana, Omo, Hadiya, Wolaita, Qwara
    Fixed Hadiya's market using a placeholder
    Lobbies can no longer request diplomatic plays against revolutionary or secessionist countries
    Fixed an issue where the Great Eastern Crisis journal entry was visible to those who did not own National Awakening
    Fixed an issue that could cause subjects of the United Principalities to receive Bessarabia, rather than the United Principalities themselves
    Fixed Missing localization for RULER_TITLE_PREMIER
    Fixed an issue that could result in Orleanist monarchs for France not having the correct ideology (Voice of the People)
    Fixed an issue where "The Feminine Order of \[State\]" would incorrectly evaluate its trigger
    Fixed an issue where some battles would have just a loc key as their name
    Fixed a typo in defines which affected USE_NATIONALIZED_ECONOMY_OF_SCALE_PENALTY
    Fixed an issue where certain ideologies referred to non-existent laws in their IG leader chances
    Fixed a bug that could occasionally cause Maximilian von Habsburg to replace Franz Josef
