## Lab 1 - Customer Churn Analysis

### Excerpt
From [this](https://aws.amazon.com/blogs/machine-learning/predicting-customer-churn-with-amazon-machine-learning/) blog post 

'Losing customers is costly for any business. Identifying unhappy customers early on gives you a chance to offer them incentives to stay. This post describes using machine learning (ML) for the automated identification of unhappy customers, also known as customer churn prediction. ML models rarely give perfect predictions though, so my post is also about how to incorporate the relative costs of prediction mistakes when determining the financial outcome of using ML.'

I use an example of churn that is familiar to all of us–leaving a mobile phone operator. Seems like I can always find fault with my provider du jour! And if my provider knows that I’m thinking of leaving, it can offer timely incentives–I can always use a phone upgrade or perhaps have a new feature activated–and I might just stick around. Incentives are often much more cost effective than losing and reacquiring a customer.

### Instruction:
- From AWS Console, Goto SageMaker
- Notebook instances -> ml-workshop-notebook -> Open Jupyter
- Open new terminal (under Files tab, far right: New/Terminal)
- In the terminal window: 
    - %cd SageMaker
    - %git clone https://github.com/jxuamazon/ai-ml-workshop
- In Jupyter Notebook
    - open ai-ml-workshop/lab-customer-churn/customer_churn_demo.ipynb
    - Kernel/Restart and Clear Output
    - "Run" go through each step
