---
title: DI study group 22.7.2019. - Retina dataset i MNIST grupni rad
date: 2019-07-22T12:07:09.806Z
image: /images/screenshot-2019-06-27-at-5.36.25-pm.png
tags:
  - di-study-group-pula
published: true
---
## fast.ai course
Vecina polaznika je pogledala prva dva videa. 
Objasnili smo [SGD](https://en.wikipedia.org/wiki/Stochastic_gradient_descent) ili koristenje derivacija za pronalazak minimuma kroz dva notebooka.

* [linearna funkcija](
https://www.kaggle.com/init27/fastai-v3-lesson-2-sgd)
* [kvadratna funkcija](https://www.kaggle.com/matejthetree/sgd-2)

ko voli matematiku nek prouci :)

## nastavak sa maslinama

evo [kernela](https://www.kaggle.com/ksaric/olives-basic-weight-decay-progressive-resizing/) koji je Kristijan Saric napravio sa maslinama. 
Naime, pokazalo se kako je na nasem datasetu sa listovima od masline model overfittao papir, jer je svaka osoba koristila isti papir za iste masline. Da bi to zaobisli, povecali smo weight decay i dobili smo model ciji heatmap se fokusira na listove.

## Retina dataset
https://www.kaggle.com/c/diabetic-retinopathy-detection

Stay tuned with retina dataset, do srijede cu uploadati resizeani dataset koji mozemo koristiti za treniranje.

/////

## MNIST FULL Zajednicki rad

Evo [link na fastai kernel](https://www.kaggle.com/matejthetree/mnist-full-zajednicki-rad?scriptVersionId=17653625) sa MNIST full datasetom i sa defaultnim postavkama i samo 4 ciklusa.

Probajte dobiti accuracy sto blizi 100%!



