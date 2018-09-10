---
layout: default
---

# What is prosody
**Prosody** can be defined as the additional information in a person's speech other than the actual content, for example: intonation and melody of a sentence, the rhythm, loudness, timbre, quality of the voice and much more.

When listening to prosody, we can understand the subtext of the sentence, for example:
1. Attitudes and intentions such as: irony, sarcasm, question, command
2. Emotional states of the speaker
3. Medical conditions such as neurological diseases
     
# What we are trying to do
We explore the question of is there a general method to determine **whether a feature is prosodic?**
We are trying to create a **"Prosodic language"** that can be a common ground to compare between different features and rank them according to the "amount" of prosodic information they carry.

# How does it sound
Here are some examples from our self-collected Hebrew data-bases of three different phrases with two types of prosodies: neutral and question:

<table>
  <tr>
       <td style="text-align: center; vertical-align: middle;">Speaker / Phrase</td>
       <td style="text-align: center; vertical-align: middle;">Prosody 1 <br> <b>Neutral</b> </td>
       <td style="text-align: center; vertical-align: middle;">Prosody 2 <br> <b>Question</b></td>
  </tr>
  <tr>
    <td style="text-align: center; vertical-align: middle;">Female, age: 21 <br>Phrase 1 
</td>
    <td style="text-align: center; vertical-align: middle;">
      <audio controls>
      <source src="noa_s1_p1.mp3" type="audio/mpeg">
      Browser doesn't support audio element 
      </audio>
    </td>
    <td style="text-align: center; vertical-align: middle;">
      <audio controls>
      <source src="noa_s1_p2.mp3" type="audio/mpeg">
      Browser doesn't support audio element
      </audio>
    </td>     
  </tr>
  <tr>   
    <td style="text-align: center; vertical-align: middle;">Male, age: 55, Phrase 2</td>
    <td style="text-align: center; vertical-align: middle;">
      <audio controls>
      <source src="Yossi_s2_p1.mp3" type="audio/mpeg">
      Browser doesn't support audio element
      </audio>
    </td>
    <td style="text-align: center; vertical-align: middle;">
      <audio controls>
      <source src="Yossi_s2_p2.mp3" type="audio/mpeg">
      Browser doesn't support audio element
      </audio>
    </td>   
  </tr>
  <tr>
    <td style="text-align: center; vertical-align: middle;">Female, age: 33, Phrase 3</td>
    <td style="text-align: center; vertical-align: middle;">
      <audio controls>
      <source src="sivan_s3_p1.mp3" type="audio/mpeg">
      Browser doesn't support audio element
      </audio>
    </td>
    <td style="text-align: center; vertical-align: middle;">
      <audio controls>
      <source src="sivan_s3_p2.mp3" type="audio/mpeg">
      Browser doesn't support audio element
      </audio>
    </td>          
  </tr>
</table>
The phrases: <br>
Phrase 1: /BO/  /LA/  /TSA/ /BIM/ = come to the turtles<br>
Phrase 2: /GAM/ /PO/  /AR/  /MON/ = there is a palace here too<br>
Phrase 3: /EN/  /KAN/ /BO/  /NIM/ = there are no beavers here<br>

    
# Our Work
## TSD - Text Speech & Dialouge Conference, Czech Republic, 2018
In this conference we are going to introduce the first step of our research: a criterion that we developed, which can measure a feature and determine whether it conveys prosodic information, and provides a numerical score for that feature. 
* **The paper**: [Ben Fishman, Itshak Lapidot, and Irit Opher, “Prosodic Features' Criterion For Hebrew”, Proceedings of Text, Speech, Dialogue-TSD conference, 2018](https://link.springer.com/chapter/10.1007/978-3-030-00794-2_52)
* **The Poster**

![poster](TSD_poster.jpg "Our poster")


## ICSEE, Israel, 2018
In this conference we are going to introduce a validation of the PFC that shows usage of a different feature set. We replaced our 48 original features with 4,500 features that were extraced using the OpenSMILE tool kit.
More details and the full paper will be uploaded soon.

## Ongoing Research

These days we are still developing and validating the PFC using an extended database, including different languages and multiple prosodies. We also formed a stronger mathematical formulation for the PFC.
Additional information will be uploaded in the near future.
