# SMS_Spam_Detection

As we are in 2021, you must know what is an e-mail and most probably you have either received it or sent it or maybe both. Well, E-mail is a message that may contain text, files, images, or other attachments that is sent through a network to a specified individual or group of individuals.

Despite having lot of chat apps like WhatsApp, Facebook messenger, snapchat etc, e-mail has remained a central part of daily digital life. In 2024, the number of global e-mail users is set to grow to 4.48 billion users, up from 3.8 billion in 2018. In terms of the most popular e-mail clients, Apple and Google are in a constant battle for the top spot.

The main idea of spam is to make a profit and it is very cheap to send, the cost are insignificant as compared to conventional marketing techniques, so marketing by spam is very cost-effective, despite very low rates of purchases in response. Junk emails sent to penetrate user inboxes with messages intended to promote products and services in order to turn a profit.

But now a days, spam is progressively being viewed as a more severe messaging threat, as it is coming to be used to deliver worms, viruses, and Trojans as well as rooks of more directly financial nature. Spammers often trick even the sharpest of e-mail users into opening these messages.

Not only this there are variety of problems caused by spam such as,

- Spam prevents the user from making full and good use of time, storage capacity and network bandwidth.

- The huge volume of spam mails flowing through the computer networks have destructive effects on the memory space of email servers, communication bandwidth, CPU power and user time.

- The menace of spam email is on the increase on yearly basis and is responsible for over 77% of the whole global email traffic.

- It is also resulted to untold financial loss to many users who have fallen victim of internet scams and other fraudulent practices of spammers who send emails pretending to be from reputable companies with the intention to persuade individuals to disclose sensitive personal information like passwords, Bank Verification Number (BVN) and credit card numbers.

This is the Spam detection classifier detecting the sms or email is spam or ham based on their characteristics.
The dataset collected from the kaggle.
Used NLP explicitely in this project as this is textual classification data.
Data cleaning was complex task in this project and used NLP concepts to carry out this project

The two common approaches used for filtering spam mails are knowledge engineering and machine learning. Emails are classified as either spam or ham using a set of rules in knowledge engineering. The person using the filter, or the software company that stipulates a specific rule-based spam-filtering tool must create a set of rules. Using this method does not guarantee efficient result since there is need to continually update the rules. This can lead to time wastage and it is not suitable especially for naive users.

Unlike knowledge engineering approach, In machine learning, no rule is required to be specified, rather a set of training samples which are pre-classified email messages are provided. A particular machine learning algorithm is then used to learn the classification rules from these email messages. Several studies have been carried out on machine learning techniques and many of these algorithms are being applied in the field of email spam filtering. Examples of such algorithms include Deep Learning, Naïve Bayes, Support Vector Machines, Neural Networks, K-Nearest Neighbour, Rough sets, and Random Forests.

To effectively handle the threat posed by email spams, leading email providers such as Gmail, Yahoo mail and Outlook have employed the combination of different machine learning (ML) techniques such as Neural Networks,  in its spam filters. Since machine learning have the capacity to adapt to varying conditions, Gmail and Yahoo mail spam filters do more than just checking junk emails using pre-existing rules. They generate new rules themselves based on what they have learnt as they continue in their spam filtering operation.

Whereas Unsupervised learning is the training of machine using information that is neither classified nor labelled and allowing the algorithm to act on that information without guidance. Here the task of machine is to group unsorted information according to similarities, patterns and differences without any prior training of data.

There are two types of training in neural network.

1.   Supervised: Here, the network is given a set of inputs and matching output patterns, known as training dataset, to train the network.  
2.   Unsupervised: In this instance, the network trains itself by producing groups of patterns. There is no earlier set of training data given to the system. 

