# HindiVisualGenome-1.1

Hindi Visual Genome 1.1 is an updated version of Hindi Visual Genome 1.0. The update concerns primarily the text part of Hindi Visual Genome, fixing translation issues reported during WAT 2019 multimodal task. In the image part, only one segment and thus one image were removed from the dataset.

Hindi Visual Genome 1.1 serves in "WAT 2020 Multi-Modal Machine Translation Task".

Hindi Visual Genome is a multimodal dataset consisting of text and images suitable for English-to-Hindi multimodal machine translation task and multimodal research. We have selected short English segments (captions) from Visual Genome along with associated images and automatically translated them to Hindi with manual post-editing, taking the associated images into account.

The training set contains 29K segments. Further 1K and 1.6K segments are provided in a development and test sets, respectively, which follow the same (random) sampling from the original Hindi Visual Genome.

A third test set is called ``challenge test set'' consists of 1.4K segments and it was released for WAT2019 multi-modal task. The challenge test set was created by searching for (particularly) ambiguous English words based on the embedding similarity and manually selecting those where the image helps to resolve the ambiguity. The surrounding words in the sentence however also often include sufficient cues to identify the correct meaning of the ambiguous word.

Please download our released corpus available freely for reseach pupose from the below link.

Download Link : https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3267

Also, read and cite our below paper(in print) about Hindi Visual Genome 1.1

@article{hindi-visual-genome:2019,
  title={{Hindi Visual Genome: A Dataset for Multimodal English-to-Hindi Machine Translation}},
  author={Parida, Shantipriya and Bojar, Ond{\v{r}}ej and Dash, Satya Ranjan},
  journal={Computaci{\'o}n y Sistemas},
  volume={23},
  number={4},
  pages={1499--1505},
  year={2019}
}
