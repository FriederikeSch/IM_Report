# IM Report

This is an Overview of the scripts used to create the data found in my IM Report

- predict_micro_match:	Predict the relation between premise and claim for the micro label corpus
- create_BERT_model: Train a BERT model for sequence classification
- micro_match:	Make a dataframe from the micro corpus to predict premise-claim-pairs with the trained BERT model
- big_essay_model:	Make a dataframe of the big essay corpus to train premise-claim-pairs with the BERT model
- Claim_Match_model:	Makes dataframe from the small essay corpus with premise-claim pairs to train the BERT model
- Word2vec:	Matches premises to claims on the small essay corpus with a Word2Vec model
- Predict_premise_claim_type:	predicts the claim_type to a given premise from the trained BERT model
- create_training_frame:	Make a Dataframe containing only claims and their claim types (Fact, Value, or Policy) to feed in to a model for claim type prediction.
- micro_label:	Matches claim types for the micro corpus (no gold labels to check validity)
- Make Essay Dataframes:	read in the ann files of the essay corpus and transform them into dataframes 
- Sentence length:	Shows the average length of the corpora
- fraction of prem and claim: shows fractions of premises to claims in the corpora
