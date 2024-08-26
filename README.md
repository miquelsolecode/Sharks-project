# Sharks-project

**INTRODUCTION**: Sharks are often sensationalized as dangerous predators in the media, but it's essential to recognize that fatal encounters with humans are relatively rare. Despite the extensive human presence in the ocean, sharks do not actively hunt humans as their natural prey.
The portrayal of sharks as relentless attackers in the media may lead to misconceptions about their behavior towards humans. While there have been recorded shark attacks, it's crucial to remember that these incidents are relatively rare considering the vast number of people in the ocean.
Looking for external factors, we hypothesized that the moon phases and it’s tides shift have an effect in shark behaviour or agressiveness, hoping for a reasonable conclusion.
DATA CLEANING AND PREPARATION:
We started this part of the process by retrieving the columns that weren’t relevant to our hypothesis, stripping spaces from the important variables, and rewritting some of them to follow the same nomenclature. We also organized in groups some categories that had too many options, like the type of attack, which had so many words for describing the same type of attacks. We also applied this method to groups/rename some of the localization variables, since lots of them were written in diferent ways but representin the same geological area.
We ended the data wrangling by removing all the unnecessary NaNs, deleting duplicates, and convertint all the information to lowercase. And when all of it was done we merged the original dataframe with a column with the moonphase data based on the time range in the preexisting data set.
With this new dataframe, we sorted the phases following their logical order, and we created a bar plot with the incidents that took place in each moon phase.THEORY-
SPECIFIC ANALYSIS
HYPOTHESIS 1: Shark agressiveness and beligerance is motivated/caused by the moon phases.
The results shown by our plots are inconclusive, with not enough data to suport our initial hypothesis; but we found interesting that the period in which there were less shark attacks was in the last moon clycle. We also confirmed that most of the attacks, no matter in which phase of the moon, were unprovoked.
