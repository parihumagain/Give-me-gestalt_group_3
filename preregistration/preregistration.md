
# Background
> "The finding of this strong correlation between detectability and preference offers wide implications for art history and human cognition as it points to a mechanism that allows us to derive pleasure from searching for and finding meaningful patterns." [1] <br>

Gestalt theory has been around for a while but it was never initially proven, that people prefer art in which they can recognize patterns and structures. The experiment we reproduce acknowledge this lack of scientific proof of a relation that was proposed in many different contexts: philosophy, psychology and neuroscience. Cubist art is chosen, since it is a mixture of forms, which need to be assembled by the viewer - and that are more or less easy to detect. Reviewing the experiment we noticed that only 20 participants were tested and a strong positive correlation between likliness and understanding was suggested [1]. We aim to have more participants for our study to get a broader and more reliable result. 

# Research questions
Is there a positive relation between the recognition of patterns and structures and the likleness of a cubist painting?

# Design of the Experiment

## General remarks about the design

what kind of a study is it (e.g., a 2x2 within-subjects factorial design)

## Sampling plan

### Participants
We plan on recruiting as many participants as possible, but we would like to have at least 40, to give a broader outcome for the study.
Potential participants include: <br>
* course members <br>
* other students via mailing lists <br>
* friends, family <br>

### Restrictions
- people with impaired colour vision
- people with impaired vision without correction (shortsightedness/longsightedness)
- people with expertise in cubist art


## Materials
To garantee a data acquisition as similar as possible to the original experiment we use the same material. 
   - To ensure normal/corrected-to-normal vision: <br>
     * Standard Snellen's eye chart test <br>
     * Short version of the Ishihara Colour test <br>
   - the images of the cubist paintings (from now on only to be called images) from the original experiment <br>
     * 120 cubist Paintings: Pablo Picasso (47), Georges Braque (33) and Juan Gris (40) <br>
     * the images are adapted to 450 pixels width and 600 pixels height <br>
     * there are monochrome and coloured images <br>
   
   format?, when? What type?(monochrome, colour)?

## Procedure
The exeriment is conducted as a browser experiment participants can access online. It is diveded in three major blocks, first the introduction, used to explain the following tasks and to perform vision tests and request former knowledge in cubist art, followed by the main experiment which consists of two blocks.

### Introduction
The introduction part consistis of following sections. <br>
1. Welcome message and short describtion of the procedure in general. <br>
2. Request about former knowledge in cubist art: <br>
  * „Do you consider yourself an expert in Cubist art or were you ever engaged in any kind of cubist art education?“ <br>
  * Participants who answer "Yes" have to be excluded after data aquisition. <br>
3. Ishihara Colour Test: Participants have to fill in the correct number in a blank space, those who give a wrong answer have to be excluded. <br>
4. Snelllen's Eye Chart Test: ???<br>
5. Ensuring approx. Same size of images and vision tests every screen for all participants. ???<b> <br>
   
Participants are assigned to one of three groups, each containing 40 images out of the original pool of images. The original experiment showed in each trial all 120 images to each participant - since that leads to a very long experiment, we deceided to shorten the procedure to make sure that participants finish the experiment.<br>

### Experiment Part 1: Preference Rating
1. Description of the task <br>
2. Task itself: <br>
  * Participants are shown 40 Stimuli in randomized order <br>
  * Each image has to be rated on liking using a 7-point-Likert-scale from 1 ('not at all') to 7 ('very') <br>
  
### Experiment Part 2: Detectability
1. Description of the task<br>
2. Task itself: <br>
  * Participants are shown 40 Stimuli in randomized order <br>
  * Each image has to be rated on how well object can be detected using a 7-point-Likert-scale from 1 ('not at all') to 7 ('very') <br>
  
### Closing Part
Last part consists of a 'Thank you for participation' message.

## Measured variables
The data aquisition will assign several values from an ordninal skala from 1 to 7 (see above) to each image for <br>
  * Detactability (X) <br>
  * Linking (Y) <br>
such that for each picture an average value can be computed.

# Analysis Plan

## Exclusion criteria
1. for single image/trial data: <br>
  ◦ if they took > 2min to decide for one image (to ensure that the participant is not to distracted)<br>
  * if they answered in < 3s <br>
  ◦ if they rated all likeliness/recognitions the same
2. whole participant data excluded:<br>
  ◦ if 3 images answerded in less than 3 sec<br>
  ◦ Whole participant excluded if they took longer than 3 min for each of 5 continuos paintings<br>
  * if they do not pass vision tests<br>


## Confirmatory hypothesis testing
  • if applicable, describe any transformations that you might want to apply to the data<br>
  • describe your statistical model <br>
        • e.g., we will use the ‘brms’ package to run a Bayesian regression model regressing <br>
        XYZ against A, B and C and their interactions<br>
  • describe by what means you will test the hypotheses mentioned earlier <br>
  • when you do this you will want to reformulate the hypotheses in a more precise fashion <br>
     • e.g., if H1 is true, we expect that parameter X is credibly bigger than zero in the posterior distribution <br>  
     
## Resources

[1] MUTH, Claudia; PEPPERELL, Robert; CARBON, Claus-Christian. Give me Gestalt! Preference for cubist artworks revealing high detectability of objects. Leonardo, 2013, 46. Jg., Nr. 5, S. 488-489.


