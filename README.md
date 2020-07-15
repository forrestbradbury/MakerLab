# MakerLab
 course materials for supporting scientific open inquiries with sensors and microcontrollers

This collection of materials supports open-inquiry physical science experiments in Bachelor's level lab courses.  Their open-source publication has been expedited because they serve as a model for pandemic-resilient science labs (https://arxiv.org/abs/2006.06881).  A majority of the materials have been written as Jupyter Notebook documents and other text-based formats, lending themselves to further collaborative development, adaptation, and expansion within this git repository.  

## Understanding science through doing science

By leveraging the modern and open-source resources of the Maker movement, students are empowered to design and conduct authentic high level scientific inquiries at home in flipped-classroom style lab courses (or course components).  By focusing learning goals on the process of conducting experimental research, the activities supported by these materials lower barriers to citizen science and simultaneously engender fuller appreciation for professional scientific endeavors.

## Downloading materials

While it is encouraged to fork and reshare adaptations of these materials on github, we realize that many people may just want a zipped folder of this repository's collection.  The latest accepted versions of the master directory can be obtained using this link:    
http://github.com/forrestbradbury/MakerLab/archive/master.zip

For further information about reusing the materials, please read the license description.  Forrest Bradbury (https://orcid.org/0000-0001-8412-4091) of Amsterdam University College is responsible for this repository and can be reached by email:  forrestbradbury ("AT") gmail.com

## Overview and description

The first published set of these materials has been designed to support a full physical science lab course, demanding ~168 hours of student work time.  The original Maker Lab course at AUC utilizes flipped-classroom approaches and trains students in Maker skills (specifically in the use of Arduinos to control sensors for scientific experiments).  Students are supported in following a full empirical research cycle (an open inquiry) and are further trained to quantitatively analyze empirical data using Python in Jupyter Notebooks.

Besides this README document and the license file, this repository consists of the following subdirectories:

- [JN_LecNs-Templates-StrExps](../MakerLab/master/JN_LecNs-Templates-StrExps):  Jupyter Notebook documents, including:
  - Lecture Notes covering:
    - introductions to Jupyter Notebooks, Markdown, and Python programming
    - uncertainty analysis, curve fitting, and Fourier transforms
  - Structured experiment instructions:
    - Arduino introduction and first structured experiment
    - Semi-structured experiments
  - Templates for student assignments:
    - open-inquiry project pre-proposal
    - open-inquiry project Lab Journal
  - Folders for data and images used in the above documents
- [equipment-list-options](../MakerLab/master/equipment-list-options):  spreadsheet giving suggested options for sets of course equipment
- [grading-forms](../MakerLab/master/grading-forms):  assessment forms for four course assignments (currently in Microsoft Word format)
- [instructor-materials](../MakerLab/master/instructor-materials):  materials that may help in adapting these materials, including:
  - example schedule for a full course (168 hours of student work time)
  - untested example schedule for a smaller course component (60-80 hours of student work time)
  - some other recommendations
- [video_lectures-presentations](../MakerLab/master/video_lectures-presentations):  links to videos, including:
  - lectures for students
  - presentation(s) on course methods & results
- [todo-list](../MakerLab/master/todo-list):  a "to do" list for ideas of expanding and improving the materials (which is parallel and probably not synchronized with the github repository development)


## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.  Everyone is free to reuse or adapt the materials under the conditions that they give appropriate attribution, do not use them nor derivatives of them for commercial purposes, and that any distributed or re-published adaptations are given the same Creative Commons License.


## Acknowledgements

The original Maker Lab pilot course at Amsterdam University College (AUC) was fully supported by a Comenius Fellowship grant from the Netherlands Initiative for Education Research (NRO) and the Dutch Ministry for Education (OCW).  AUC also previously supported a related project of smaller scope through a Blending Learning grant.  The Comenius project team included Freek Pols (TU Delft, https://orcid.org/0000-0002-4690-6460), "Paul" C. L. Vlaanderen (Universiteit van Amsterdam), and Jasper J. Homminga (Universiteit Twente).  Freek helped with the course design and conception and development of these materials, and many of his specific contributions are acknowledged in the individual documents.  Paul co-taught the pilot Maker Lab course and gave continual input and council in the course design and materials (in too many places to allow for specific attribution).  Jasper played an important consultative role thanks to his experience in guiding open inquiries.

Also importantly, Gary Steele (TU Delft), Jan Koetsier (AUC), and David Fokkema (UvA) assisted with the Jupyter Notebook lecture notes.  The four lecture note documents which introduce Python programming all include significant material, structure, and inspiration from documents in Gary's "Introduction to Python for Physicists" (https://gitlab.tudelft.nl/python-for-applied-physics/practicum-lecture-notes).  Jan is largely to thank for the adaptation and extension of Gary's materials for Maker Lab students.  David provided feedback and superior methods in the document on curve fitting.

Saalih Allie, Andy Buffler, Dale Taylor, and Nuraan Majiet from the University of Cape Town all helped steer the Maker Lab course design through conversations and sharing best practices.  Additionally, the document on uncertainty analysis draws inspiration and some nice figures from UCT's "Introduction to Measurement in the Physics Laboratory:  A probabilistic approach" by Buffler, Allie, Lubben, and Campbell.

Finally, conversations with Jean J. Heremans and Thomas O’Donnell from Virginia Tech helped in better understanding how these course methods might be applied in dedicated advanced physics labs.

Additional contributors (either via this git repository, or otherwise) are encouraged to suggest a shout-out here!
