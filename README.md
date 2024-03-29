# MAMIC - Music and Maths in Collaboration
Hello and welcome to the MAMIC Git


MAMIC is a collation of Pure Data library abstractions and thus a visual programming library for the Pd-L2Ork IDE, specifically designed to give primary school students the chance to create music through maths and visual programming. This is achieved by MAMIC's use of the the UK's National Curriculum (NC) statutory requirements for music, maths and computing at Key Stage (KS) One. Thus, allowing students to create MAMIC patches, which can be thought of as collections of interconnected abstractions that converge to make a MAMIC program (patch).
 

MAMIC aims to take advantage of music’s interdisciplinary qualities to teach maths and computing through a visual programming environment that is based on NC statutory requirements. This is achieved through the thematic approach to interdisciplinary curricular connections. MAMIC contains certain visual programming attributes and resourcing structures that can potentially refocus music as required by using service connections, symmetric correlations and syntegration opportunities in both mathematical and computing terms to take advantage of its interdisciplinary vehicle qualities.


MAMIC uses the Ubuntu Studio 16.04 LTS operating system and is fully portable through the use of a bootable USB distribution designed for PC hardware. This USB distribution also includes Central Processing Unit (CPU) demand reduction algorithms to enable optimum performance on a variety of computing systems in-the-wild. The nature of the USB system also enables in-the-wild practitioners to boot the system directly, without the need to install it to a computer hard drive. 
<br>
<br>
<br>
<b>MAMIC has two elements:</b>
<br>
<br>
●	The MAMIC library – a visual programming library in isolation 
<br>
<br>
●	The MAMIC USB system – a USB-optimised version of the Ubuntu Studio 16.04 LTS operating system that encompasses the Pd-2LOrk IDE, the MAMIC library, in-the-wild practitioner support materials and additional operating system features. 
<br>
<br>
<br>
<b>MAMIC aims to:</b>

●	Leverage musical process relating to composition and performance to introduce coding (and visual programming specifically) in an accessible and engaging way.

●	Use musical process to vibrantly introduce mathematical concepts.

●	Reinforce existing mathematical knowledge by making abstract concepts audible and/or visible, and able to be modified in a hands-on way.  

●	Facilitate and support in-the-wild delivery by non-subject-specialists.

●	Run on a wide variety of computers, including on the older and budget-orientated hardware found in many schools, without requiring permanent installation.







The MAMIC topology model below gives an insight into how the MAMIC abtractions are ordered 

![mamiciteration3](https://user-images.githubusercontent.com/10425370/156435572-22abf2ad-57b6-414a-acf3-4941950c8443.png)





The MAMIC library adopts the syntegration concept the sequence number as the primary mechanism for programming/controlling all MAMIC abstractions. The sequence number has two forms – command variables and music variables. Music variables are integers that control direct musical processes like scale degrees, musical pitches, or chord voicings. Command variables are integers that allow other MAMIC abstractions to be triggered in isolation or in sequence, appropriate to the MAMIC patch in question. 

MAMIC uses NC-focused worksheet algorithms to ensure interdisciplinary use of the NC statutory requirements of music, maths and compting at KS One. 


<h2>Video Code Examples from the MAMIC Library</h2>
Below is a table containing some video examples of how to use the MAMIC library.
<br>
<br>
<table>
<thead>
  <tr>
    <th>Video URL</th>
    <th>Video Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>https://youtu.be/0wkOQFS14pg</td>
    <td>[compk] Abstraction Example showing Audio File Playback.</td>
  </tr>
  <tr>
    <td>https://youtu.be/ghVLSvAG5Gs</td>
    <td>[xboxpad] Example Demonstrating Audio Playback and Sequence Number Implementation </td>
  </tr>
    <tr>
    <td>https://youtu.be/nErDdCTEgLs</td>
    <td>MAMIC Score Demonstration</td>
  </tr>
  <tr>
    <td>https://youtu.be/sKv4jOWzh18</td>
    <td>NC-Focused Worksheet Algorithm Example – Creating Pitches with Numbers</td>
  </tr>
  <tr>
    <td>https://youtu.be/R4MufyuJhoE</td>
    <td>NC-Focused Worksheet Algorithm Example – Dates and Chords</td>
  </tr>
</tbody>
</table>
<h2>Further MAMIC Resources</h2>
<p>Further MAMIC resources can be found <a href="https://drive.google.com/drive/folders/10YK8cYSjPG9dq7qrXabGDg1yLgssHpFE?usp=sharing">here</a>
These include:</p>

● The MAMIC Operations Manual
<br>
<br>
● Student NC-focused Interdisciplinary Worksheets
<br>
<br>
● MAMIC Helpsheets
<br>
<br>
● DI Student Worksheets - Differentiated Tasks
<br>

 





<h2>How to Install this MAMIC Library</h2>

Firstly, I recommend you work with MAMIC on Ubuntu-Studio 16.04 and install the Pd-L2Ork IDE through these terminal commands:

To build the MAMIC System on Ubuntu Studio 16.04

Install Synaptic Package Manager

sudo apt-get update

sudo apt-get install synaptic

Then install the Pd-L2Ork IDE

sudo add-apt-repository ppa:dr-graef/pd-l2ork.xenial

sudo apt-get update

sudo add-apt-repository ppa:maarten-baert/simplescreenrecorder

sudo apt-get update

Install Pd-L2Ork IDE and the other packages below with Synaptic Package Manager

Pd-L20rk

VLC Player

Simple Screen Recorder

Next take the contents of this Git MAMICLibrary and navigate to this folder in Pd-L2Ork as a library path. 

Please then feel free start using and changing the MAMIC abstractions.

Please feel free to add to this project and contribute :) 

