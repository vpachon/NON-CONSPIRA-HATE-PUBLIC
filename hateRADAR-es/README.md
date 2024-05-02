# Dataset Description

The hateRADAR-es dataset comprises tweets collected to study hate speech against refugees in the Spanish language. It includes several thousand tweets that were gathered using keywords related to refugees and immigration, and further filtered to focus on potential hate speech content.

# File Description

The dataset is divided into two sets for reproducibility of experiments: training and testing datasets. Both datasets are provided in CSV format with the following fields:

    ID: The unique identifier for each tweet. You can use this ID to retrieve individual tweets from the Twitter API of your choice.
    Label: Binary label where 0 represents "No hate speech" and 1 represents "Hate speech detected".

# Label Interpretation
The criteria for labeling are based on detailed linguistic and contextual analysis as described in our paper, "Deep Learning Approaches for Identifying Anti-Refugee Speech in Spanish Texts." The labeling process was designed to capture not only explicit expressions of hate but also subtler forms of negative sentiment that could be indicative of underlying prejudice. This comprehensive approach ensures that the dataset supports the development of NLP models that are sensitive to the nuances of language used in hate speech.

The use of this detailed labeling criteria stems from the need to accurately differentiate between general negativity and specific hate speech targeted at refugees, which is crucial for training effective machine learning models that can be deployed in real-world scenarios to monitor and mitigate such harmful content on social media platforms.

# Annotation Process

The annotation was conducted by sociolist and social workers native Spanish speakers, who followed rigorous guidelines to ensure the consistency and reliability of the labels. The annotation process was iterative, involving multiple rounds of review to refine the guidelines and improve inter-annotator agreement. This detailed process is perfectly described in our paper "Deep Learning Approaches for Identifying Anti-Refugee Speech in Spanish Texts." In the paper, we outline the specific criteria and methods used to ensure high-quality annotations, discussing the challenges faced and how they were addressed to achieve a robust dataset. This comprehensive description provides a foundation for understanding the meticulous effort involved in preparing the dataset and the importance of precise annotation in developing effective machine learning models for hate speech detection.

# Citation

Please cite the use of the hateRADAR-es dataset in your work as follows:

    (Your Name, Year). hateRADAR-es: A Dataset for Detecting Hate Speech Against Refugees in Spanish. [Title of Your Paper], [Journal/Conference Name].

# Contact

If you have any questions, feedback, or need further information about the hateRADAR-es dataset, please feel free to contact me. I'm more than happy to assist you with any queries or provide additional details.

You can reach me via email at vpachon@uhu.es.

If you need access to the dataset that includes the text of the tweets, please let me know, and I'll be glad to discuss the possibilities of sharing that version with you.

I'm also open to collaboration or any suggestions to improve the dataset and its usability. Your input is valuable, and I look forward to hearing from you!

Thank you for using the hateRADAR-es dataset.
