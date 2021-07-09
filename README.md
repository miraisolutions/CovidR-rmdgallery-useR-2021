# useR! 2021: CovidR and `{rmdgallery}`

## A streamlined process for collecting community contributions in a gallery website

Riccardo Porreca, Francesca Vitalini, [Mirai Solutions GmbH](https://mirai-solutions.ch)

Regular talk at [useR! 2021](https://user2021.r-project.org/)


## Abstract

The active open source community is certainly one of R’s greatest assets. During the organization of the virtual e-Rum2020, in the midst of the pandemic outbreak, the Organizing Committee thought of engaging the R community by gathering contributions around the topic of COVID-19, as part of the pre-conference event CovidR (https://2020.erum.io/covidr-contest). This came with the need for a smooth and integrated way of collecting community work, which was elegantly addressed in the form of a contributions gallery website (https://milano-r.github.io/erum2020-covidr-contest), populated with submissions coming as Pull Requests / Issues in a GitHub repository.

Behind the scenes, this was supported by the development of a novel package rmdgallery (https://riccardoporreca.github.io/rmdgallery), providing an R markdown site generator for a gallery of (embedded) content created in a dynamic way based on metadata in YAML or JSON format. This simple yet flexible tool, paired with GitHub Actions and the community features of GitHub, was key to the CovidR success, in a number of ways. These include: seamless submission process, automated inclusion in the gallery of contributed abstracts and content, collecting "likes'' using Utterances (https://utteranc.es), dynamic badges reflecting the status as the context evolved, live updates during the event with the announced awardees in a matter of a pull-request.

In this talk, I go through the main features of the package and its application for the CovidR contest, highlighting the power of using open source tools for community and collaborative initiatives.
