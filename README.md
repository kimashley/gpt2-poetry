# gpt2-poetry

The following code is for my senior honor's thesis project, under the guidance of Dr. Keith Holyoak at the University of California, Los Angeles.

I am currently analyzing whether the GPT-2 model can more effectively generate free-verse or structured poetry by utilizing the GPT-2 architecture (code originated from "Language Models are Unsupervised Multitask Learners" by Radford et. al., paper at this link: https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) to generate poetry trained on two different corpora: a corpora of sonnets (fourteen lined, rhymed poems) and another corpora of free-verse poetry from ten to eighteen lines selected from Poetry Magazine's issues from January 2012 - December 2021. I plan to compare the quality of these poems to randomly selected human-written poems from each of the training sets through a participant survey on the different characteristics of poetry. 

These models are trained and can be prompted to generate poems.

To run: install Python 3.9.8, as well as the following modules: Fire 0.1.3, Regex 2017.4.5, Requests 2.21.0, tqdm 4.31.1, and toposort 1.5.

This project is in process and solely the free-verse portion of the data is currently uploaded to Github. 

Last updated: 1/5/2021
