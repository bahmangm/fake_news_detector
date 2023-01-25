# fake_news_detector
A Self-attention Mechanism based Model for Early Detection of Fake News
First, you need to download FakeNewsNet from https://github.com/KaiDMML/FakeNewsNet and 
its social context by using Twitter API. Then, you need to set the settings in the configs.py file. 
After that, the files need to be run in the following order:

1- content_dataset_creation.ipynb
2- creating_database_tables.ipynb
3- creating_a_table_of_newsids_tweetids_retweetids.ipynb
4- removing_extra_nodes.ipynb
5- creating_a_table_of_lengthes.ipynb
6- creating_propagation_network.ipynb
7- extracting_node-level_and_cumulative_features.ipynb



Finally, you can train the model by running self_attention_based_classifier.ipynb.
