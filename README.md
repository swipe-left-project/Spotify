# Decoding Biases in AI: Final Porject

## Introduction

On June 5th, 2020, Republic Records, an entity within Universal Music Records, announced that they would “remove 'urban' from the label’s verbiage in describing departments, employee titles and music genres” (Aswad 2020). This announcement came in the midst of a nation-wide conversation around systemic racism in the United States after the death of George Floyd, Ahmaud Arbery and Breonna Tyler : #TheShowMustBePaused and Blackout Tuesday movements notably demanded that the music industry take accountability for its disparate treatment of Black artists, by “protecting and empowering the black communities that have made them disproportionately wealthy in ways that are measurable and transparent” (idem). Republic Records was the first of many actors within the American music ecosystem to adopt such a measure, and was notably followed by the National Academy for Recording Arts and Sciences. This organisation, in charge of the Grammy Awards, decided to undertake a similar change and substitute the category “Best Urban Contemporary Album '' for “Best Progressive R&B Album” (Lewis 2020). This change was presented as a way to “appropriately categorize and describe this subgenre” and ultimately use “a more accurate definition to describe the merit or characteristics of music compositions or performances themselves within the genre of R & B (idem). 
\
\
Such a conversation found some echo in France, as the French streaming platform Deezer decided to follow suit. Deezer’s justification was built on a rationale similar to that of the Grammys: they saw the term 'urban' as an outdated label that lumped together Black artists, regardless of their music genres (Fanen 2020). However, as opposed to the United States, this decision was not universal in France : most actors still use the term, including record labels and Spotify France. Spotify France has notably argued that this conversation around the “urban” term is a mere “anglo-saxon debate” which is not relevant to the French scene, as the “urban” label adequately and precisely refers to the “music of the youth in urban areas” (Cachin 2020). 
\
\
This contradiction between Deezer and Spotify France reflects the intrinsic difficulty to categorize and classify music. Musical genres are categories that are ever-evolving, reassessed and redefined, as artists innovate and experiment through genre-bending by mixing features associated with a specific genre, with features associated with another. The debate in France is focused on the category “pop urbaine” which is used to refer to hip hop, r&b, dancehall, afrotrap and ragga (Lemaître 2020). Some argue that pop urbaine is a relevant label which refers to a musical melting pot incorporating diasporic sonorities (from North Africa and sub-Saharan Africa), the French local musical culture, and the US art form of hip hop (Cachin 2020). Others, however, see this term as a stigmatizing abstract label which far from defining an aesthetic, exemplifies a disparate treatment between aesthetics associated with artists of color and aesthetics more associated with white artists (Fanen 2020).  In other words, while advocates see this term as a legitimate and specific music category, its opponents see this genre as an outdated catch-all term which reflects a lack of understanding of the evolution of the musical scene in France among young artists of color. 
\
\
Our research aims at contributing to this debate by interrogating the implications of the use of the label “urban” on Spotify France, and on its recommendation algorithm. Our findings show that the use of such broad catch-all categories leads to a heightened competition between artists, making it harder for niche and independent artists to be recommended by algorithm to the average user. This dynamic sets the pop urbaine genre apart from more specific genres in France, but also from countries in which Spotify has attempted to develop a more specific, comprehensive and fine grained understanding of the local music scene. Ultimately, this phenomenon results in the promotion of a select few well-established artists, and impedes Spotify’s mission to enable the listener to discover new artists. More substantively, specific and precise labelling is more conducive to the emergence and discovery of new, independent and nicher artists, and enables a proper understanding and account of the evolution of musical phenomena among young artists of color.


## Context

## Literature Review

## Methdology

![Methodology Flowchart](/../main/spotify@1.5x.png)

### Playlists considered: Pop Urbaine, Who We Be, GrandHit

Since the starting point of our project was the broad genre of Pop Urbaine, we considered the Spotify created Pop Urbaine playlist as our primary dataset, which claims to include “all pop urbaine and afropop hits”. To allow a comparison between two similar playlists, we included Who We Be, the UK’s biggest “Hip-Hop, Afrobeats, Dancehall and RnB playlist”.  Since we wanted to explore the intersection between hip hop and French music, the comparison with Who We Be allowed us to study this across language and geographical region. However, these two playlists did not account for variances that might arise from English music in Spotify being better categorised. This is why we also included GrandHit, a playlist that contains the 50 most popular French hits of the moment. By using GrandHit as a comparison with Pop Urbaine, we were able to clarify whether the issue lay with categorisation of French music or specifically Pop Urbaine. 

### Process followed

We have represented our methodology in the flowchart above and  will explain it here briefly for further clarification. To collect the data we either used the Spotipy API to generate dataframes of playlists or used the website OrganizeYourMusic to generate tables that we formatted into excel sheets to later import into our notebook. Most of our analysis was done using Python and the Pandas library, and some of the data visualisation was done using Data Wrapper.  We decided to analyse three types of datasets from these playlists. First, we looked at the frequency of artists within playlists. Second, we looked at the frequency of genres and subgenres within the playlists. Finally, we considered the frequency of artists and their popularity from the radios of random artists associated with the three main playlists. These steps are better explained in the notebook, especially with regards to the code used and the specific dataset referred to. The logic underlying our analysis was counting and creating visualisations to show frequency and variance. 

## Analysis

All of our analysis is conducted in the following notebook: [Spotify Data Analysis](https://colab.research.google.com/drive/1w99D_v5jLEBoDnfZvAtqSLsCKjXunA2l?usp=sharing) \
The link above gives you the ability to comment on the notebook. The datasheets required to run the code have also been uploaded to this respository.

## Discussion

## Conclusion
