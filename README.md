# NLP-Assignment
# 📘 Natural Language Processing (NLP) — Assignment

![NLP](https://img.shields.io/badge/Topic-Natural%20Language%20Processing-blue?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-success?style=for-the-badge)
![Format](https://img.shields.io/badge/Format-Short%20Answers-orange?style=for-the-badge)

## 🧭 Learning roadmap

1. NLP and text-data fundamentals
2. Text preprocessing and tokenization
3. Numerical text representations and similarity
4. Core NLP tasks
5. Chatbots and practical applications
6. Transformers and Large Language Models

## 📚 Questions and Answers

### 1. NLP and Text-Data Fundamentals

**Q1. What is NLP?**
- **Answer:** NLP (Natural Language Processing) is a field of AI that helps computers process and work with human language.
- **Example:** A chatbot answering a user's question.

**Q2. Why is NLP important in Artificial Intelligence?**
- **Answer:** NLP lets people interact with computers using everyday language.
- **Example:** A voice assistant understanding “Set an alarm.”

**Q3. Why is human language difficult for computers to understand?**
- **Answer:** Words can have different meanings depending on context, grammar, and usage.
- **Example:** “Bank” can mean a financial institution or the side of a river.

**Q4. What can happen if we use very large N-grams on small text data?**
- **Answer:** The feature space can become sparse and overfit because many sequences occur rarely.
- **Example:** A five-word phrase may appear only once in a small dataset.

**Q5. Why do we remove punctuation from text data?**
- **Answer:** It can reduce noise when punctuation is not useful for the task.
- **Example:** Removing commas before counting review words.

**Q6. Give some real-life examples of NLP.**
- **Answer:** NLP is used in chatbots, translation, spam filters, search, and sentiment analysis.
- **Example:** An email service identifying junk mail.

**Q7. Why do we remove stop words from text data?**
- **Answer:** Removing them can reduce feature count when common words add little value to the task.
- **Example:** Removing “the” from a keyword-search index.

**Q8. What is text data in NLP?**
- **Answer:** Text data is written language that an NLP system analyzes.
- **Example:** Customer reviews stored in a file.

**Q9. Why is text data important in NLP?**
- **Answer:** Text contains information that NLP can classify, search, summarize, or interpret.
- **Example:** Analyzing product reviews to find common complaints.

**Q10. What is the difference between structured and unstructured text data?**
- **Answer:** Structured data follows a fixed format; unstructured text has no consistent predefined layout.
- **Example:** A table of customer names is structured, while free-form reviews are unstructured.

**Q11. What are common problems found in raw text data?**
- **Answer:** Raw text may contain typos, extra spaces, inconsistent capitalization, emojis, and noisy symbols.
- **Example:** “ GREAT!!! ” contains extra spaces and punctuation.

**Q12. Why do we clean text data before using it in NLP?**
- **Answer:** Cleaning reduces irrelevant variation and makes text more consistent for analysis.
- **Example:** Removing extra spaces from a customer review.

### 2. Text Preprocessing

**Q13. What is the difference between Bag of Words and normal tokenization?**
- **Answer:** Tokenization splits text into tokens; Bag of Words converts those tokens into numerical counts.
- **Example:** Tokenization gives [“red”, “car”]; Bag of Words counts red: 1 and car: 1.

**Q14. What is tokenization in NLP?**
- **Answer:** Tokenization splits text into smaller units called tokens, such as words or sentences.
- **Example:** “I like NLP” becomes [“I”, “like”, “NLP”].

**Q15. What is lemmatization in NLP?**
- **Answer:** Lemmatization converts a word to its dictionary base form, called a lemma.
- **Example:** “cars” becomes “car”.

**Q16. Why do we use lemmatization in text preprocessing?**
- **Answer:** It groups grammatical forms while usually preserving valid words.
- **Example:** “running” may be reduced to “run”.

**Q17. What is the difference between stemming and lemmatization?**
- **Answer:** Stemming chops word endings; lemmatization aims to return a valid dictionary form.
- **Example:** Stemming may produce “studi”, while lemmatization returns “study”.

**Q18. Why does lemmatization need part of speech sometimes?**
- **Answer:** A word's base form can depend on its grammatical role in a sentence.
- **Example:** “saw” can be the past tense of “see” or a noun.

**Q19. Why is lemmatization useful in chatbot and search engine projects?**
- **Answer:** It can help match different grammatical forms of a word.
- **Example:** A search for “running” may also match “run”.

**Q20. What is lowercasing in NLP?**
- **Answer:** Lowercasing converts uppercase letters to lowercase to make text more consistent.
- **Example:** “HELLO” becomes “hello”.

**Q21. Why do we convert text into lowercase before NLP processing?**
- **Answer:** It reduces differences caused only by capitalization.
- **Example:** “Python” and “python” can be treated alike.

**Q22. Which Python method is used for lowercasing text?**
- **Answer:** Python strings provide the `lower()` method.
- **Example:** `nlp` returns `nlp`.

**Q23. What is the difference between \`Python\` and \`python\` before lowercasing?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q24. Why should we be careful while lowercasing words like \`US\` and \`Apple\`?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q25. What is the difference between tokenization and POS tagging?**
- **Answer:** Tokenization splits text into tokens; POS tagging labels each token's grammatical role.
- **Example:** “Dogs bark” becomes two tokens, then noun and verb tags.

**Q26. What is punctuation removal in NLP?**
- **Answer:** Punctuation removal deletes selected punctuation marks from text.
- **Example:** “Hello, world!” becomes “Hello world”.

**Q27. How can punctuation affect tokenization?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q28. Which Python module is useful for punctuation removal?**
- **Answer:** Python's `string` module provides `string.punctuation`, which can be used with `translate()`.
- **Example:** Use `str.maketrans('', '', string.punctuation)` to remove common punctuation.

**Q29. Why should we be careful while removing punctuation from emails and URLs?**
- **Answer:** Characters such as `@`, `.`, `/`, and `?` can be essential to email addresses and URLs.
- **Example:** Removing punctuation from `help@example.com` can damage the address.

**Q30. What is stemming in NLP?**
- **Answer:** Stemming cuts words down to a rough root form using rules.
- **Example:** “playing” may become “play”.

**Q31. Why do we use stemming in text preprocessing?**
- **Answer:** It groups related word forms and can reduce vocabulary size.
- **Example:** “connect”, “connected”, and “connecting” may be reduced to similar stems.

**Q32. Why can stemming sometimes produce words like \`studi\`?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q33. Where is stemming used in real-life NLP projects?**
- **Answer:** It is used in search and information retrieval when rough grouping of word forms is acceptable.
- **Example:** A search system matching “connect” with “connected”.

**Q34. What are stop words in NLP?**
- **Answer:** Stop words are very common words that some NLP tasks may not need.
- **Example:** “the”, “is”, and “and”.

**Q35. Give some examples of common stop words.**
- **Answer:** Common English stop words include “the”, “is”, “and”, and “of”.
- **Example:** “The cat is here” contains “the” and “is”.

**Q36. How does stop words removal help in text classification?**
- **Answer:** It may reduce unhelpful features, but should be tested because common words can carry meaning.
- **Example:** Removing “the” from product reviews before classification.

**Q37. What is a text cleaning pipeline in NLP?**
- **Answer:** A text cleaning pipeline is a sequence of steps that prepares text for analysis.
- **Example:** Lowercasing, tokenizing, and normalizing a review.

**Q38. Why is text cleaning important before NLP model training?**
- **Answer:** It helps reduce noise and keeps training data consistent.
- **Example:** Fixing inconsistent capitalization in reviews.

**Q39. What are the common steps in a text cleaning pipeline?**
- **Answer:** Common steps include handling missing values, normalizing text, tokenizing, and applying task-specific filtering.
- **Example:** Convert “ GREAT!!! ” to “great” when punctuation is not needed.

**Q40. Why should we be careful while removing stop words?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q41. What is the difference between raw text and cleaned text?**
- **Answer:** Raw text is the original input; cleaned text has selected noise or inconsistencies handled.
- **Example:** Raw: “Hello!!!”; cleaned: “hello”.

**Q42. Why is tokenization important before text processing?**
- **Answer:** It gives NLP tools manageable units to analyze.
- **Example:** Splitting a review into words before counting them.

**Q43. What is the difference between word tokenization and sentence tokenization?**
- **Answer:** Word tokenization splits text into words; sentence tokenization splits it into sentences.
- **Example:** “Hi there. Welcome!” becomes [“Hi there.”, “Welcome!”] with sentence tokenization.

**Q44. Why can punctuation create problems during tokenization?**
- **Answer:** Punctuation may attach to words or carry meaning, so careless splitting can create incorrect tokens.
- **Example:** “hello!” may be treated as “hello” plus “!”.

**Q45. Why is text cleaning important before topic modeling?**
- **Answer:** Noise and inconsistent word forms can obscure meaningful patterns.
- **Example:** Normalizing word forms can help theme discovery.

### 3. Numerical Text Representations and Similarity

**Q46. What is Bag of Words in NLP?**
- **Answer:** Bag of Words represents a document by counting vocabulary words, usually ignoring word order.
- **Example:** “cat cat dog” becomes cat: 2, dog: 1.

**Q47. Why do we convert text into numbers in NLP?**
- **Answer:** Most machine-learning algorithms need numerical features rather than raw words.
- **Example:** Representing a review as a vector before classification.

**Q48. What is vocabulary in Bag of Words?**
- **Answer:** Vocabulary is the set of unique terms collected from the text.
- **Example:** For “red car, blue car”, the vocabulary is red, car, and blue.

**Q49. What is the main limitation of Bag of Words?**
- **Answer:** It usually ignores word order and deeper meaning.
- **Example:** “dog bites man” and “man bites dog” can have the same word counts.

**Q50. What is cosine similarity in NLP?**
- **Answer:** Cosine similarity compares the angle between two nonzero numerical vectors.
- **Example:** Two documents with similar term patterns may score close to 1.

**Q51. Why do we convert text into vectors before using cosine similarity?**
- **Answer:** Cosine similarity operates on numerical vectors rather than raw text strings.
- **Example:** Convert two resumes to TF-IDF vectors before comparing them.

**Q52. What does a cosine similarity score close to \`1\` mean?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q53. What is the difference between cosine similarity and Euclidean distance?**
- **Answer:** Cosine similarity compares vector direction; Euclidean distance measures straight-line distance between vector points.
- **Example:** Vectors `[1, 2]` and `[2, 4]` point in the same direction but have different lengths.

**Q54. How is cosine similarity useful in resume screening and chatbot projects?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q55. What is GloVe in NLP?**
- **Answer:** GloVe learns word vectors using global word co-occurrence statistics.
- **Example:** It learns from how often “ice” and “cold” occur with related words.

**Q56. What is the full form of GloVe?**
- **Answer:** GloVe stands for Global Vectors for Word Representation.
- **Example:** A GloVe model maps “book” to a numerical vector.

**Q57. How does GloVe learn word meaning?**
- **Answer:** It uses patterns in how frequently words occur together across a text collection.
- **Example:** Repeated co-occurrence of “doctor” and “hospital” helps shape their vectors.

**Q58. What is the difference between GloVe and Word2Vec?**
- **Answer:** GloVe emphasizes global co-occurrence statistics; Word2Vec learns by predicting words from local context.
- **Example:** GloVe uses co-occurrence counts, while Skip-Gram predicts nearby words.

**Q59. Why can words like \`bank\` create problems for basic GloVe embeddings?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q60. What are N-grams in NLP?**
- **Answer:** N-grams are consecutive sequences of N tokens.
- **Example:** “machine learning model” contains the bigram “machine learning”.

**Q61. What is the difference between unigram, bigram, and trigram?**
- **Answer:** A unigram has one token, a bigram has two consecutive tokens, and a trigram has three.
- **Example:** In “I like NLP”, “I” is a unigram, “I like” a bigram, and “I like NLP” a trigram.

**Q62. Why are N-grams useful in sentiment analysis?**
- **Answer:** They preserve short word sequences that can reveal meaning.
- **Example:** The bigram “not good” signals negative sentiment.

**Q63. How are N-grams different from Bag of Words?**
- **Answer:** N-grams define token sequences used as features; Bag of Words counts features and can use unigram or N-gram features.
- **Example:** A Bag of Words model using bigrams can count “very good”.

**Q64. What is the role of TF-IDF in spam detection?**
- **Answer:** TF-IDF can represent messages as weighted word features for a classifier.
- **Example:** The phrase “claim reward” contributes features to a spam model.

**Q65. Why do we convert text into numbers before classification?**
- **Answer:** A classifier needs numerical features to learn patterns from text.
- **Example:** TF-IDF features train a spam classifier.

**Q66. What is text similarity in NLP?**
- **Answer:** Text similarity estimates how alike two pieces of text are by words or meaning.
- **Example:** Comparing a question with FAQ answers.

**Q67. What is cosine similarity?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q68. What is the difference between lexical similarity and semantic similarity?**
- **Answer:** Lexical similarity compares shared words; semantic similarity compares meaning.
- **Example:** “car” and “automobile” share little exact wording but have similar meanings.

**Q69. How is text similarity useful in resume screening and chatbot projects?**
- **Answer:** It can rank resumes against job descriptions or retrieve relevant answers.
- **Example:** A system ranks a resume with Python experience higher for a Python role.

**Q70. What is TF-IDF in NLP?**
- **Answer:** TF-IDF weights a term by its frequency in a document and how uncommon it is across documents.
- **Example:** “turbocharger” may be more informative than “the” in a technical report.

**Q71. What is the difference between TF and IDF?**
- **Answer:** TF measures a term's frequency in a document; IDF reduces the weight of terms common across documents.
- **Example:** “engine” appearing often in one report can have high TF.

**Q72. Why does TF-IDF give low value to common words?**
- **Answer:** Words appearing in many documents are usually less useful for distinguishing documents.
- **Example:** “the” often has a lower IDF than “turbocharger”.

**Q73. What is the difference between Bag of Words and TF-IDF?**
- **Answer:** Bag of Words usually uses counts; TF-IDF weights terms by how informative they are across documents.
- **Example:** “the” may count in Bag of Words but receive a low TF-IDF weight.

**Q74. Why is TF-IDF useful in search engines and resume screening?**
- **Answer:** It highlights terms that help distinguish one document from others.
- **Example:** A resume mentioning “Python” can match a Python-focused job description.

**Q75. What are word embeddings in NLP?**
- **Answer:** Word embeddings are dense numerical vectors that represent words and can capture usage patterns.
- **Example:** “king” and “queen” may have nearby vectors.

**Q76. Why do we convert words into vectors?**
- **Answer:** Vectors let models calculate patterns, relationships, and similarity numerically.
- **Example:** Comparing vectors for “doctor” and “nurse”.

**Q77. What is the difference between one-hot encoding and word embeddings?**
- **Answer:** One-hot encoding uses a mostly-zero vector for each word; embeddings use dense learned vectors.
- **Example:** A four-word vocabulary can encode “cat” as `[1, 0, 0, 0]`.

**Q78. What is Word2Vec?**
- **Answer:** Word2Vec learns word vectors from patterns in surrounding words.
- **Example:** It may learn that “coffee” appears near “cup” and “drink”.

**Q79. Why can the word \`bank\` be difficult for normal word embeddings?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q80. What is Word2Vec in NLP?**
- **Answer:** Word2Vec is a method for learning word embeddings from local context.
- **Example:** It learns a vector for “coffee” based on words around it.

**Q81. What is the difference between CBOW and Skip-Gram?**
- **Answer:** CBOW predicts a target word from context; Skip-Gram predicts context words from a target word.
- **Example:** CBOW uses “I ___ tea” to predict “drink”.

**Q82. Why does Word2Vec check nearby words?**
- **Answer:** Words used in similar contexts often have related meanings or uses.
- **Example:** “tea” and “coffee” often appear near “drink”.

**Q83. What is one limitation of basic Word2Vec?**
- **Answer:** It generally gives each word one vector, even if the word has several meanings.
- **Example:** “bank” in “river bank” and “bank account” shares one basic vector.

### 4. Core NLP Tasks

**Q84. What is the difference between text classification and sentiment analysis?**
- **Answer:** Text classification is a broad method for assigning labels; sentiment analysis specifically identifies opinion or emotional polarity.
- **Example:** Classifying an email as spam is text classification, while labeling a review positive is sentiment analysis.

**Q85. What is language detection in NLP?**
- **Answer:** Language detection predicts which language a text is written in.
- **Example:** Identifying “Bonjour” as French.

**Q86. Why is language detection important in multilingual applications?**
- **Answer:** It helps an application choose suitable language-specific processing or responses.
- **Example:** A support app routes a Spanish question to a Spanish workflow.

**Q87. How does language detection help chatbots?**
- **Answer:** It can help a chatbot select a language model, response template, or translation step.
- **Example:** A bot responds in Marathi after detecting Marathi input.

**Q88. Why is mixed language text difficult for language detection?**
- **Answer:** A sentence may combine languages, scripts, abbreviations, and borrowed words.
- **Example:** “Kal meeting hai” mixes English and Hindi.

**Q89. What is the difference between language detection and translation?**
- **Answer:** Detection identifies a language; translation converts text from one language into another.
- **Example:** Detecting “Hola” as Spanish differs from translating it to “Hello”.

**Q90. What is machine translation in NLP?**
- **Answer:** Machine translation automatically converts text from one language into another.
- **Example:** Translating “Good morning” into Hindi.

**Q91. Why is machine translation useful?**
- **Answer:** It helps people communicate and access information across language barriers.
- **Example:** Translating a product manual for international customers.

**Q92. What is the difference between rule-based translation and neural machine translation?**
- **Answer:** Rule-based systems use language rules and dictionaries; neural systems learn translation patterns from data.
- **Example:** A neural system translates a full sentence using learned context.

**Q93. Why is context important in machine translation?**
- **Answer:** A word's correct translation can depend on its meaning in a sentence.
- **Example:** “Light bag” and “light the lamp” use “light” differently.

**Q94. What are some challenges in translating mixed-language text?**
- **Answer:** Mixed scripts, slang, spelling variations, and language switching can confuse translation systems.
- **Example:** “Please jaldi reply karo” combines English and Hindi.

**Q95. What is Named Entity Recognition in NLP?**
- **Answer:** NER finds named entities such as people, organizations, locations, dates, and money amounts.
- **Example:** NER identifies “Pune” as a location in “I work in Pune”.

**Q96. What are common entity types in NER?**
- **Answer:** Common types include person, organization, location, date, time, and money.
- **Example:** “OpenAI” can be tagged as an organization.

**Q97. What is the difference between POS tagging and NER?**
- **Answer:** POS tagging labels grammatical roles; NER identifies real-world entities.
- **Example:** “Microsoft” can be a proper noun and an organization entity.

**Q98. How is NER useful in resume screening and news analysis?**
- **Answer:** It can extract skills, organizations, dates, people, and locations for later processing.
- **Example:** Extracting an employer name and employment dates from a resume.

**Q99. What is Parts of Speech Tagging in NLP?**
- **Answer:** POS tagging assigns grammatical labels such as noun, verb, adjective, or adverb to tokens.
- **Example:** In “Birds fly”, “Birds” is a noun and “fly” is a verb.

**Q100. Why is POS tagging important in NLP?**
- **Answer:** It helps systems understand the grammatical role of words in context.
- **Example:** A parser uses POS tags to analyze a sentence.

**Q101. What is the difference between noun and verb?**
- **Answer:** A noun names a person, place, thing, or idea; a verb expresses an action or state.
- **Example:** In “The driver stops”, “driver” is a noun and “stops” is a verb.

**Q102. How can the same word have different POS tags in different sentences?**
- **Answer:** Its grammatical role depends on how it is used in the sentence.
- **Example:** “I book a ticket” uses “book” as a verb; “Read the book” uses it as a noun.

**Q103. What is the use of sentiment analysis in business?**
- **Answer:** It helps teams monitor customer satisfaction and identify recurring issues.
- **Example:** Analyzing reviews to find complaints about late delivery.

**Q104. What is sentiment analysis in NLP?**
- **Answer:** Sentiment analysis identifies the opinion or emotional polarity expressed in text.
- **Example:** Classifying “The service was excellent” as positive.

**Q105. Why is sentiment analysis useful for businesses?**
- **Answer:** It helps summarize customer opinions from reviews, surveys, and social posts.
- **Example:** A company tracks negative comments about delivery delays.

**Q106. What is the difference between positive, negative, and neutral sentiment?**
- **Answer:** Positive expresses a favorable opinion, negative an unfavorable opinion, and neutral neither clearly.
- **Example:** “The package arrived” is generally neutral.

**Q107. Why is the word \`not\` important in sentiment analysis?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q108. What are some challenges in sentiment analysis?**
- **Answer:** Sarcasm, context, mixed opinions, slang, and negation make sentiment difficult to detect.
- **Example:** “Great, another delay” may be sarcastic.

**Q109. What is spam detection in NLP?**
- **Answer:** Spam detection identifies unwanted or deceptive messages from their text and other signals.
- **Example:** Flagging a fraudulent prize message.

**Q110. Why is spam detection important in email and SMS systems?**
- **Answer:** It helps protect users from unwanted messages, scams, and phishing attempts.
- **Example:** Filtering a fake bank-alert SMS.

**Q111. How does Machine Learning help in spam detection?**
- **Answer:** It learns patterns from labeled spam and legitimate messages to classify new messages.
- **Example:** Training a classifier on examples of spam emails.

**Q112. What is the difference between false positive and false negative in spam detection?**
- **Answer:** A false positive marks a legitimate message as spam; a false negative lets spam pass as legitimate.
- **Example:** A work email sent to the spam folder is a false positive.

**Q113. What is text classification in NLP?**
- **Answer:** Text classification assigns text to one or more predefined categories.
- **Example:** Classifying a review as positive or negative.

**Q114. What is the difference between binary classification and multi-class classification?**
- **Answer:** Binary classification has two possible classes; multi-class classification has more than two.
- **Example:** Spam/not spam is binary; sports/business/technology is multi-class.

**Q115. Why is spam detection considered a text classification problem?**
- **Answer:** Messages are assigned labels such as spam or legitimate.
- **Example:** Labeling “Claim your prize now” as spam.

**Q116. Which algorithms are commonly used for text classification?**
- **Answer:** Common algorithms include Naive Bayes, Logistic Regression, Support Vector Machines, and neural networks.
- **Example:** A Naive Bayes model labels emails as spam or not spam.

**Q117. What is text summarization in NLP?**
- **Answer:** Text summarization creates a shorter version that preserves important information.
- **Example:** Turning a long report into five key bullet points.

**Q118. Why do we use text summarization?**
- **Answer:** It helps people understand long documents faster.
- **Example:** Summarizing a lengthy news article.

**Q119. What is the difference between extractive and abstractive summarization?**
- **Answer:** Extractive summarization selects existing text; abstractive summarization generates a new concise version.
- **Example:** Extractive uses a key sentence, while abstractive rewrites it briefly.

**Q120. Why can text summarization be difficult for long documents?**
- **Answer:** A system may miss distant relationships, key details, or contradictions across sections.
- **Example:** A summary of a long report may omit an important exception.

**Q121. How is text summarization useful in news apps and business reports?**
- **Answer:** It provides quick overviews of lengthy information.
- **Example:** Showing a short summary above a full news story.

**Q122. What is topic modeling in NLP?**
- **Answer:** Topic modeling discovers recurring themes across a collection of documents.
- **Example:** Finding themes such as pricing and delivery in customer reviews.

**Q123. Why do we use topic modeling?**
- **Answer:** It helps explore large text collections without manually labeling every document.
- **Example:** Discovering common themes in thousands of support tickets.

**Q124. What is LDA in topic modeling?**
- **Answer:** Latent Dirichlet Allocation (LDA) is a probabilistic model that represents documents as mixtures of topics.
- **Example:** A review may contain both delivery and product-quality topics.

**Q125. What is the difference between topic modeling and text classification?**
- **Answer:** Topic modeling discovers themes without predefined labels; classification predicts predefined categories.
- **Example:** LDA discovers review themes, while a classifier labels reviews as complaints.

### 5. Chatbots and Practical Applications

**Q126. What is a chatbot?**
- **Answer:** A chatbot is software that interacts with people through text or voice.
- **Example:** A website bot answers questions about shipping.

**Q127. Why do we use chatbots in websites and apps?**
- **Answer:** They answer common questions quickly and can provide support at any time.
- **Example:** A banking app bot explains how to reset a PIN.

**Q128. What is the difference between rule-based chatbot and AI-based chatbot?**
- **Answer:** Rule-based bots follow predefined rules; AI-based bots use models to interpret or generate responses.
- **Example:** A menu bot follows fixed options, while an AI bot handles varied wording.

**Q129. What is intent in chatbot development?**
- **Answer:** Intent is the goal or purpose behind a user's message.
- **Example:** “Book me a ticket” expresses a booking intent.

**Q130. Why is mixed-language text difficult for chatbots?**
- **Answer:** The bot may struggle with language switching, slang, spelling variations, and local expressions.
- **Example:** “Order track karna hai” mixes English and Hindi.

**Q131. How does a chatbot use NLP?**
- **Answer:** It processes a message to identify meaning, retrieve information, and create a response.
- **Example:** A support bot detects a refund request and shows refund steps.

**Q132. How is NLP used in Google Translate?**
- **Answer:** Translation systems use language-processing models to interpret input and generate text in another language.
- **Example:** Translating a sentence from English to Marathi.

**Q133. Why is NLP useful in spam email detection?**
- **Answer:** It helps analyze wording and patterns associated with unwanted or deceptive mail.
- **Example:** A model flags an email containing suspicious prize claims.

### 6. Transformers and Large Language Models

**Q134. What is a Large Language Model?**
- **Answer:** An LLM is a model trained on large amounts of text to predict and generate language.
- **Example:** An assistant drafts an email from a short instruction.

**Q135. Why are Large Language Models important in modern AI?**
- **Answer:** They can perform many language tasks from instructions and context.
- **Example:** An LLM summarizes meeting notes on request.

**Q136. What is the role of tokens in LLM?**
- **Answer:** Tokens are text units a model processes and generates; they may be words, parts of words, or characters.
- **Example:** “unbelievable” may be split into multiple tokens.

**Q137. What is the difference between NLP and LLM?**
- **Answer:** NLP is the broad field of language processing; an LLM is one type of model used for NLP tasks.
- **Example:** A TF-IDF spam filter is NLP but not an LLM.

**Q138. What are some limitations of Large Language Models?**
- **Answer:** They can produce incorrect claims, reflect bias, miss context, and lack knowledge of unseen events.
- **Example:** An LLM may confidently give an incorrect date.

**Q139. Why do we use NER in text processing?**
- **Answer:** It extracts important real-world names and facts from unstructured text.
- **Example:** Extracting company names from job advertisements.

**Q140. Why should we be careful while removing the word \`not\`?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q141. Why do we convert text into vectors before similarity checking?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q142. Why is basic \`split()\` not always enough for real NLP projects?**
- **Answer:** This concept describes a method or idea used to help computers process human language. The exact approach depends on the NLP task.
- **Example:** A text-processing system uses it while analyzing a sentence.

**Q143. What is a Transformer in NLP?**
- **Answer:** A Transformer is a neural-network architecture that uses attention to process relationships between tokens.
- **Example:** A Transformer helps generate an answer to a question.

**Q144. Why is attention important in Transformer architecture?**
- **Answer:** Attention lets the model weigh which other tokens are relevant to each token.
- **Example:** In “The animal was tired because it ran”, attention can help connect “it” with “animal”.

**Q145. What is self-attention?**
- **Answer:** Self-attention lets each token use information from other tokens in the same sequence.
- **Example:** The representation of “bank” can use surrounding words such as “river”.

**Q146. What is the difference between encoder and decoder?**
- **Answer:** An encoder builds representations of input; a decoder generates output, often one token at a time.
- **Example:** An encoder-decoder model translates English into French.

**Q147. Why are Transformer models important in modern AI systems?**
- **Answer:** They work well across many language tasks and underpin many modern language models.
- **Example:** A Transformer-based model answers questions about a document.

## ✅ Key Takeaways

- NLP helps computers process human language.
- Preprocessing makes text more consistent, but cleaning choices should match the task.
- Bag of Words, TF-IDF, and embeddings represent text numerically in different ways.
- NLP tasks include classification, sentiment analysis, NER, language detection, translation, summarization, and topic modeling.
- Transformers and LLMs support many modern AI applications, but their outputs should be checked.

---

If this README helps you, consider giving the repository a ⭐ on GitHub.
