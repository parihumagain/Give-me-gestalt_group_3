
# Background
> "The finding of this strong correlation between detectability and preference offers wide implications for art history and human cognition as it points to a mechanism that allows us to derive pleasure from searching for and finding meaningful patterns." [1] <br>

Gestalt theory has been around for a while and it was suggested that it was never initially proven, that people prefer art in which they can recognize patterns and structures. The experiment we reproduce acknowledge this lack of scientific proof of a relation that was proposed in many different contexts: philosophy, psychology and neuroscience. Cubist art is chosen, since it is a mixture of forms, which need to be assembled by the viewer - and that are more or less easy to detect. Reviewing the experiment we noticed that only 20 participants were tested and a strong positive correlation between likliness and understanding was suggested [1]. We aim to have more participants for our study to get a broader and more reliable result. 

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
   
   format?, when? What type?(monochrome, colour)?)

## Procedure
The exeriment is conducted as a browser experiment participants can access online. It is diveded in three major blocks, first the introduction, used to explain the following tasks and to perform vision tests and request former knowledge in cubist art, followed by the main experiment which consists of two blocks.

### Introduction

1. „Do you consider yourself an expert in Cubist art?“ If you do, this experiment is unfortunately not for you! <br>
2. Group is randomly chosen and participant is assigned to one of three experiments, each containing 40 images out of the original pool of images.<br>
3. Ensuring approx. Same size of images and vision tests every screen for all participants.<br>
4. Vision test: Vision is tested with Ishihara and Snellen testing, ensuring normal vision for all participants.<br>
5. Trials?? <br>
6. First round: Participants rate how well they like images shown in random order on a scale of 1-7*<br>
7. Second round Participants rate how well they are able to identify forms/patterns  in the whole image on a scale of 1-7* (in the same pictures from 4, randmoly mixed)<br>
*1 not at all- 7 very much

## Measured variables
• based on the design you described, what are the variables that you are going to measure <br> 
  • Variables measured: likleness on scale 1-7 <br>
  • how well they think they are able to identify patterns in scale 1-7 (1 being very bad and 7 being very good) <br>
• how will they be measured in the experiment? <br>
    Either pole or single numbers that can be clicked? <br>
• how will they be treated: 1 not at all- 7 very much


# Analysis Plan

## Exclusion criteria
• for single trial data: <br>
        ◦ if they took longer than 2min to decide (to ensure that the participant is not to distracted)<br>
        ◦ if they rated all likeliness/recognitions the same, if the answered in <3s 
    • whole participant data excluded:<br>
        ◦  if 3 trials shorter than 3 sec<br>
        ◦ Whole participant excluded if they took longer than 3 min for each of 5 continuos paintings<br>
    • if they do not pass vision tests<br>


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


