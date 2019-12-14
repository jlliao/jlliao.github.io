---
title: "Apply Machine Learning to My Illness"
excerpt: "How can we use machine learning to reason our diagnose process?"
header:
  overlay_image: /assets/images/god-algorithm.jpg
  overlay_filter: 0.5
categories:
  - Machine Learning
tags:
  - machine learning
  - philosophy
---

Recently, as I start to understand machine learning, I have chosen a well-written book to be my guide. The Master Algorithm written by Pedro Domingos has invited me to take a deep look at five different tribes of machine learning, the symbolists, connectionists, evoluationaries, bayesians, analogizers. Each has their own advantages and constraints when applied to diverse scenarios, and Pedro Domingos has demonstrated how they could be united to construct the ultimate master algorithm, the same algorithm that can be applied to so many different things in our daily life. To be honest, when I read such spellbinding quest, I was a bit skeptical. The search for the so-called ultimate theory has been emerging in numerous academic fields, just as the string theory in physics and ultimate theory of personality in psychology, yet after decades of conjecture and research, none has been fruitful. What would make this master algorithm a potential reality and how can we benefit from such understanding? Would it be even possible to combine logic and probability?

I have put this book aside as I was preparing for my final exams at the college.

# From the Master Algorithm to My Illness

Unfortunately, I was sent to hospital’s emergency on a night recently due to breathing difficulty. It was four o’clock in the morning. As I was totally exhausted, a doctor has called upon me to do a checkup. She looked at me and said, “Okay, tell me what is wrong.” While in pain, I told her that I have breathing difficulty and both my nose and throat are blocked. Here, what I was doing is to provide her data to process, or more precisely, a description of an effect. She then searched my medical history and found out that I have chronic rhinitis, “Are you using a nasal spray regularly?” My answer was no, because I have used it for three months and the spray is not very effective. “Well then, I will prescribe you a nasal spray. That is probably why your nose is blocked. You need to do a lateral X-ray on your neck so that I can clearly see what is happening to your throat.”

Well then, although the doctor may not realize it, she is a Bayesian, who uses a consequential effect to conjecture the cause. But wait, she may not a Bayesian, because, in order for her to use probabilistic inference to obtain a high posterior probability, I would have to come very often, and specifically to this hospital, with a blocking a nose and a rhinitis history. The fact that she made a prescription so quickly would make her a symbolist, who use inverse deduction with pure logic. Just like traversing a decision tree, her mind has gone through multiple “If-Else” statements and prescribed me the nasal spray, given the fact that I have a blocking nose and rhinitis history.

After half an hour, the X-ray image was sent to the doctor’s computer. She skimmed through the image and said, “Your airway looks pretty normal. I think all you need is some anti-swelling medicine to unblock your throat.” The diagnosis might seem simplistic, as the doctor only considered one area of the image. A connectionist would instead use a recurrent neural network to check the whole image and suggest any abnormality. Such algorithm may not be able to replace the intuition of a doctor, but would provide interesting points that the doctor would have ignored if the image is checked in a hurry.

# Machine Learning Is Not Panacea

To my surprise, after reading The Master Algorithm, I started to think as a machine learning developer and consider cases where machine learning could help to optimize or automate. But can we really implement these algorithms?

For the past year, we have read many articles claiming that a specific algorithm has surpassed human doctors in a specific type of diagnoses, such as skin cancer and pneumonia. How do we fathom these claims? Do they really understand the pain points in the diagnostic process and address doctors’ and patients’ demands? How can we apply these algorithms to a realistic environment, where data are highly complex, segmented and full of errors? These questions are often overlooked in a kaggle machine learning competition.

In fact, recently IBM Watson has failed to collaborate with MD Anderson, a top-level medical center in the US. We can see that the application of Artificial Intelligence or machine learning should focus more on how to improve doctors’ work (such as generating reports for medical image or recommend prescriptions), rather than idealistically replacing doctors to make a diagnosis. Despite the discussion on whether such ultimate goal can be achieved or accepted, any application of AI or machine learning should not bypass the necessary incremental process. Therefore, any comparison between human doctors and AI violates the scientific testing principle. The papers that do not consider the realistic application scenarios or dramatize the competition between human and machine are misleading to both medical practitioners and the public.

# The Challenges Remain in the Medical Field

What are the challenges that prevent us from effectively applying machine learning to medical diagnosis, tracking and management? If we go back to the process of machine learning, we can find that there are still numerous fundamental issues that have not been solved in realistic scenarios. These findings may not appear in the research papers, but they are crucial and indispensable to the success of implementation.

First, heterogeneous data exists everywhere in the hospitals and clinics – medical image, videos, voices, text, structural data and unstructured data. Each type of data has its own processing method, storing format, transmitting method and algorithm. Nonetheless, if multiple formats and data sources can be integrated and analyzed, the medical Big Data can greatly improve treatment quality and patients’ satisfaction, and at the same time, lower the treatment risk and medical cost. Yet, how do we develop a system that can optimize the usage of multimodal data to make better diagnosis and treatment? This is still a challenging task.

Secondly, there is deficiency in valid data. We would not expect Big Data in most of the applications. However, we still hope to make use of those small data to train a general-purpose model. In this case, we can use a small dataset from one field to learn in another field. Through transfer learning, we can achieve the similar effect and solve the problem of data island, but there is still a long way to go.

Thirdly, we prefer personalized models to achieve precise medication. Through incremental learning, we can create models that fit individual profiles. Starting from a general model, the model will be updated in the process of interactions between professionals and patients. Idealistically, after a period of time, a particular model would be flexible enough to suit individual demands.

Fourth, we would need energy-efficient local infrastructure to support the system. In competitions or in theoretical settings, the cloud has huge amounts of computational power, so energy-consumption and efficiency is not the top priority. However, most medical centers would still not permit transferring medical data to cloud services because they could risk leaking private health data. Thus, data tends to be stored locally in the user terminals, but it would be difficult to apply machine learning to local machines.

The quest for the master algorithm is surely appealing, but there is still a mountain to climb when it comes to application. In specific fields such as the digital transformation of healthcare, the gap between theory and reality has never been so immense.