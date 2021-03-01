# anki-templates
## Invisible clozes
This [Anki](https://apps.ankiweb.net/) card template allows making selected cloze deletions invisible (for examples see the use cases section).

### Use
- In the cloze style field, the visibility of all the clozes can be set using 1 (normal cloze) or 0 (invisible cloze), following the order in the text. The numbers need to be put together without any separator.
- All the clozes need to start with `{{c1::` (see restrictions)
- In case the cloze syle field is empty or has the wrong number of character, it is ignored and all clozes are displayed as normal.

### Installation
- Download and import the CustomClozes.apkg collection into your Anki installation.
- The imported folder which contains half a dozen sample cards can then be deleted. However, it might be a good idea to study them first to understand how the template works.
- The "CustomClozes" card type will be available when creating new cards.

### Restrictions and further possibilities
- This template doesn't currently work for notes with multiple cards (`c1`, `c2` etc.). This would be the next feature to implement.
- Using other numbers (or characters) than 1 or 0, additional cloze styles could be defined (e.g. bold but without the brackets etc.). I will do this when I have a use case for it (or upon request).
- In case you find other uses for this template, I would be happy to know!

### Possible use cases
1. **Words that influence other words:** The original problem solved by this template was cloze deletion of Welsh prepositions. Since the following noun's initial letter might change ("mutate") depending on the preposition, writing the noun in mutated form might give an unwanted hint towards the required preposition. But including the first letter of the noun in the blank just looks ugly and silly. With invisible blanks, a card could look like this:

![cael_gwared](https://user-images.githubusercontent.com/65987125/107576602-a7b6d680-6bf1-11eb-94c9-266f0ab5bef2.jpg)

2. **Words that get separated:** This is a classical situation with German composed verbs:

![mitbringen](https://user-images.githubusercontent.com/65987125/107578618-43e1dd00-6bf4-11eb-8127-d857a6879223.jpg) and
![aussehen](https://user-images.githubusercontent.com/65987125/107578636-480dfa80-6bf4-11eb-8d84-5aa3db3e8b3f.jpg)

3. **"Find the mistake" cards:** The mistake in a sentence can be hidden and revealed using an invisible cloze:

![cywira](https://user-images.githubusercontent.com/65987125/109553090-e0501e80-7ad2-11eb-9571-d82b51c680a6.jpg)

4. **Changing clause structure when connecting clauses:** This can be used for reported speech, but really for every subordinate clause that changes the word order or some of the words. A Welsh example:

![meddai_hi](https://user-images.githubusercontent.com/65987125/107578176-b1413e00-6bf3-11eb-8d29-8705746949b6.jpg) 

and one in German:

![mitsingen](https://user-images.githubusercontent.com/65987125/107578207-be5e2d00-6bf3-11eb-9eec-c602d21a32e5.jpg)

5. **Ablauts and other stem changes:** I haven't yet found an example for this that is actually useful, but in theory, you can do things like this:

![gesungen](https://user-images.githubusercontent.com/65987125/107578920-ad61eb80-6bf4-11eb-8ff4-480bfd77d285.jpg)
