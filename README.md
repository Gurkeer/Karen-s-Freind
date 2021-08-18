<h1>ProGrad</h1>

## LAB | Text Adventure

This is a short story about a girl named Karen and her friend. Run `index.html` to view the story. You will see that the story is incomplete. On finishing each _Trial_, a part of the story will be unlocked. Go to the `src/app.js` file and complete all the unfinished code to find out how this story ends.

## Requirements

- Fork this repo
- Clone this repo
- Practice JavaScript Basics - _datatypes, operators, conditions_

## Submission

- Upon completion, run the following commands:

  ```
  git add .
  git commit -m "done"
  git push origin master
  ```

- Create Pull Request so your TAs can check up your work.

### Tests

Open the `SpecRunner.html` file on your browser and start coding to pass the test. Remember to focus on one test at a time and read carefully the instructions to understand what you have to do.

## Trial 1: Home Sweet Home

We've got some basic information about Karen's home. Find out the type of each data. Create a function `moreAboutHome()` which takes `address, distanceFromTown, hasNeighbours` as arguments and _returns all datatypes concatenated in a single variable_.

## Trial 2: My name is Karen

Now, we're given some more information about Karen's family. Create a function `moreAboutKaren()` that takes `parents, noOfSiblings, isNuclearFamily` as arguments. Check if the arguments passed are of the datatypes `String, Number, Boolean` respectively and _return true/false_ accordingly.

## Trial 3: Karen's new friend

Karen says she's made a new friend but Lily doesn't believe her just yet. create a function `doesFriendExist()` that takes `ageInText, ageInNumber` as arguments. It checks which of the given value is `NaN` and _returns the value_.

## Trial 4: Lily's investigation

Lily game Karen some sweets in order to calm her down so she could follow her. Lily has a sweet tooth and couldn't resist the temptation. She ate a lot of sweets on her way to the river.

- Lily gave Karen x sweets
- Karen ate y sweets herself
- She ate another z sweets every n meters travelled
- Her friend divided the remaining sweets into 2 parts for each.

  Create a function `sweetTooth()` which takes `totalNoOfSweets, sweetsConsumedByKaren, sweetsConsumedInNMeters, metersToTravel` as arugments and _return number of sweets Karen's friend would have_.

## Trial 5: Haunting discovery

Lily stalks Karen slowly, making sure to not alert her. Suddenly, a gust of wind sends a chilld down her spine. She feels the temperature dropping and checks her phone. It displays the temperature in fahrenheit. Create a function `convertToCelsius()` which takes an argument `fahrenheit` and _returns the temperature in celcius_.

## Trial 6: Rising paranoia

Lily starts panicking once she reaches. She feels there's something wrong with her and requires immediate medical attention. She cannot decide what to do next. How to fix this without hurting her child any further. Create a function `aDifficultChoice()` which takes an argument `choice` and _returns the corresponding choice_.

## Challenge 1: Console Karen

Lily's actions had a negative effect of Karen and now she's drifted further away. Lily realizes that she must do something immediately to console her daughter. She thinks of a couple of strategies that might help. Create a function `consoleKaren()` which takes an argument `strategies` and _returns a concatenated string of strategies_. Each strategy is seperated by a space.

_Inspired by [Mysterious Friend](https://yourstoryclub.com/short-stories-unusual-experience/thriller-short-story-mysterious-friend/) - yourstoryclub.com_
