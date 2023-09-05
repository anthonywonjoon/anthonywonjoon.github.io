---
layout: essay
type: essay
title: "BertErnie WOD Reflection"
# All dates must be YYYY-MM-DD format!
date: 2023-09-04
published: true
labels:
  - Engineering
  - Career
  - ICS314
---

## Preparing for and Performing the WOD

This past week, we took our first WOD. The ticking time, the pressure of looking at the clock, and the silence in the room as everyone is clacking away at their keyboard can be very stressful and make anyone crack. Luckily, the prompt was not too crazy as it was our first WOD. This was my first time doing WODs in a classroom setting, but I have done them in the past, in my ITM class, as well as the practice WODs from this class. Prepping by going over the material for that week was very helpful and a big key to succeeding.

## WOD Performance

My code for the prompt is below:
```
const bertErnie = function fourBertSixErnie(ceiling) {
    for (let i =  1; i < ceiling + 1; i++) {
        if (i % 4 === 0 && i % 6 === 0 ) { // if multiple of both 4 and 6
            console.log("BertErnie");
        }
        else if (i % 4 === 0) { // if multiple of 4
            console.log("Bert");
        }
        else if (i % 6 === 0) { // if multiple of 6
            console.log("Ernie");
        }
        else {
        console.log(i); // if not multiple of either, print
        }
    }
}

bertErnie(100);

```

From the start, the prompt looked familiar. It is, at its core, the [FizzBuzz problem](https://leetcode.com/problems/fizz-buzz/).

After discussion, I realised that I should have done this in two different ways: without the loop inside the function, or including a floor in the function. This would allow for the function to be modifiable without changing the actual function.

Below you can find a variation where the loop exists outside the function, allowing us full control of the floor and ceiling without worry of modifying the algorithm.

```
  const bertErnie = function fourBertSixErnie(counter) {
    if (counter % 4 === 0 && counter % 6 === 0) { console.log("BertErnie); }
    else if (counter % 4 === 0) { console.log("Bert); }
    else if (counter % 6 === 0) { console.log("Ernie); }
    else { console.log(counter); }
  }

  for (let i = 1; i <= 100; i++) {
    bertErnie(i);
  }
```

I did not struggle with the time limit, but I realised I should have used more of the time to go over the code that I had written rather than rushing to turn it in. I still had a lot of wiggle room to reach Rx (which I believe was 7 minutes).

The experience of doing these WODs are valuable because they reflect technical interviews: coding problems focused on finding an optimal algorithm and/or data structure in a limited amount of time. These WODs will prepare those of us planning on entering the Software Engineering field.

I think a big part of these WODs that are done in class are the discussions after. As in every field in the professional field and in academia, peer-reviews are a core part of growing. Being able to discuss what we thought of on our own, the pitfalls of some of our logic, and finally combining the strengths of our individual thoughts into one idea is the best way to keep growing. 
