# Interview_splitter

This notebook splits an recorded inteview in .mp4 format into the audio and video streams based on the 
current speaker. The idea is to break an interview down into individual speakers (being the interviewer
and the interviewee). It requires a breakdown of the interview text passed to it as a .json file (typically 
from an amazon transact) split of who said what with given timestamps. It saves then saves the split into a 
separate directory for each different interview, sound as .mp3 and video as .mp4 files.

The next part of the notebook then breaks down the emotions detected using code that was sourced from pre-existing 
emotion recognition libraries. The final part then puts these emotions based on each question into a .pdf
file for display and saving.
