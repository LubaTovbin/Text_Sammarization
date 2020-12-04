Text Summarization for Policies 

Ezana Tesfaye (ezana.tesfaye@sjsu.edu)
Liubov Tovbin (liubov.tovbin@sjsu.edu)
Sadia Yousafzai (sadia.yousafzai@sjsu.edu)
Swetha Shiva Shankar Reddy (swetha.shivashankarreddy@sjsu.edu)
Prof. Mahima Agumbe Suresh as a project advisor

With the rapid growth of the web and mobile services, users frequently come across unilateral contracts such as “Terms of Service” or “User Agreement.”  Most current mobile and web applications, such as Facebook, Google, and Twitter, require users to agree to “Terms and Conditions” or “Privacy Agreements.” However, most of us rarely, if ever, read these conditions before signing. The problem is that policies are usually long and written in language that is hard for laypersons to comprehend. Besides, users agree to them without reading them carefully.  Providing users with at least the essence of legally binding contracts helps them understand what users agree to before signing them. In this project, we aim to solve this problem with automatic text summarization. We base our work on the state-of-the-art pre-trained model, PEGASUS. We investigate the possibility to tailor it for a specific task of summarizing the legal policies. Based on our experiments, we conclude that given a small domain-specific dataset, it is better to fine-tune only a small part of the entire architecture, namely the last layer of the encoder and decoder. It prevents the model from overfitting and saves computations. Besides text summarization, we train our model to recognize user preference for the summary length. We use the ROGUE metric as well as partial human evaluation to assess the model performance. To make our text summarization engine accessible, we present it as a web application.

