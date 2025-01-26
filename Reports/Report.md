# REPORT

**METHODOLOGY**
* The Steps to Develop a Chatbot
  1. Crawl data from any website to collect information (e.g., https://www.presight.io/privacy-policy.html).
  2. Perform preprocessing for NLP.
  3. Convert the data into vectors (Embedding).
  4. Receive the question input from the user interface.
  5. Preprocess and embed the question input.
  6. Find matching vectors: To improve the model's performance and accuracy, we retrieve the top 3 vectors with the highest scores instead of just the top 1.
  7. Use the high-scoring vectors to identify the corresponding passages they represent.
  8. Map the identified passages to larger text segments to ensure sufficient context and information are provided.
  9. Input the mapped passages into the Gemini API or a similar LLM to process and generate accurate, natural responses.
  10. Output the generated response from the LLM to the user interface.

**REFLECTION**
* Achievements: Successfully developed a chatbot capable of delivering results with up to 95% accuracy.
* Limitations: Insufficient attention and development on the chatbot's front-end interface.

**A set of questions to evaluate the results**
1. Privacy Policy and User Rights

 Q1: What purposes does Presight use personal data for?

 Q2: How can I edit or update my personal information stored by Presight?

 Q3: Does Presight share personal data with third parties?

 Q4: How can I access the personal information that Presight holds about me?

2. Data Security and Safety

 Q5: What measures does Presight take to ensure data security?

 Q6: Is my data encrypted during transmission and storage?

 Q7: What does Presight do in case of a data breach?

3. Data Collection and Retention

 Q8: What types of data does Presight collect from users?

 Q9: How long does Presight retain my data after my account is deactivated?

 Q10: Is my data used to train AI or machine learning models?

4. Cookies and Third-Party Websites

 Q11: How does Presight use cookies on its website?

 Q12: Can I control the use of cookies on the Presight website?

 Q13: Is Presight responsible for privacy practices on third-party websites?

5. Policy Updates and Changes

 Q14: How are updates to the Privacy Policy communicated to users?

 Q15: How can I know when Presight’s Privacy Policy has been updated?

6. Contact and Support

 Q16: What email can I use to contact Presight about the Privacy Policy?

 Q17: How can I reach Presight if I have concerns about my personal data?

7. User Responsibilities and Rights

 Q18: What responsibilities do users have in maintaining the accuracy of their personal data?

 Q19: Does Presight allow users to correct inaccurate data?

