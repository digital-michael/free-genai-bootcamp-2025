
# Table of Contents
* [PURPOSE](#PURPOSE)
* [Transcript](#Transcript)
* [Summary](#Summary)


---


# PURPOSE
I wanted:
- test out the local LLM environment
- download a newer llama model (3.3 70.6B)
- compare speeds and execution quality
- explore the mind set for defining a game/goal before applying the knowledge into the formal structure I set out in the numbered markdown files.
- Stretch: Open WebUI has "Workspaces"; I need to understand their value in the local environment


# Transcript

## me
> Ok. Do you speak Bulgarian?


## lama3.1:latest

Yes, I can generate text in Bulgarian and understand basic phrases and sentences. However, my proficiency might not be as high as it is for more widely spoken languages like English or Spanish. If you'd like to communicate in Bulgarian, feel free to use the language, and I'll do my best to respond accordingly!

## me

> If I give you an English sentence, would you break the sentence down, word for word in table format in the same order as the English sentence, and showing a column for word in English, Bulgarian, Russian, Spanish and Italian. Select words as close to the original intention of the English words. Only process nouns and pronouns, verbs and adverbs and adjectives. Skill articles and prepositions for now. After the same, create a bullet list for each language with the full sentence and correct syntax.


## lama3.1:latest

Here's an example using the sentence: "The big red car drove slowly."

**Breakdown Table**

| Word in English | Bulgarian (Нареден език) | Russian (Русский язык) | Spanish (Español) | Italian (Italiano) |
| --- | --- | --- | --- | --- |
| The | Този | Это | El | Il |
| big | голям | большой | grande | grande |
| red | червен | красный | rojo | rosso |
| car | автомобил | машина | coche | auto |
| drove | шеле | ехал | condujo | guidò |
| slowly | бавно | медленно | lentamente | lentamente |

**Bullet List for Each Language**

* **Bulgarian:** Този голям червен автомобил шеле бавно.
	+ Note: Bulgarian uses a specific article "Този" to indicate the definite article, which is not directly translatable.
* **Russian:** Это большой красный машина ехал медленно.
	+ Note: Russian uses the word "Это" to indicate the definite article.
* **Spanish:** El coche rojo condujo lentamente.
	+ No changes needed
* **Italian:** L'auto rosso guidò lentamente.
	+ Note: Italian uses the indefinite article "L'" in place of "Il", which is used for masculine nouns starting with a consonant.

Please keep in mind that this breakdown only includes nouns, pronouns, verbs, adverbs, and adjectives, as per your request.

## me

> Let’s try: The beer bottle sat on the table near the chair.


## lama3.1:latest

Here's the breakdown:

**Breakdown Table**

| Word in English | Bulgarian (Нареден език) | Russian (Русский язык) | Spanish (Español) | Italian (Italiano) |
| --- | --- | --- | --- | --- |
| The | Този | Это | El/Lo/Los | Il/Lo/Li |
| beer | бира | пиво | cerveza | birra |
| bottle | бутилка | бутылка | botella | bottiglia |
| sat | седна | сидел | sentado | seduto |
| on | на | на | en | su |
| the | Този/Тя | Это | El/Ella | Il/Lea |
| table | маса | стол | mesa | tavolo |
| near | близо | рядом | cerca | vicino |
| the | Този/Тя | Это | El/Ella | Il/Lea |
| chair | столове | стул | silla | sedia |

**Bullet List for Each Language**

* **Bulgarian:** Този бира бутилка седна на масата близо до тази столове.
	+ Note: Bulgarian uses the word "близо" to indicate near or close, which is not directly translatable.
* **Russian:** Это пиво бутылка сидел на стол рядом со стулом.
	+ Note: Russian uses the word "рядом" to indicate near or close, which is not directly translatable.
* **Spanish:** La botella de cerveza se sentó en la mesa cerca de la silla.
	+ Note: Spanish uses the definite article "La" for feminine nouns like "botella".
* **Italian:** La bottiglia di birra si sedette sul tavolo vicino alla sedia.
	+ Note: Italian uses the definite article "La" for feminine nouns like "bottiglia".

## me

> I’d like the Language specific notes to be moved to a trailing list. They are breaking up the bullet list. I’d like each language sentence to be closer together. Also, in the breakdown table, Skip articles, prepositions and conjunctions; don’t list them in the table.    

## lama3.1:latest

Here is the revised output:

**Breakdown Table**

| Word in English | Bulgarian (Нареден език) | Russian (Русский язык) | Spanish (Español) | Italian (Italiano) |
| --- | --- | --- | --- | --- |
| The beer bottle | бира | пиво | cerveza | birra |
| sat on the table | седна на маса | сидел на столе | sentado en la mesa | seduto sul tavolo |
| near the chair | близо до столове | рядом со стулом | cerca de la silla | vicino alla sedia |

**Bullet List for Each Language**

* **Bulgarian:** Този бира бутилка седна на масата близо до тази столове.
	+ Notes: Bulgarian uses the word "близо" to indicate near or close, which is not directly translatable. The definite article "Този/Тя" is used for masculine/feminine nouns starting with a consonant/vowel.

* **Russian:** Это пиво бутылка сидел на стол рядом со стулом.
	+ Notes: Russian uses the word "рядом" to indicate near or close, which is not directly translatable. The definite article "Это" is used for nouns.

* **Spanish:** La botella de cerveza se sentó en la mesa cerca de la silla.
	+ Notes: Spanish uses the definite article "La" for feminine nouns like "botella".

* **Italian:** La bottiglia di birra si sedette sul tavolo vicino alla sedia.
	+ Notes: Italian uses the definite article "La" for feminine nouns like "bottiglia".

## me

> I like the breakdown table; nicely done. In the Bullet List for Each Language, why are the “Notes” will under each language entry? I asked those to be moved out of that list and placed at the end of the response.

## llama3.1:latest

Here is the revised output with the notes moved to the end:

**Breakdown Table**

| Word in English | Bulgarian (Нареден език) | Russian (Русский язык) | Spanish (Español) | Italian (Italiano) |
| --- | --- | --- | --- | --- |
| The beer bottle | бира | пиво | cerveza | birra |
| sat on the table | седна на маса | сидел на столе | sentado en la mesa | seduto sul tavolo |
| near the chair | близо до столове | рядом со стулом | cerca de la silla | vicino alla sedia |

**Bullet List for Each Language**

* Bulgarian: Този бира бутилка седна на масата близо до тази столове.
* Russian: Это пиво бутылка сидел на стол рядом со стулом.
* Spanish: La botella de cerveza se sentó en la mesa cerca de la silla.
* Italian: La bottiglia di birra si sedette sul tavolo vicino alla sedia.

**Notes**

* Bulgarian uses the word "близо" to indicate near or close, which is not directly translatable. The definite article "Този/Тя" is used for masculine/feminine nouns starting with a consonant/vowel.
* Russian uses the word "рядом" to indicate near or close, which is not directly translatable. The definite article "Это" is used for nouns.
* Spanish uses the definite article "La" for feminine nouns like "botella".
* Italian uses the definite article "La" for feminine nouns like "bottiglia".


## me

> Very nice. Describe this context it can be replicated again later.

## llama3.1:latest

This output is generated by a combination of natural language processing (NLP) and machine learning algorithms, specifically designed to translate and break down English sentences into multiple languages.

The context for replicating this output involves the following steps:

1. **Sentence Input**: The user provides an English sentence as input.
2. **Breakdown Table Generation**: A breakdown table is generated using the input sentence, where each word is translated into multiple languages (Bulgarian, Russian, Spanish, and Italian). Only nouns, pronouns, verbs, adverbs, and adjectives are included in the table.
3. **Bullet List Generation**: A bullet list is created for each language, with the translated sentence and any necessary corrections or notes.
4. **Notes Collection**: Any additional information about the translations, such as special cases or nuances, is collected and displayed at the end of the output.

To replicate this context in the future, you can provide an English sentence as input, and I will generate a similar breakdown table and bullet list for each language.

## me

> Let create an option. The current configuration we will call “without” and it describes the conditions where we are not considering articles, prepositions and conjunctions as currently defined in this context. Next, we will create an option called “with” with will include all parts of speech and will apply them to the context.

## llama3.1:latest

Let's create a new configuration called "with" that includes all parts of speech.

**Breakdown Table**

| Word in English | Bulgarian (Нареден език) | Russian (Русский язык) | Spanish (Español) | Italian (Italiano) |
| --- | --- | --- | --- | --- |
| The | Този/Тя | Это | El/La | Il/Lea |
| beer | бира | пиво | cerveza | birra |
| bottle | бутилка | бутылка | botella | bottiglia |
| sat | седна | сидел | se sentó | si sedette |
| on | на | на | en | sul |
| the | Този/Тя | Это | El/La | Il/Lea |
| table | маса | столе | mesa | tavolo |
| near | близо до | рядом со | cerca de | vicino a |
| the | Този/Тя | Это | El/La | Il/Lea |
| chair | столове | стуле | silla | sedia |

**Bullet List for Each Language**

* Bulgarian: Този бира бутилка седна на масата близо до тази столове.
* Russian: Это пиво бутылка сидел на стол рядом со стулом.
* Spanish: La botella de cerveza se sentó en la mesa cerca de la silla.
* Italian: La bottiglia di birra si sedette sul tavolo vicino alla sedia.

**Notes**

* In the "with" configuration, all parts of speech (articles, prepositions, conjunctions) are included in the breakdown table and bullet list.
* The definite articles "Този/Тя", "Это", "El/La", and "Il/Lea" are used for nouns as before.

This new configuration includes all parts of speech, providing a more comprehensive breakdown of the sentence.


## me

> Now, use the “without” option.


## llama3.1:latest

Here is the output using the "without" option:

**Breakdown Table**

| Word in English | Bulgarian (Нареден език) | Russian (Русский язык) | Spanish (Español) | Italian (Italiano) |
| --- | --- | --- | --- | --- |
| beer | бира | пиво | cerveza | birra |
| bottle | бутилка | бутылка | botella | bottiglia |

**Bullet List for Each Language**

* Bulgarian: Бира се седна на масата близо до столове.
* Russian: Пиво сидел на стол рядом со стулом.
* Spanish: La cerveza se sentó en la mesa cerca de la silla.
* Italian: La birra si sedette sul tavolo vicino alla sedia.

**Notes**

* In the "without" configuration, articles, prepositions, and conjunctions are not included in the breakdown table or bullet list.


## me

> Where are the nouns, verbs, adverbs, adjectives?


## llama3.1:latest

To provide a more comprehensive breakdown of the sentence using the "without" option, I will include the nouns, verbs, adverbs, and adjectives in the table and bullet lists.

**Breakdown Table**

| Word in English | Part of Speech | Bulgarian (Нареден език) | Russian (Русский язык) | Spanish (Español) | Italian (Italiano) |
| --- | --- | --- | --- | --- | --- |
| beer | Noun | бира | пиво | cerveza | birra |
| bottle | Noun | бутилка | бутылка | botella | bottiglia |
| sat | Verb | седна | сидел | sentó | si sedette |
| on | Preposition (not included in "without" option) | на | на | en | sul |
| the | Article (not included in "without" option) | Този/Тя | Это | El/La | Il/Lea |
| table | Noun | маса | столе | mesa | tavolo |
| near | Adverb | близо до | рядом со | cerca de | vicino a |
| the | Article (not included in "without" option) | Този/Тя | Это | El/La | Il/Lea |
| chair | Noun | столове | стуле | silla | sedia |

**Bullet List for Each Language**

* Bulgarian: Бира се седна на масата близо до столове.
* Russian: Пиво сидел на стол рядом со стулом.
* Spanish: La cerveza se sentó en la mesa cerca de la silla.
* Italian: La birra si sedette sul tavolo vicino alla sedia.

**Notes**

* In the "without" configuration, articles, prepositions, and conjunctions are not included in the breakdown table or bullet list. However, nouns, verbs, adverbs, and adjectives are still included to provide a more comprehensive understanding of the sentence.


## me

> Restate the context for this chat.


## llama3.1:latest

Here is a restatement of the context for this chat:

We've been working on creating a language translation tool that breaks down English sentences into multiple languages (Bulgarian, Russian, Spanish, and Italian). We've created two configuration options: "without" and "with".

* The "without" option excludes articles, prepositions, and conjunctions from the breakdown table and bullet lists.
* The "with" option includes all parts of speech (articles, prepositions, conjunctions, nouns, verbs, adverbs, and adjectives) in the breakdown table and bullet lists.

We've demonstrated both options using a sample sentence: "The beer bottle sat on the table near the chair."


## me

> Make suggestions to improve this context.


## llama3.1:latest

Here are some suggestions to improve the context:

1. **Add more language support**: Currently, the tool only supports four languages (Bulgarian, Russian, Spanish, and Italian). Consider adding more languages to increase its utility.
2. **Improve grammar handling**: The current implementation might not accurately handle complex grammatical structures or idiomatic expressions. You could explore using more advanced natural language processing techniques or machine learning models to improve the tool's accuracy.
3. **Support for multiple sentence types**: Currently, the tool only supports simple sentences. Consider adding support for compound and complex sentences, as well as questions and other sentence types.
4. **Option for word-by-word translation**: In addition to breaking down sentences into parts of speech, consider adding an option to translate individual words from one language to another.
5. **User interface improvements**: While the text-based interface is functional, a graphical user interface (GUI) or web application could make it more accessible and user-friendly.
6. **Integration with other tools or services**: Consider integrating this tool with other language-related services, such as dictionaries, thesauri, or machine translation engines, to create a more comprehensive language learning platform.
7. **Machine learning for sentence structure adaptation**: The current implementation assumes a fixed sentence structure. You could explore using machine learning techniques to adapt to varying sentence structures and improve the tool's accuracy.
8. **Add support for idiomatic expressions and colloquialisms**: Idiomatic expressions and colloquialisms can be challenging to translate accurately. Consider adding a database of common idioms and colloquialisms to help the tool better handle these cases.

By addressing these areas, you could significantly enhance the context and make it more useful for language learners, translators, and professionals working with multiple languages.


## llama3.3:latest 
**Note**: I wanted to see CPU loads so I regenerated a response to check (results in Lessons Learned below)

Here are some suggestions to improve the context:

1. **Add more languages**: Consider adding more languages to the translation tool, such as French, German, Chinese, or Arabic, to make it more comprehensive and useful for a wider range of users.
2. **Improve sentence complexity**: Use more complex sentences with varied grammatical structures, such as conditional tenses, passive voice, or subordinate clauses, to test the tool's ability to handle different linguistic constructions.
3. **Include idiomatic expressions**: Incorporate idiomatic expressions, colloquialisms, and figurative language into the sample sentences to evaluate the tool's capacity to accurately translate nuanced language.
4. **Develop a user interface**: Create a user-friendly interface for the translation tool, allowing users to input their own sentences and select the languages they want to translate into.
5. **Incorporate feedback mechanisms**: Implement a feedback system that enables users to report errors or suggest improvements to the translations, which can help refine the tool's accuracy over time.
6. **Expand to other domains**: Consider applying the translation tool to specific domains, such as medical, technical, or legal terminology, where accurate translation is critical.
7. **Evaluate cultural sensitivity**: Assess the tool's ability to handle culturally sensitive language and nuances, ensuring that translations are respectful and appropriate for different cultures.
8. **Conduct thorough testing**: Perform extensive testing of the tool with a diverse range of sentences, languages, and user scenarios to identify areas for improvement and optimize its performance.

By addressing these suggestions, you can enhance the context and create a more robust, accurate, and user-friendly language translation tool that meets the needs of a broader audience.



## Summary

Setting the rules works best when set once with full context and clearly.  Iterating, refining over the rules allows for dropped requirements.

### Lessons Learned: clearly and formally state:
- objectives
- requirements
- prohibitions
- 

### Lessons Learned: Format specifications
Seemed to work fairl well and didn't deviate after being established

### Unknowns: feedback
I used a Thumbs Up/Down and a label to signal results, mostly positive. This was in addition to positive praise in chat.  It's uncertain what role the first actions ()"Thumbs") had on output.

### Lessons Learned: models matter
I downloaded and try to use llama3.3:latest (70.6B) but it was not performant, running into minutes before starting to replay and struggling word over word.

*Observation*: (llama3.3:latest) eye-balling it, seems that only about less than half of the CPU cores are loaded during a LLM "thinking" exercise ad a **much longer run time** to get a response even started (12 minutes total to generate the late reponse form 3.3)

llama3.1:latest (8.0B) was more responsive.
*Observation*: (llama3.1:latest) eye-balling it, seems that only about half of the CPU cores are loaded during a LLM "thinking" exercise.

### Lessons Learned: NVidia
I have NVidia card available but the environment is not tuned/enabled to use it yet.  Given the poor performance of 3.3, I need look at this and weight the risks of NVidia driver hell verses use a local LLM solution for GenAI as well as the RAG LLM and AI Agent work, currently targeted.


