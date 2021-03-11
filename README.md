# Text-Summarization-and-Classification-of-Clinical-Discharge-Summaries-using-Deep-Learning [Preprint](https://www.researchgate.net/publication/340407380_Text_Summarization_and_Classification_of_Clinical_Discharge_Summaries_using_Deep_Learning)

Clinical Discharge Summaries contain a huge amount
of data but are difficult to obtain and to be used in analysis because
of its unstructured narrative format. Also, they contain spelling
mistakes, abbreviations which makes it difficult to summarize.
With vast amount of information, there is a need to have a proper
segregation of important details like Symptoms, History,
Medications to have a better and efficient classification. 

To save the overall time and energy of the patient and increase the
effectiveness of the physician in saving the lives of the sufferers,
we suggest a classification of the Clinical Discharge Summaries
text, which aims to automatically predict the diagnoses needed for
a patient based on clinical notes. The reminiscence is represented
by a raw text file with doctor's entnaaries about the patient
including his / her age, problems described in normal flow, history
of the patient and so on. 

We are also investigating the automated
classification of patient discharge notes into standard disease
labels which includes the name of the diagnostic procedure
required. In this approach, we use Convolutional Neural Networks
to classify and represent complex features from the medical
discharge summaries using the MT sample dataset. We make use
of GloVE to have a pretrained model learn from it.

We implemented our CNN model on MT samples dataset
with multiple layers being added and removed to improve the
efficiency. Our training accuracy increases with every epoch
and reaches 0.87 and the validation accuracy is at 0.89 as
shown in the graph 1. The model during its validation set also
achieved a recall score of 0.888, precision of 0.98 and an F1
score of 0.939.
