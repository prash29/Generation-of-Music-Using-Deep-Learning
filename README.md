# Generation-of-Music-Using-Deep-Learning

The weight of the model used after training is available in the link below
(https://drive.google.com/open?id=1gl9icPYtfDMPS-H2xnwwBrSnCsJnzCCT)

### Brief Description


The dataset used in this project is a subset of the piano music avaialble in the MAESTRO dataset. The models don't try to generate multi-instrument music. The focus has been on learning structural patterns to create sequences for single instrument (piano) music.
This project primarily aims to compare two deep learning techniques in the task of learning musical styles and generating novel musical content. An LSTM model and a GAN model were evaluated using a survey which helped in obtaining an Mean Opinion Score (MOS) which was used as an indicator of the comparative quality and performance of the models. The MIDI files were processed using the Music21 library. 

The models generated music of specified lengths and BPM (Beats per minute). Ample number of samples were created so as to increase the sample size of comparison. Further, a small study was conducted to get a better metric. Subjects in the study were made to listen to samples of both the models and a few human samples from the real world in a random order. The Mean Opinion Score (MOS) indicator was used as the metric. The listeners in the study were also asked to classify the sample as human or AI generated. 

The study involved around 150 participants from diverse backgrounds. Some, with fairly good understanding of music theory, some who don’t necessarily understand music theory, but listen to a lot of music regularly and finally, some, who don’t listen to music regularly. The MOS for both the models combined was 3.55. Individually, the LSTM model performed better with a MOS of 3.80 compared to the GAN model which had a MOS of 3.17. The MOS for each of the music samples is shown in bar graph below. It was also observed that 63.8% of the participants classified the samples of the LSTM model as human composed as shown in the pie chart below. This implies that the participants identified in these samples, some semblance to the human ones in terms of structural patterns, emotion or just melody.

Some of the sample music generated can be found here https://drive.google.com/open?id=13bMdHkV0nsN7rQ8pC_l9rgH7b8sFDvLP .



###### Mean Opinion Scores
![Alt text](https://github.com/prash29/Generation-of-Music-Using-Deep-Learning/master/bar.png)
