
This repository is supportive to the following manuscript:
 Al-Ghawanmeh, F., Jensenius, A., and Smaïli, K. Arab Music Improvisation Corpus for Research (AMICOR): Development and Machine Translation Experiments. Journal manuscript submitted for review in August 2023.
 
(the material corresponding to this contribution is all uploaded by August 2025 at the latest),

 We have made the following resources accessible to the research community online: a parallel music dataset comprising 7K sentences distributed across 8 maqam-based sub-datasets, accompanied by a set of Matlab functions for dataset pre-processing (file name: Matlab set of functions to preprocess the dataset.rar). Additionally, initial versions of two Java applications has been shared: 1) the Mawaweel application, integrating the best-performing machine translation model to offer real-time instrumental audio responses to vocal audio prompts; 2) The Corpus Maker application, developed to streamline the dataset construction. Furthermore, we have included a collection of symbolic case studies interpreting the results, alongside a selection of illustrative audio and video examples (File name:Link to computer applications_ Mawaweel and Corpus Maker.docx).

 The manuscript includes a thorough presentation of the eight subdatasets consisting together the AMICOR dataset, particularly in terms of subdataset size (count of parallel sentences), quality (proxied by student versus professional performance), as well as the length of the melodic sentence (count of musical notes' tokens).


 We note that we provide two versions of the dataset: a fully processed version in text format (separated by maqam: file name "AMICOR dataset text representaations.rar", full dataset not separated by maqam, file name: "Clean corpus-20230505T220107Z-001.zip"), and a MATLAB version with only very minor processing (file name: AMICOR dataset Matlab Matrices.rar). While the former was used in our MT experimentation, the latter preserves durations without quantization and allows for a wider range of scale degrees spanning over two octaves (i.e., full vocal range and most of the instrumental range). This provides the research community with a higher-resolution dataset for further explorations. We added a figure to the repository showing an example of a parallel musical sentence, including a table that illustrates the content of each data representation. It presents the musical score, the text representation, the MATLAB file representation, and the corresponding textual illustration used in the manuscript.

While the article's manuscript uses an illustrative data representation, her in GitHub, letters (a to g) correspond to the 1st through 7th scale degrees, while numbers (1-8) signify quantized durations from shortest to longest.


Supporting files:

FILE NAME:                                                      DESCRIPTION

EAMT23.pdf:                                                     a previous article that provides validation of the BLEU metric used in the evaluation in Mawwal MT.

Example of responsive accompaniment.mp3:                        example audio files illustrating the responsive musical accompaniment using the proposed MT method.

Link to example of statistical and Neural MT models.rtf:        link to example models

Links to video presentations from conferences.docx:             links to academic presentations on this project from previous conferences

Live demo in Stocastic Labs Berkeley California Aug 2023.mp4:   video file with live demo illustrating the use of Mawaweel computer application for responive accompaniment using MT.

Python short scripts for analysis of music text corpora.txt:    Python scripts for analysis of music text corpora

published papers and artwork.rar:                               collection of published papers and an artwork within this project (using MT for responsive mawwal accompaniment)





