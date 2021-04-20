# RNN-TV-Script-Generation-Project
Using Recurrent Neural Network (RNN)  to generate new tv scripts as part of Udacity's Deep Learning Nanodegree program.

## Project Overview
This project focuses on creating a RNN in PyTorch that can learn to generate new tv scripts - like Seinfeld scripts.

## Notebook Sections
Load in Dataset
Explore Dataset
Preprocess Dataset: Lookup Tables, Tokenize Punctuation, Save Preprocessed data
Batch Data & Create Dataloader
Define Recurrent Neural Network (RNN) Architecture
Define Forward & Backward Propagation
Define Training Function
Set Model Hyperparamters
Train RNN & Save Model
Generate New Scripts
Results
The model generates conversations between the characters based on the first keyword provided. The script isn't perfect but can be a bit amusing. Common issues seen: duplicated words in a single line, mixing spoken lines with (stage directions), and excessive punctuation.

## Sample Output:

> jerry: articulate donald donald. i was in mortal danger, i had to tell him what happened to him.
> 
> jerry: you know what? 
> 
> george: no further questions. you were fighting fighting.
> 
> jerry: no, no, no.
> 
> hoyt: yes.
> 
> hoyt: you know, i was covering this jury, i was carjacked and the jury's were going to have a little chat removed, and you know the guy that was the moops, geraldo.
> 
> george: what do you say?
> 
> hoyt: yes.
> 
> hoyt: yes!
> 
> george: what are you going to do?
> 
> george: yeah, yeah, sure.
> 
> jerry: what is that?
> 
> jerry: you know, they got the video permission to do it, but you can cross the bubble door.
> 
> hoyt: yes.
> 
> hoyt: you were aware with him.
> 
> hoyt: i cant do this anymore.
> 
> george: i think it's a good thing to be a relief.
> 
> jerry: i think it's a misprint for a while. i had to tell them, geraldo.
> 
> elaine: i know.
> 
> hoyt: so, what do you do?
> 
> jerry: i think she showed a little mishap.
> 
> hoyt: yes.
> 
> hoyt: so, i got accosted on a library.
> 
> hoyt: yes.
> 
> hoyt: so, you were innocentbystanders.
> 
> george: i was in my bathroom and they were going out with them?
> 
> hoyt: i had to tell you what happened to you.
> 
> chiles: so, essentially, i was covering that the most part of selfishness, theyre fighting.
> 
> hoyt: what? what?
> 
> jerry: what?
> 
> hoyt: so?
> 
> hoyt: no further questions.
> 
> hoyt: i was aware of it, but you know what you do.
> 
> jerry: so what do you want to do?
> 
> george: yeah.
> 
> jerry: what?
> 
> jerry: you were in the city?
> 
> jerry: i dont know. `

HyperParameters Set
Sequence Length: 8
Training Epochs: 10
Learning Rate: 0.001
Embedding Dimension: 280
Hidden Dimension: 300
Number of Layers: 2

