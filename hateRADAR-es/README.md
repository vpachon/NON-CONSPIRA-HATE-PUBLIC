# Dataset Description

The hateRADAR-es dataset comprises tweets collected to study hate speech against refugees in the Spanish language. It includes several thousand tweets that were gathered using keywords related to refugees and immigration, and further filtered to focus on potential hate speech content.

# File Description

The dataset is divided into two sets for reproducibility of experiments: training and testing datasets. Both datasets are provided in CSV format with the following fields:

    ID: The unique identifier for each tweet. You can use this ID to retrieve individual tweets from the Twitter API of your choice.
    Label: Binary label where 0 represents "No hate speech" and 1 represents "Hate speech detected".
