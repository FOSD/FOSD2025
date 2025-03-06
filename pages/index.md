<style>
  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 40px; /* Adds space between tables */
  }
  th, td {
    border: 1px solid #ddd;
    padding: 12px;
    text-align: left;
  }
  th {
    background-color: #f4f4f4;
    font-size: 1.2em;
  }
  td {
    font-size: 1em;
  }
  table colgroup col:first-child {
    width: 20% !important;
  }
  table colgroup col:last-child {
    width: 80% !important;
  }
</style>

# About
The Meeting on Feature-Oriented Software Development (FOSD Meeting) is a yearly informal meeting to bring together the community of researchers working on feature-oriented software development, including, but not limited to:

- Product lines
- Software variability
- Configuration management
- Software architecture

The meeting series started 16 years ago to bring several research groups with common interests closer together. It has successfully been repeated 15 times with 20 to 50 participants each, and has established countless collaborations since. For example, see the recent past FOSD meetings: [FOSD 2024 in Eindhoven](https://set.win.tue.nl/event/fosd-meeting-2024/), [FOSD 2023 in Ulm](https://fosd23.uni-ulm.de/), and [FOSD 2022 in Vienna](https://fosd2022.wu.ac.at/).

The main objective is that researchers at different career stages (including undergraduate and early-career graduate students) come together to present their research, to get feedback from peers, to discuss new directions, and to initiate collaborations.

The format of an FOSD meeting consists of short presentations from each participant with plenty of time for discussion. Young researchers (graduate and undergraduate students), as well as more senior community members, present their research, provide and get feedback from others, engage into discussions and establish new collaborations. FOSD is a place for discussion, not a publication venue. Participants can present previously published work as well as unpublished work, including early ideas and work in progress. The key is to encourage discussions, to receive feedback and to grow the network of collaborating researchers.

## Important Dates
<table>
  <tr>
    <td>Abstract Submission Deadline</td>
    <td>December 4, 2024 </td>
  </tr>
  <tr>
    <td>Notification of Acceptance</td>
    <td>December 16, 2024 </td>
  </tr>
  <tr>
    <td>Registration Deadline</td>
    <td>March 5, 2025</td>
  </tr>
  <tr>
    <td>FOSD Meeting 2025</td>
    <td>March 25 - 28, 2025</td>
  </tr>
</table>

# Participants
<table>
  <tr>
    <th>Name</th>
    <th>Title</th>
    <th>University</th>
  </tr>
  {% for item in site.data.participants %}
  <tr>
   <td width="20%">{{item.name}}</td>
   <td width="60%">{{item.title}} {% if item.link != null %}<a href={{item.link}} target="_blank" >[slides]</a>{% endif %}</td>
   <td width="20%">{{item.university}}</td>
  </tr>
 {% endfor %}

</table>

# Schedule
The list of speakers for each session will be announced on the preceding day. For the first day (Tuesday, March 25th) we plan to announce the concrete talks approximately one week before.

<table>
  <tr>
    <th>Time</th>
    <th>Tuesday (25th March)</th>
  </tr>
  <tr>
    <td>08:30</td>
    <td>Morning Coffee</td>
  </tr>
  <tr>
    <td>09:00</td>
    <td>Opening</td>
  </tr>
  <tr>
    <td>09:15</td>
    <td><b>Keynote:</b> Norbert Siegmund (Univ. Leipzig)</td>
  </tr>
  <tr>
    <td>10:15</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>10:45</td>
    <td>Session 1</td>
  </tr>
  <tr>
    <td>12:00</td>
    <td>Lunch</td>
  </tr>
  <tr>
    <td>13:30</td>
    <td>Session 2</td>
  </tr>
  <tr>
    <td>14:45</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>15:15</td>
    <td>Session 3</td>
  </tr>
  <tr>
    <td>16:30</td>
    <td>Reception at Hochschule Anhalt</td>
  </tr>
  <tr>
    <td style="border-left: none; border-right: none;"></td>
    <td style="border-left: none; border-right: none;"></td>
  </tr>
  <tr>
    <th>Time</th>
    <th>Wednesday (26th March)</th>
  </tr>
  <tr>
    <td>08:30</td>
    <td>Morning Coffee</td>
  </tr>
  <tr>
    <td>09:00</td>
    <td><b>Keynote:</b> Danilo Beuche (pure/PTC)</td>
  </tr>
  <tr>
    <td>10:00</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>10:30</td>
    <td>Session 4</td>
  </tr>
  <tr>
    <td>12:00</td>
    <td>Lunch</td>
  </tr>
  <tr>
    <td>13:30</td>
    <td>Session 5</td>
  </tr>
  <tr>
    <td>14:45</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>15:15</td>
    <td>Session 6</td>
  </tr>
  <tr>
    <td>19:00</td>
    <td>Dinner at Brauhaus Köthen</td>
  </tr>
  <tr>
    <td style="border-left: none; border-right: none;"></td>
    <td style="border-left: none; border-right: none;"></td>
  </tr>
  <tr>
    <th>Time</th>
    <th>Thursday (27th March)</th>
  </tr>
  <tr>
    <td>08:30</td>
    <td>Morning Coffee</td>
  </tr>
  <tr>
    <td>09:00</td>
    <td>Session 7</td>
  </tr>
  <tr>
    <td>10:15</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>10:45</td>
    <td>Session 8</td>
  </tr>
  <tr>
    <td>12:00</td>
    <td>Lunch</td>
  </tr>
  <tr>
    <td>13:30</td>
    <td>Informal Get-Together (Breakout Session)</td>
  </tr>
  <tr>
    <td>14:30</td>
    <td><b>Social Event:</b> Bauhaus Museum Dessau</td>
  </tr>
  <tr>
    <td>18:30</td>
    <td>Dinner at Creperie Lorette</td>
  </tr>
  <tr>
    <td style="border-left: none; border-right: none;"></td>
    <td style="border-left: none; border-right: none;"></td>
  </tr>
  <tr>
    <th>Time</th>
    <th>Friday (28th March)</th>
  </tr>
  <tr>
    <td>08:30</td>
    <td>Morning Coffee</td>
  </tr>
  <tr>
    <td>09:30</td>
    <td>Session 9</td>
  </tr>
  <tr>
    <td>10:15</td>
    <td>Coffee Break</td>
  </tr>
  <tr>
    <td>10:45</td>
    <td>Session 10</td>
  </tr>
  <tr>
    <td>12:00</td>
    <td>Lunch</td>
  </tr>
</table>


{% for conf_day in site.data.schedule %}
### Schedule {{ conf_day.day | date: "%A, %b %e" }}

{% for session in conf_day.sessions %}
Session: {{ session.from | date: "%R" }} - {{ session.to | date: "%R" }}, Chair: {{ session.chair }} 
{% for talk in session.talks %}
* **{{ talk.speaking }}**: {{ talk.title }}
{% endfor %}
{% endfor %}
{% endfor %}

# Venue & Travel Information
The FOSD Meeting 2025 will take place at the Anhalt University of Applied Sciences in Köthen, Germany.

Köthen (Anhalt) is a town in the federal state of Saxony-Anhalt with a population of around 26,000. Köthen is historically significant above all as the place where Johann Sebastian Bach worked, who was Kapellmeister at the court of Prince Leopold von Anhalt-Köthen from 1717 to 1723. Some of his most famous works were composed during this time, including the Brandenburg Concertos and parts of the Cello Suites.

The town has a long history dating back to 1115, when it was first mentioned in a document. Köthen was once the capital of the Principality of Anhalt-Köthen. [Homeopathy also has a special influence in Köthen, as Samuel Hahnemann, the founder of homeopathy, lived and worked here]. Today, the town is a center for teaching and education, with the Anhalt University of Applied Sciences playing an important role. Architectural sights such as Köthen Castle and St. Jacob's Church bear witness to the town's rich history.

<iframe id="gmaps_iframe" src="https://www.google.com/maps/d/embed?mid=1zgLgPVTlVTXBu35Tt8JQzorzVzY_6LM&ehbc=2E312F"></iframe>

Anhalt University of Applied Sciences is the largest and one of the most important universities of applied sciences in Saxony-Anhalt. It is spread over three locations (Köthen, Bernburg, Dessau) and offers a wide range of practical courses in the fields of engineering, design, computer science, economics, agriculture and natural sciences. With around 7,500 students, the university attracts both national and international students who benefit from a modern and interdisciplinary education.

In Köthen, the university concentrates primarily on technical and natural science fields, while in Bernburg the focus is on agriculture and ecology. Dessau is known for design and architecture, deeply rooted in the Bauhaus tradition. Research is a central component of Anhalt University of Applied Sciences, with innovative projects being promoted in cooperation with industry and other research institutions. The university attaches great importance to application-oriented research and offers numerous laboratories and facilities where students can gain practical experience. In addition, the university supports business start-ups and thus contributes to the regional industry and beyond.

![Department02](/FOSD2025/assets/img/CS-department02.jpg)

The FOSD meeting takes place at the Department of Computer Science and Languages, which is located in the venerable Ratke building, a building erected in 1885 and named after Wolfgang Ratke, a pioneer of the modern school system.

## Arrival by Train

Köthen is located between Magdeburg and Leipzig, and thus, well-connected by regional as well as Intercity train:

* from Leipzig Airport: ~35-50 minutes
* from Halle (Saale): ~20-25 minutes
* from Magdeburg: ~25-40 minutes
* from Hannover: ~2 hours
* from BER airport: ~2,5 hours
* from Frankfurt/Main airport: ~ 4,5-5 hours

## Arrival by Plane
Since there is no airport in Köthen, we recommend that you book a flight to one of the airports below and find a connection by train.

* Leipzig/Halle Airport has regular flights to several major European cities. Arriving there, you can reach Köthen by train in around 35-50 minutes.
* Frankfurt Airport can also be reached from non-european countries. Taking the train to Köthen will take around 4,5 to 5 hours.

# Contact
For questions and abstract submissions, please send an email to <fosd25@hs-anhalt.de>.

## Organizers
- [Sandro Schulze](https://www.hs-anhalt.de/hochschule-anhalt/service/personenverzeichnis/person/prof-dr-sandro-schulze.html)
- [Tobias Dick](https://www.se.cs.uni-saarland.de/people/dick.php)

## Steering Committee
- [Sven Apel](https://www.se.cs.uni-saarland.de/apel/)
- [Thomas Thüm](https://www.uni-paderborn.de/person/102807)
