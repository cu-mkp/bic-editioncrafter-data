# editioncrafter-data

Data and metadata for an edition prototype of Mary Anne Rawson's anti-slavery anthology [*The Bow in the Cloud*](https://github.com/cmohge1/bow-in-the-cloud-edition) (1834), created with EditionCrafter, a publication tool for digital critical editions under development by the [Making and Knowing Project](https://makingandknowing.org/) (M&K), [Performant Software Solutions](https://www.performantsoftware.com/), and a number of other case-study collaborators. EditionCrafter, under development (2022-2024), is designed to be an open-source, customizable publishing tool that will allow users to deploy their own texts, data, and commentary as low-maintenance digital critical editions. It will enable the creation of static sites that rely on basic well-established technologies and workflows to address issues of longevity, maintenance, sustainability, and cost. For more about this work, see the NSF award announcement: [Crafting an Open Source Digital Publication Tool for the History of Science](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2218218&HistoricalAwards=false).

This project builds upon the publication of *[Secrets of Craft and Nature. A Digital Critical Edition of BnF Ms. Fr. 640](https://edition640.makingandknowing.org/#/)* by the Making and Knowing Project. The underlying software developed for *Secrets of Craft and Nature* will serve as the starting point for EditionCrafter. 

## About *The Bow in the Cloud*

*The Bow in the Cloud* is an anti-slavery anthology that was published in 1834 by the London firm of Walford & Jackson, in St. Paul’s Churchyard. The anthology consists of 85 poems and prose pieces by a mixture of well-known and non-professional writers involved in anti-slavery societies throughout Great Britain. It was edited by Mary Anne Rawson, née Read (1801–1887), who sought to create what she called in her Preface to the anthology ‘a structure of moral and literary architecture’.  In 1826, Mary-Anne Read, a young activist in Sheffield encouraged by the example of her philanthropist parents, sought to assemble an anti-slavery literature anthology to influence public opinion. Yet the project stalled, for reasons that are not yet known. By 1834, Mary Anne, now married to George Rawson, and still living in Sheffield, had re-ignited the project and shepherded The Bow in the Cloud into publication with a major London publisher.

*The Bow in the Cloud* is an early example of the political literary anthology, and a rather large one (over 400 pages) with some long pieces, and it features grassroots activists, politicians, and well-known literary writers (but no Romantic authors, although Rawson tried to commission work from the likes of Wordsworth, Southey, and Thomas Moore). This kind of eclectic book not only reflected growing literacy rates in the UK but also was the product of several decades of energy from various publishing movements, including the religious press, the new business of editorial reproductions, cheaper printing technologies, the expansion of the literary marketplace after the era of radical political publishing, and women's anti-slavery societies.

*The Bow in the Cloud* also comes with an under-researched manuscript collection of more than 600 items that is vast and revealing – particularly so for an anthology of this kind, with so many contributors. Each submission to the anthology came with a covering letter (and some submissions have multiple letters spanning from 1826 to 1834), and some pieces also came with photographs, artworks, engravings, or newspaper clippings. 

The primary purpose of the edition of this anthology is to show how the it was constructed based on the surviving documentary evidence. There are three parts to the edition: the published version of The Bow in the Cloud (along with the attendant manuscripts relating to each piece); a selection of important unpublished material, including poems that were submitted but not published in 1834, and letters from authors who declined to contribute to the anthology; and network analysis and mapping tools to demonstrate the social and semantic networks, as well as the geographical breadth, of the people associated with the anthology. This project is mainly using EditionCrafter to provide reading texts of select unpublished manuscripts from the collection, which will complement the project's [Scalar-based edition](https://christopherohge.com/education/bow-in-the-cloud/index?path=index).

## editioncrafter-data repository

This repository is a template repository for users who plan to use EditionCrafter to create their editions. It contains the basic structure and organization of the files needed as input for the creation of the "folios view" element: the side-by-side viewing panes of the text, where users can choose between versions of the text including facsimile images, transcribed text, and translated text. All associated metadata is also to be housed in this repository.

<img src="https://raw.githubusercontent.com/cu-mkp/edition-webpages/master/images/howtouse-dualpane.png" alt="how-to-use-dualpane" width="500">

> Example of the "folios view," with side-by-side viewing panes of [fol. 4r](https://edition640.makingandknowing.org/#/folios/4r/f/4r/tl) of BnF Ms. Fr. 640 in *Secrets of Craft and Nature*.


## How-tos

Because this repository may be used by beginners, a number of helpful how-tos have been included:
- [Introduction to Git and Github](how-tos/intro-to-github.md)
- [Naming Protocols](how-tos/naming-protocols.md)
- [Setting up Github to Work Locally & General Workflow](how-tos/github-local-setup-and-workflow.md)
- [Command Line Intro and Helpful Commands](how-tos/command-line.md)
- [Project Setup Overview](how-tos/project-setup.md) - reference for project developers

## Repository Structure

This repository has two main areas: 
1. [texts/](texts/) directory - all files associated with an edition's source material (i.e., transcriptions and translations)
2. [metadata/](metadata/) directory - all metadata (data about data) associated with an edition

This is based upon the model used for the creation of *Secrets of Craft and Nature*. M&K's repository for BnF Ms. Fr. 640’s data is [cu-mkp/m-k-manuscript-data](https://github.com/cu-mkp/m-k-manuscript-data) and the “read me” file (scroll down below the file and directory listings on the repo's homepage) describes the repo's structure and how M&K has already worked with Github for *Secrets of Craft and Nature*.
