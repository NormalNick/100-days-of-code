# 100 Days Of Code - Log

### Day 1: Jan 04, 2017
**Today's Progress**: 
Find the Longest Word in a String	Jan 04, 2017		View solution
Title Case a Sentence	Jan 04, 2017		View solution

**Thoughts**: 

**Link(s) to work**: 
[Find the Longest Word in a String](https://www.freecodecamp.com/challenges/Find%20the%20Longest%20Word%20in%20a%20String?solution=%0Afunction%20findLongestWord(str)%20%7B%0A%20%20var%20words%3Dstr.split(%22%20%22)%3Bconsole.log(%22words%3D%22%2Cwords)%20%0A%20%20var%20longestWord%3Dwords%5B0%5D%3B%0A%20%20var%20longestWordLength%3Dwords%5B0%5D.length%3B%0A%20%20for%20(i%20%3D%201%3B%20i%3C%3Dwords.length-1%3B%20i%2B%2B)%20%7B%0A%20%20%20%20if%20(words%5Bi%5D.length%20%3E%20longestWordLength)%20%7B%0A%20%20%20%20%20%20longestWordLength%3Dwords%5Bi%5D.length%3B%0A%20%20%20%20%20%20longestWord%3Dwords%5Bi%5D%3B%0A%20%20%20%20%20%20%20%20%20%20console.log(longestWordLength%2C%20longestWord)%3B%0A%0A%20%20%20%20%7D%0A%20%20%7D%0A%20%20%20%20%0A%20%20return%20longestWordLength%3B%0A%7D%0A%0AfindLongestWord(%22The%20quick%20brown%20fox%20jumped%20over%20the%20lazy%20dog%22)%3B%0A)
[Title Case a Sentence](https://www.freecodecamp.com/challenges/Title%20Case%20a%20Sentence?solution=%0Afunction%20titleCase(str)%20%7B%0A%20%20words%3Dstr.split(%22%20%22)%3Bconsole.log(%22words%3D%22%2C%20words)%3B%0A%0A%20%20var%20titleCased%20%3D%20titleCaseWord(words%5B0%5D)%3B%0A%20%20for%20(i%3D1%3Bi%3Cwords.length%3Bi%2B%2B)%20%7B%0A%20%20%20%20titleCased%20%3D%20titleCased%20%2B%20%22%20%22%20%2B%20titleCaseWord(words%5Bi%5D)%3B%0A%20%20%20%20%0A%20%20%7D%0A%20%20console.log(%22titleCased%3D%22%2CtitleCased)%3B%0A%20%20return%20titleCased%3B%0A%7D%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%0Afunction%20titleCaseWord(str)%20%7B%0A%20%20str%3Dstr.toLowerCase()%3B%0A%20%20letters%20%3D%20str.split(%22%22)%3B%20%2F%2Fstring%20of%20letters%0A%20%20console.log(%22letters%3D%22%2Cletters)%3B%0A%20%20%20%20%20%20return%20letters%5B0%5D.toUpperCase()%20%2B%20str.substr(1)%3B%0A%20%20%20%20%7D%0A%0AtitleCase(%22I%27m%20a%20little%20tea%20pot%22)%3B%0A)

### Day 2: Jan 11, 2017
##### (delete me or comment me out)

**Today's Progress**: Got setup on my Surface. Installed VS Code. Installed Git. Cloned 100days repo. 

**Thoughts:** I don't have a mouse hooked up, which makes it more difficult to actually type. Using touch is too difficult

**Link to work:** 

### Day x: 
##### (delete me or comment me out)

**Today's Progress**: 

**Thoughts**: 

**Link(s) to work**: 


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)
