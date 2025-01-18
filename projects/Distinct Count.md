---
layout: project
type: project
image: img/micromouse/console.png
title: "Distinct Counts"
date: 2024
published: true
labels:
  - C
  - CLion
summary: "A project I made that counts the specific distinct letters in a sentence."
---

<div class="text-center p-4">
  <img width="200px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Clion.svg/1200px-Clion.svg.png" >
</div>

The Distinct count program was a project that I produced in ICS 212 during my first semester as a sophomore in UH Manoa. The goal of this project was to be able to produce a list that defines the number of distinct letters for a sentence typed by the user.

Out of the other programs that I had coded for the duration of the course, this specific program stood out to me more in that I was able to produce C code much more efficiently as well as utilizing the command prompt to run the program. 

A sample of the code in the program can be viewed below:

```c
void countCharacters(int letters[]) {
int character;

//Acts like a scanner function; Goes through each character in the line until EOF.
//For both uppercase and lowercase, as long as the characters are within range of a - z,
//the value for that index will increment by 1. Any special case characters are ignored.
while ((character = getchar()) != EOF) {

  if (character >= 'a' && character <= 'z') {
    letters[character - 'a']++;
}
  if (character >= 'A' && character <= 'Z') {
    letters[character - 'A']++;
    }
  }
 }
```

My project can be found in my GitHub here: [Distinct Letter Count Program](https://github.com/danny-ngo-2005/programs-from-class/blob/main/distinctalphabets.c).
