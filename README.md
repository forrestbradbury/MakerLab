**UPDATES:**
**Since publishing these course materials, I've worked in collaboration with other teachers to extend and improve materials for supporting open inquiry labs.  Our collaborative work can be found here:  https://edusources.nl/materials/04566738-bd6f-49c6-a2d9-f64a3885394b**
**And an article on design of open inquiry labs can be found here:  https://edusources.nl/materials/15cc57c2-f271-47e6-99b4-1e57de1c2af1**
**And my own updated Maker Lab materials can be found here:  https://edusources.nl/materials/06a621ae-92d3-4cdc-a416-433bb372e116**

**This GitHub repository contains the materials from the first course iteration, and will remain unchanged due to lack of time.  Thus anyone interested in the evolution of the course design and materials is directed to the links above.**

# MakerLab

 course materials for supporting scientific open inquiries with sensors and microcontrollers

This collection of materials supports open-inquiry physical science experiments in Bachelor's level lab courses.  Their open-source publication has been expedited because they serve as a model for pandemic-resilient science labs (https://arxiv.org/abs/2006.06881).  Most of the materials have been written as Jupyter Notebook documents and other text-based formats, lending themselves to further collaborative development, adaptation, and expansion within this git repository.  

## Understanding science through doing science

**Empowerment:** By leveraging the modern and open-source resources of the Maker movement, students are empowered to design and conduct authentic high level scientific inquiries at home in flipped-classroom style lab projects.  

**Science Outreach & Advocacy:** By focusing learning goals on the process of conducting experimental research, the activities supported by these materials lower barriers to citizen science and simultaneously engender fuller appreciation for professional scientific endeavors.

The "[Why_Open_Flipped_andArduinos.md](Why_Open_Flipped_andArduinos.md)" document gives a fuller motivation for the Maker Lab course methods.  

## Downloading materials

Those interested in adopting and adapting materials are encouraged to get in touch!  If there is interest, a "faculty online learning community" will be initiated to support adaptations, and any reshared extensions & improvements of this material will benefit everyone.

While it is encouraged to fork and reshare adaptations of these materials on GITHUB, we realize that many people may just want a zipped folder of this repository's collection.  The latest accepted versions of the master directory (in a single zip file) can be obtained using this link:    
http://github.com/forrestbradbury/MakerLab/archive/master.zip

For information about reusing the materials, please read the license description ([license.md](license.md)).  Forrest Bradbury (https://orcid.org/0000-0001-8412-4091) of Amsterdam University College is responsible for this repository and can be reached by email:  forrestbradbury ("AT") gmail.com .  

## Overview and description

The first published set of these materials has been designed to support a full physical science lab course, demanding ~168 hours of student work time.  The original Maker Lab course at AUC utilizes flipped-classroom approaches and trains students in Maker skills (specifically in the use of Arduinos to control sensors for scientific experiments).  Students are supported in following a full empirical research cycle (an open inquiry) and are further trained to quantitatively analyze empirical data using Python in Jupyter Notebooks.

Besides this README document and the license file, this repository consists of the following subdirectories:

- [1_instructor-materials](1_instructor-materials):  materials for helping instructors in adapting these methods, including:
  - "tips_for_instructors" - tips for adoption and adaptation
  - "AUC_course_manual" - course description and example schedule for a full course (168 hours of student work time)
  - "short_open_inquiry" - untested example schedule for a smaller course component (55-80 hours of student work time)
- [2_equipment-list-options](2_equipment-list-options):  spreadsheet giving suggested options for sets of course equipment
- [3_JN_LecNs-Templates-StrExps](3_JN_LecNs-Templates-StrExps):  Jupyter Notebook documents, including:
  - Lecture Notes covering:
    - the empirical research process
    - introductions to Jupyter Notebooks, Markdown, and Python programming
    - uncertainty analysis, curve fitting, and Fourier transforms
  - Structured experiment instructions:
    - Arduino introduction and first structured experiment
    - Semi-structured experiments
  - Templates for student assignments:
    - open-inquiry project pre-proposal
    - open-inquiry project Lab Journal
  - Folders for data and images used in the above documents
- [4_video_lectures-presentations](4_video_lectures-presentations):  links to videos, including:
  - lectures for students
  - conference presentation(s) on course methods & results
  - online 3rd party videos related to the Maker movement
- [5_grading-forms](5_grading-forms):  assessment forms for four course assignments (currently in Microsoft Word format)
- [6_todo-list](6_todo-list):  a "to do" list for ideas of expanding and improving the materials (which is parallel and probably not synchronized with the GITHUB repository development)


## Acknowledgements

The original Maker Lab pilot course at Amsterdam University College (AUC) was fully supported by a Comenius Fellowship grant from the Netherlands Initiative for Education Research (NRO) and the Dutch Ministry for Education (OCW).  AUC also previously supported a related project of smaller scope through a Blending Learning grant.  The Comenius project team included Freek Pols (TU Delft, https://orcid.org/0000-0002-4690-6460), "Paul" C. L. Vlaanderen (Universiteit van Amsterdam), and Jasper J. Homminga (Universiteit Twente).  Freek helped with the course design and conception and development of these materials, and many of his specific contributions are acknowledged in the individual documents.  Paul co-taught the pilot Maker Lab course and gave continual input and council in the course design and materials (in too many places to allow for specific attribution).  Jasper played an important consultative role thanks to his experience in guiding open inquiries.

Also importantly, Gary Steele (TU Delft), Jan Koetsier (AUC), and David Fokkema (Vrije Universiteit Amsterdam) assisted with the Jupyter Notebook lecture notes.  The four lecture note documents which introduce Python programming all include significant material, structure, and inspiration from documents in Gary's "Introduction to Python for Physicists" (https://gitlab.tudelft.nl/python-for-applied-physics/practicum-lecture-notes).  Jan is largely to thank for the adaptation and extension of Gary's materials for Maker Lab students.  And, David provided feedback and superior methods in the curve fitting document.

Saalih Allie, Andy Buffler, Dale Taylor, and Nuraan Majiet from the University of Cape Town (UCT) all helped steer the Maker Lab course design through conversations and sharing best practices.  Additionally, the document on uncertainty analysis draws inspiration and some nice figures from UCT's "Introduction to Measurement in the Physics Laboratory:  A probabilistic approach" by Buffler, Allie, Lubben, and Campbell.

The Maker Lab leans heavily on Maker resources and communities from across the globe, though a few specific people deserve special recognition.  Especially useful were lengthy conversations about Maker education with Felix Holm of Maker Station in Cape Town, Chris Julien and Henk Buursen (including an awesome FabLab tour from Henk) from the Amsterdam Waag Society, and some Maker friends Kuni Cherenack, Troy Nachtigall, Martin Bruggink, and Bram de Kruijff.  Further, Thierry Slot of the Universiteit van Amsterdam delivered an inspiring guest lecture which was highly appreciated by the Maker Lab students on his scientific research enabled by Maker methods (described briefly here:  https://youtu.be/vwsZGp8XRaU).

Recently, conversations with Jean J. Heremans and Thomas O’Donnell from Virginia Tech helped in better understanding how these course methods might be applied in dedicated advanced physics labs.

Finally, the pilot course AUC students deserve a big shout out.  Every last one of them persevered through the stress and uncertainty of the pandemic to successfully complete two open-inquiry projects and pass the course.  Their dedication and energy were critical for the success of the pilot and proved that experimental lab courses can succeed and shine - even in such challenging circumstances - simply by supporting students' own project ideas.
