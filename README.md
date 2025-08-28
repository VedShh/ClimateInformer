# ClimateInformer

Climate change presents an urgent global challenge, yet widespread misinformation and a lack of accessible, adaptable educational tools significantly impede public understanding and proactive engagement. Existing climate models often lack the real-time adaptability and user-specific scenario exploration capabilities necessary to foster deep comprehension and empower individual action. This paper introduces ClimateInformer, a web-based educational platform that integrates user-defined scenarios via a Large Language Model (LLM)-driven carbon emission estimator. Users enter custom scenarios such as 'Oil use goes up 50\%' along with a time duration. These inputs get fed into the LLM, which generates a predicted carbon delta, which feeds into our refined SVR predictive model, achieving approximately 91\% accuracy when compared to real data. The predictive model predicts the final temperature which is then fed back into the LLM to generate the mitigation strategies and then we push it all to the frontend. Unlike static carbon footprint calculators or preset simulation models, ClimateInformer offers personalized, interactive insights. The model demonstrates robust predictive accuracy, and initial human trials across 20 different participants have shown a 5\% increase in climate literacy among participants. We are introducing a simple tool, to the best our knowledge, is the first climate literacy tool that provides a unique, interactive platform that can be easily used/reproduced by middle and high school students. 

To use this system, do the following:
1. Upload code into google colab
2. Upload dataset into google drive
   --> To get the full dataset you must download (or just set it up with Github Desktop) the entire ClimateInformer repo onto your local drive, which at that point you will get full access to the dataset
4. Run the first 2 code cells in order
5. In the output of the 2nd code cell, there should be an ngrok link that takes you to a local version of the software
6. Explore the code!

The last code cell is for debugging. If the code does not work for some reason, run the last code cell, and then rerun cells 1 and 2. 
