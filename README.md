# dpbe_l2_pre_registration

## Study Information

### Double Phonemic Boundary Effect in Bilinguals: a Replication Study with L2 Spanish Learners


### Description (optional)


Several authors have demonstrated the double phonemic boundary effect in bilingual population, providing strong evidence to support the hypothesis of a language-specific phonemic system in bilingual mind. Therefore, the aim of this study is to extend prior findings to a new population of Heritage L2 Spanish learners and English native L2 Spanish learners.





### Hypotheses 

### Hipothesis 1
Bilinguals shift perception across language context by switching between language-specific phonetic systems. Non-directional hypothesis. There is a relationship between the existence of two separate phonetic systems and the speaker shift perception of the sounds.

### Hipothesis 2
Bilinguals identification of the VOT stimuli varies depending on the language context. Non-directional hypothesis. There is a relationship between the language context and the  identification of the VOT stimuli by  bilinguals.

### Hipothesis 3
Proficiency have an effect in the voicing identification boundaries between English and Spanish. Directional hypothesis. There is a positive relation between proficiency and the identificacion of voicing boundarie.



## Design Plan

### Study type (required)

**Please check one of the following statements**

- Experiment - A researcher randomly assigns treatments to study subjects, this includes field or lab experiments. This is also known as an intervention experiment and includes randomized controlled trials.





### Blinding (required)

**Blinding describes who is aware of the experimental manipulations within a study. Mark all that apply.**

- No blinding is involved in this study.
- For studies that involve human subjects, they will not know the treatment group to which they have been assigned.
- Personnel who interact directly with the study subjects (either human or non-human subjects) will not be aware of the assigned treatments. (Commonly known as “double blind”)
- Personnel who analyze the data collected from the study are not aware of the treatment applied to any given group.





### Is there any additional blinding in this study? (optional)

**Add information here**



### Study design (required)


The experiment is a two-alternative forced choice administered in two sessions with at least 24 hours between sessions. There will be one group of English second language (L2) learners of Spanish with different L2 proficiency levels. Proficiency level will be measured through vocabulary size, using a computerized version of the LEXTale test on Psychopy, and it will be considered a continuous variable. VOT will also be a continuous variable, ranging from -60ms to 60ms in 10ms intervals, including pre-voiced, short-lag, and long-lag VOTs. 

The study has a within-subject design, all participants will complete the same tasks in both modes (English and Spanish). Mode will be counterbalanced, half of the participants will perform the first session in English and the other half in Spanish.


### Randomization (optional)

Participants will be randomly assigned to start with the Spanish  or the English version of the experiment.



## Sampling Plan

### Existing Data (required)

- Registration prior to creation of data 

Pre-registration is occurring before data collection for the intended research. No previous existing data will be analyzed. This research will be confirmatory. The studies taken as reference are discussed right below.

Gonzales and Lotto (2013) cued their early Spanish-English bilinguals perceptually and conceptually in a forced-choice task in which participants had to select whether the pseudo-word containing a sound from the /b/ or /p/ continuum they were hearing was Spanish or English. Gonzales et al. (2019) cued their Spanish-English and French-English bilingual participants only conceptually. In both studies, findings suggest that participants adjusted their phonemic identification boundary according to the language context. Casillas and Simonet (2018) expanded the population by adding beginner and proficient L2 speakers. These participants were cued perceptually. They found that late bilingual speakers also show evidence of the double phonemic boundary effect, although this effect was more pronounced in more advanced late bilingual speakers.



### Sample size (required)

This study aims at replicating the results found in those three investigations, and to collect data for a condition not tested yet – when speakers are only conceptually cued. In order to do so, new data will be collected following the same procedure as in those studies from an adult L2 population on the east coast of the U.S. The population will be mostly college-aged, and they will participate as part of the grade for their Spanish courses (both language and content), or voluntarily. The goal is to get around 30 participants for each group: beginner and intermediate learners of L2 Spanish, and early English-Spanish bilinguals. Their proficiency will be assessed through the Bilingual Language Profile (BLP) questionnaire (Birdsong, Gertken, & Amengual, 2012). Special attention will be paid to the language history (range [120, 120]) and the proficiency (range [24, 24]) modules. For the early bilinguals, a score closer to 0 indicates balanced bilingualism and such values are what we are looking for for this group of participants.

### Data collection procedures (required)


Data collection should last about two weeks, and participants will complete the experiment in a single session individually at a computer with a headset. There may be other participants completing the experiment at the same time, but no interaction will take place between them. Due to monetary restrictions and scarcity of population constraints, data collection might take longer than the two expected weeks or the pool of participants may be reduced.

The procedure consists of a forced-choice task. Participants will be presented aurally syllables (pa – ba) from the voiced-voiceless continuum /b/-/p/, spanning from the Spanish /b/ to the English /p/ one by one. There will be two blocks, and participants will be cued conceptually that they are going to hear English or Spanish. The blocks order will be counterbalanced across participants. For both blocks the syllables will be taken from the whole continuum. After hearing the syllable, participants will have to choose whether they heard /pa/ or /ba/. There will be no extra sounds in the stimuli biasing the responses towards one language or the other.



## Variables

### Manipulated variables (optional)

**Describe all variables you plan to manipulate and the levels or treatment arms of each variable. This is not applicable to any observational study.**





### Measured variables (required)

**Describe each variable that you will measure. This will include outcome measures, as well as any predictors or covariates that you will measure. You do not need to include any variables that you plan on collecting if they are not going to be included in the confirmatory analyses of this study.**




### Indices (optional)

**If any measurements are going to be combined into an index (or even a mean), what measures will you use and how will they be combined? Include either a formula or a precise description of your method. If you are using a more complicated statistical method to combine measures (e.g. a factor analysis), you can note that here but describe the exact method in the analysis plan section.**







## Analysis Plan

### Statistical models (required)


Responses to the two-alternative forced choice test will be analyzed. Since data is categorical (ba - pa), the hierarquical models will be fit with a binomial distribution using the logit link function, using _R_ (R Core Team, 2018) and the package 'lmer4'. We will include participant as a random effect. Mode and 
proficiency will be fixed factors. Finally, the criterion will be response to the VOT continuum. 

### Inference criteria (optional)


We will use p-values as indicators of main effects or interactions. The alpha level will be set at 0.05. We will also assess the gooness-of-fit for the models with marginal _R^2^_ ( _R^2^_ m, without mixed effects) and conditional _R^2^_ ( _R^2^_ c, with mixed effects).


### Data exclusion (optional)

We will exclude data according to the following criteria:

- Error during data collection
- Participant's lack of understanding or engagement during the task






