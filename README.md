# Data and codes
We release the data and codes used in our paper.

We uploaded the core codes in File "code":  
-File "basic" containes the codes of basic model.   
-File "advance" containes the codes of advanced model.
Both basic and advanced models are implemented based on [Fairseq](https://github.com/pytorch/fairseq) framework provided.

File ``yelp'' contains the synthetic semi-structured training pairs and generated summaries.
We randomly sample 30 training pairs from the synthetic training dataset.
      summary_yelp_train: the summary of the samples (Output) 
      OAs_yelp_train: the noisy opinion-aspect pairs of the samples (Input)
      ISs_yelp_train: the noisy implicit sentences of the samples (Input)
      yelp_result: the summaries generated by TBA with BART, which is the best result on Yelp dataset.	  

File ``amazon'' contains the synthetic semi-structured training pairs and generated summaries.
We randomly sample 30 training pairs from the synthetic training dataset.
      summary_amazon_train: the summary of the samples (Output) 
      OAs_amazon_train: the noisy opinion-aspect pairs of the samples (Input)
      ISs_amazon_train: the noisy implicit sentences of the samples (Input)
      amazon_result: the summaries generated by TBA with BART, which is the best result on Amazon dataset.

File ``RT'' contains the synthetic semi-structured training pairs and generated summaries.
We randomly sample 30 training pairs from the synthetic training dataset.
      summary_rt_train: the summary of the samples (Output) 
      OAs_rt_train: the noisy opinion-aspect pairs of the samples (Input)
      ISs_rt_train: the noisy implicit sentences of the samples (Input)
      rt_result: the summaries generated by TBA with BART, which is the best result on RottenTomatoes dataset.
