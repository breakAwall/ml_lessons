### File Descriptions
<ins>proposal.pdf/proposal.docx</ins>: This includes the pdf and docx respectively of the proposal I had submitted for the capstone earlier

<ins>report.pdf/report.docx</ins>: the report.pdf is the main file, containing my report. It has descriptions and images for the motivation, background, data exploration, model selection, preprocessing, model evaluation, etc.

<ins>data_exploration_raw.ipynb</ins>: This was the first file I wrote, it isn't well formatted data exploration

<ins>data_exploration.ipynb</ins>: This is my 'official' data exploration file, it is clean, documented, and structured and has information on all the data exploration steps I did and included in my report. 

<ins>feature_creation.ipynb</ins>: This file contains code that did any variable selection and preprocessing to create the input and output I would eventually feed into my models. It also has code that runs the benchmark. 

<ins>model_selection.ipynb</ins>: This file contains models that were ultimately selected for presentation in the report. All these models were run on sagemaker.

<ins>selected_model_eval.ipynb</ins>: This file contains code for running cross validation on teh selected model as well as analyzing its output in terms of what it got right and wrong.

<ins>data/</ins>: This director contains all the data files (provided are in json and intermediate ones created by me are csv)

### Setup and Data Retreival
No special Setup is needed and all the raw data is in the data directory as

profile.json
portfolio.json
transcript.json
