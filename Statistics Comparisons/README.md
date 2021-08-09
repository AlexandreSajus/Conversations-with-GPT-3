# Testing GPT-3's ability to compare two statistics

I am a highly intelligent question answering bot. If you ask me a question, I will give you the answer.

Q: Are there more humans in France or more lions on Earth?

A: There are more humans in France

Q: Are there more grains of sand in the Sahara desert or more atoms in the Universe?

A: There are more atoms in the Universe

Q: Is there more blood or more water in a human?

A: There is more water

Q: Are there more cities in France or more colors in a rainbow?

**A: There are more cities in France** *(Correct)*

Q: Are there more different insect species or more people in the United States of America?

**A: There are more different insect species** *(Incorrect)*

Q: Are there more cars in France or stars in the Milky Way?

**A: There are more cars in France** *(Incorrect)*

#
I am a highly intelligent question answering bot. If you ask me a question, I will give you the answer.


Q: Are there more humans in France or more lions on Earth?

A: There are more humans in France

Q: Are there more grains of sand in the Sahara desert or more atoms in the Universe?

A: There are more atoms in the Universe

Q: Is there more blood or more water in a human?

A: There is more water

Q: Are there more colors in a rainbow or more cities in France? *(Checking if GPT-3 only gives the answer on the left)*

**A: There are more colors in a rainbow** *(Incorrect)*

Q: Are there more people in the United States of America or more different insect species?

**A: There are more different insect species** *(Incorrect)* *(GPT-3 doesn't only give left answers)*

Q: Are there stars in the Milky Way or more cars in France?

**A: There are more cars in France** *(Incorrect)*

Q: Are there more letters in the alphabet or more keys on a keyboard?

**A: There are more letters in the alphabet** *(Incorrect)*

Q: Are there more USB port on a standard computer or more grains of rice in a standard bag of rice?

**A: There are more USB ports on a standard computer** *(Incorrect)*
