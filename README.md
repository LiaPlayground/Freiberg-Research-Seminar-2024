<!--
author: André Dietrich
email:  andre.dietrich@informatik.tu-freiberg.de

import: https://fjangfaragesh.github.io/AVR8js-mem/INCLUDE.md

@style
.fall {
  position: absolute;
  top: 0;
  animation: fall 4s linear;
}
@keyframes fall {
  0% { top: 0; }
  100% { top: 100%; }
}
@end

@wave
<script input="button" run-once="true" modify="false">
if (LIA.classroom.connected){
    LIA.classroom.publish("wave", "@0")
}
"@0"
</script>
@end

-->


# Freiberg Research Seminar 2024

0. Pre-History
1. LiaScript
2. Peer2Peer Classrooms
3. Peer2Peer Remote-Labs

## Pre-History

!?[Industrial eLab](https://www.youtube.com/watch?v=bICfKRyKTwE "eLab - Labor mit Fernzugriff an der Otto-von-Guericke-Universität Magdeburg 2018")

## LiaScript

_LiaScript: A simple and easy to use markdown based _

### Technologies

* Back-End implemented in [Elixir](https://en.wikipedia.org/wiki/Elixir_%28programming_language%29)
* Fron-End implemented in [Elm](https://en.wikipedia.org/wiki/Elm_%28programming_language%29)

    {{1}}
<section>
---

__BrowserBased Technologies__

* Indexed Database API [IndexedDB](https://en.wikipedia.org/wiki/Indexed_Database_API)
* Speech Synthesis or [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)

  
  >                 {{|>}}
  > Hello and welcome this is a text-to-speech example.

* Progressive Web App [PWA](https://en.wikipedia.org/wiki/Progressive_web_app)
* Web Real-Time Communication [WebRTC](https://en.wikipedia.org/wiki/WebRTC)
* Conflict-free Replicated Data Types [CRDTs](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type)

</section>

### Features


#### Quizzes

    {{1}}
<section>

What is the name of the Markdown-Dialect I am talking about?

[[LiaScript]]

</section>














    {{2}}
<section>

Insert the currect numbers such that the pyramid provides sums from bottom to top...

<!-- data-show-partial-solution -->
``` ascii
                        .----------------------.
                       /                      /|
             .--------+----------------------+ +---------.
            /         |      " [[  24   ]] " |/         /|
  .--------+----------+----------+-----------+---------+ +----------.
 /         |         11          |      "[[   13   ]] "|/          /|
+----------+----------+----------+----------+----------+----------+ +
|      " [[   5   ]] "|          6          |          7          |/
+---------------------+---------------------+---------------------+
```

</section>















    {{3}}
<section>

Do you know an easier way of creating quizzes?

[( )] Yes
[(X)] No

</section>
















    {{4}}
<section>

Guess the correct German articles?

[[male (der)] (female [die]) [neuter (das)]]
[    [X]           [ ]             [ ]     ]  Mann - German for man
[    ( )           (X)             ( )     ]  Frau - German for woman
[    [X]           [ ]             [ ]     ]  Junge - German for boy
[    ( )           ( )             (X)     ]  Mädchen - German for girl
[    [X]           [X]             [ ]     ]  Paprika - German for bell pepper
[    (X)           (X)             (X)     ]  Joghurt - German for yogurt

</section>






#### Multimedia & Presentation Formats


![Portrait of a lady](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Leonardo_da_Vinci_%28attrib%29-_la_Belle_Ferroniere.jpg/723px-Leonardo_da_Vinci_%28attrib%29-_la_Belle_Ferroniere.jpg "La Belle Ferronnière, c. 1490–1498")

![Lady with an Ermine](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Lady_with_an_Ermine_-_Leonardo_da_Vinci_-_Google_Art_Project.jpg/761px-Lady_with_an_Ermine_-_Leonardo_da_Vinci_-_Google_Art_Project.jpg "Lady with an Ermine, c. 1489–1491, Czartoryski Museum, Kraków, Poland")

![Mona Lisa](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Mona_Lisa%2C_by_Leonardo_da_Vinci%2C_from_C2RMF_retouched.jpg/687px-Mona_Lisa%2C_by_Leonardo_da_Vinci%2C_from_C2RMF_retouched.jpg "Mona Lisa or La Gioconda c. 1503–1516, Louvre, Paris")

![Virgin and Child ](https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Leonardo_da_Vinci_-_Virgin_and_Child_with_St_Anne_C2RMF_retouched.jpg/764px-Leonardo_da_Vinci_-_Virgin_and_Child_with_St_Anne_C2RMF_retouched.jpg "The Virgin and Child with Saint Anne, c. 1501–1519, Louvre, Paris")

![The Death of Leonardo da Vinci](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Francois_Ier_Leonard_de_Vinci-Jean_Auguste_Dominique_Ingres.jpg/1276px-Francois_Ier_Leonard_de_Vinci-Jean_Auguste_Dominique_Ingres.jpg "The Death of Leonardo da Vinci, by Ingres, 1818")


    {{1}}
!?[Text 2 Speech](https://www.youtube.com/watch?v=saxAFw7XpjI)




#### Visualization


      9 |                                       (* dots)
        |
      y |                              *
      - |
      a |                    *
      x |
      i |          *
      s |
        |*
      0 +------------------------------------
        0            x-axis                 36



















    {{1}}
|   x | dots |
| ---:| ----:|
|   0 |    0 |
|  10 |    2 |
|  20 |    4 |
|  30 |    6 |























    {{2}}
| Animal          | weight in kg | Lifespan years | Mitogen |
| --------------- | ------------:| --------------:| -------:|
| Mouse           |        0.028 |              2 |      95 |
| Flying squirrel |        0.085 |             15 |      50 |
| Brown bat       |        0.020 |             30 |      10 |
| Sheep           |           90 |             12 |      95 |
| Human           |           68 |             70 |      10 |























    {{3}}
<!--
data-type="heatmap"
data-title="Seattle mean temperature in Fahrenheit"
data-show
-->
| Seattle |  Jan |  Feb |  Mar |  Apr |  May |  Jun |  Jul |   Aug |  Sep |  Oct |  Nov |  Dec |
| -------:| ----:| ----:| ----:| ----:| ----:| ----:| ----:| -----:| ----:| ----:| ----:| ----:|
|       0 | 40.7 | 41.5 | 43.6 | 46.6 | 51.4 | 56.0 | 60.5 |  61.2 | 57.0 | 50.1 | 44.1 | 39.6 |
|       2 | 40.2 | 40.7 | 42.7 | 45.3 | 50.0 | 54.4 | 58.5 |  59.2 | 55.4 | 49.2 | 43.5 | 39.3 |
|       4 | 39.7 | 40.0 | 41.9 | 44.4 | 48.9 | 53.2 | 57.0 |  57.7 | 54.2 | 48.6 | 43.1 | 38.9 |
|       6 | 39.6 | 39.5 | 41.3 | 44.2 | 49.5 | 54.2 | 57.8 |  57.4 | 53.6 | 48.2 | 42.8 | 38.7 |
|       8 | 39.6 | 39.9 | 42.9 | 47.1 | 52.7 | 57.3 | 61.3 |  61.1 | 56.7 | 49.5 | 43.1 | 38.7 |
|      10 | 41.3 | 42.7 | 46.4 | 50.7 | 56.4 | 60.9 | 65.2 |  65.4 | 60.9 | 52.8 | 45.5 | 40.4 |
|      12 | 43.8 | 46.0 | 49.5 | 53.8 | 59.6 | 64.3 | 69.4 |  69.8 | 65.1 | 56.0 | 47.8 | 42.6 |
|      14 | 45.1 | 47.7 | 51.3 | 55.9 | 61.9 | 66.9 | 72.6 |  73.2 | 67.7 | 57.8 | 48.8 | 43.6 |
|      16 | 44.5 | 47.5 | 51.4 | 55.9 | 62.3 | 67.5 | 73.9 |  74.3 | 68.2 | 57.4 | 47.8 | 42.6 |
|      18 | 42.6 | 44.7 | 48.7 | 53.8 | 60.3 | 65.9 | 72.3 |  72.2 | 64.6 | 53.9 | 46.0 | 41.2 |
|      20 | 42.0 | 43.3 | 46.4 | 50.2 | 56.0 | 61.4 | 66.9 |  66.6 | 60.7 | 52.3 | 45.2 | 40.7 |
|      22 | 41.4 | 42.5 | 45.0 | 48.3 | 53.5 | 58.2 | 63.2 |  63.5 | 58.7 | 51.1 | 44.5 | 40.1 |

#### oEmbed

    {{1}}
??[Familienschacht Freiberg](https://sketchfab.com/3d-models/familienschacht-freiberg-germany-7c7d30506c554385a4a4321366e2e601)

    {{2}}
??[Simulation: Noninverting Amplifier](https://www.falstad.com/circuit/circuitjs.html?startCircuit=amp-noninvert.txt)

    {{3}}
??[States of Matter](https://phet.colorado.edu/sims/html/states-of-matter/latest/states-of-matter_all.html)

#### Coding & Reusability

https://github.com/topics/liascript-template


Todo: Music


##### Arduino

<lia-keep>
<div id="example2_div_id">
<wokwi-led color="green" pin="9" port="B" label="B1"></wokwi-led>
<span id="simulation-time"></span>
<memout-element
        type="diagram2"
        outputs="[bytesToInt(data[0x84],data[0x85]), 15625, extractBit(data[0x23],1)*30000 + 260]"
        color="blue"
        min="0"
        max="65536"
        width="800"
        height="300"
        interval="58000000"
        title="TCNT1 und OCR1A"
        colors='["red","blue","green"]'
        labels='["TCNT1","OCR1A","LED"]'
    ></memout-element><br>
</div>
</lia-keep>

```cpp       avrlibc.cpp
#ifndef F_CPU
#define F_CPU 16000000UL // 16 MHz clock speed
#endif

int main(void)
{
  DDRB |= (1 << PB1);  // Ausgabe LED festlegen
  TCCR1A = 0;
  TCCR1B = 0;
  TCCR1B |= (1 << CS12) | (1 <<CS10);  // 1024 als Prescale-Wert
  TCCR1A |= (1 << COM1A0);
  OCR1A = 15625;

  while (1) _delay_ms(500);
}
```
@AVR8jsMem.sketch(example2_div_id,100000,1)


### Hosting

    {{1-2}}
![Library of Alexandria](https://raw.githubusercontent.com/LiaPlayground/University-Future-Festival-2023/main/img/alexandria.jpg)

#### Git

> Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers. It was originally created by Linus Torvalds in 2005 for development of the Linux kernel, and has become the most popular version control system.
>
> _Source: [Wikipedia](https://en.wikipedia.org/wiki/Git)_

    {{1}}

![Git](https://raw.githubusercontent.com/LiaPlayground/University-Future-Festival-2023/main/img/git.png)

#### IPFS & IPNS
<!--
icon: https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Ipfs-logo-1024-ice-text.png/240px-Ipfs-logo-1024-ice-text.png
-->

> The __I__nter__P__lanetary __F__ile __S__ystem (IPFS) is a protocol, hypermedia and file sharing peer-to-peer network for storing and sharing data in a distributed file system ...
> _supported by Opera, Brave-Browser, Agregore, and more to come_
>
> https://ipfs.tech

![IPFS](https://icommunity.io/wp-content/uploads/2020/08/IPFS.jpg)

#### Onion-Share
<!--
icon: https://upload.wikimedia.org/wikipedia/commons/1/15/Tor-logo-2011-flat.svg
-->

!?[Onion-Share Demo](https://www.youtube.com/watch?v=y6tBVNe6mWw&t=1200s)

The [Tor Network](https://en.wikipedia.org/wiki/Tor_%28network%29) is a system that allows users to anonymize their online activities and their identity by routing the data traffic through multiple servers, thereby hiding the source of the data. The network consists of thousands of voluntary servers worldwide that act as "nodes" and encrypt the data traffic to protect the privacy of the users.

__Tor Browser: For anonymous browsing__

* Download & Install: https://www.torproject.org/download/

* Disable private browsing to enable IndexedDB for caching LiaScript courses:

  Settings >> Privacy & Security >> History >> Always use private browsing mode (disable)

* Enable CORS:

  Settings >> Extensions & Themes >> Search for "[CORS Unblock](https://addons.mozilla.org/en-US/firefox/addon/cors-unblock/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)" >> Click on "[CORS Unblock](https://addons.mozilla.org/en-US/firefox/addon/cors-unblock/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)" >> Install (Add to Firefox)

  If you have __disabled private browsing__ mode, enable "CORS Unblock".

  Otherwise, enable the plugin first to be used in private mode:
  Settings >> Extensions & Themes >> "CORS Unblock" >> Run in Private Windows (Allow)


  ![Activate CORS Unblock](https://addons.mozilla.org/user-media/previews/full/213/213890.png?modified=1622134234)


__OnionShare for anonymous hosting and sharing__

* Download & Install: https://onionshare.org
* Open and "Connect to Tor"
* Share data: Start Hosting >> Add Files or Add Folder >> Start sharing
* Send the Onion-Address and the Private-Key to your students
* Open the Onion-Address within the Tor-Browser, enter the private key and select "Remember this key"
* Open the README.md of the course and copy this URL
* Goto https://LiaScript.github.io and paste this URL "click on Load URL"


#### Learning Management Systems

[LiaScript-Exporter](https://www.npmjs.com/package/@liascript/exporter) exports to:

- SCORM 1.2 & 2004
- PDF
- IMS
- Projects
- RDF / Metadata
- Android APK

    {{1}}
!?[LiaScript in Moodlet](https://www.youtube.com/watch?v=yk4uEqoKcpw)


## Classrooms-Lite

<div style="width:100%;height:0;padding-bottom:75%;position:relative;"><iframe src="https://giphy.com/embed/fVPzDNORY7A3szWDil" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/fVPzDNORY7A3szWDil">via GIPHY</a></p>

### Peer^2^Peer in da Browser

    {{1-2}}
``` ascii    __Fig:__ Classic Client & Server Applications
    👨🏾‍💻 --.     .-- 👩‍💻
          \   /

👩‍💻 ------  🖥️  ------ 👨🏾‍💻

          /   \
    👨🏾‍💻 --'     '-- 👩‍💻
```

    {{2}}
``` ascii    __Fig:__ Peer^2^Peer- or Mesh-Networks
- - - --👨🏾‍💻-----👩‍💻
              /  \
             /    \
    👩‍💻------+-----👨🏾‍💻- - -
      \    /      /
       \  /      /
        👨🏾‍💻     👩‍💻- - - -
```

### WebRTC

> The __Web Real-Time Communication__ is a free and open-source project providing web browsers and mobile applications with real-time communication (RTC) via application programming interfaces (APIs).
> It allows audio and video communication to work inside web pages by allowing direct peer-to-peer communication, eliminating the need to install plugins or download native apps...
>
> _Source: [Wikpedia](https://en.wikipedia.org/wiki/WebRTC)_


    {{0-1}}
``` ascii
                     (WebRTC)
Alice 👩‍💻 <------------------------------> 👨🏾‍💻 Bob
```

    {{1}}
``` ascii
               (Signaling Server)

       .-------------> 🖥️ --------------.
       |    "{1}{}"   /  A      "{2}{}" |
       |             /    \             |
       |            /      \            V
                   /        \
Alice 👩‍💻 <--------'          '--------- 👨🏾‍💻 Bob
            "{4}{}"             "{3}{}"
      A                                  A
      |                                  |
      '----------------------------------'
      A    "{5}{Direct Communication}"   A
      |                                  |
      '-- - - - - - - - - - - - - - - - -'
             "{6}{InDirect via TURN}"
```

    {{7}}
> More confusing information on WebRTC:
>
> !?[WebRTC](https://www.youtube.com/watch?v=7cbD-hFkzY0)


### CRDTs

A _**C**onflict-free **R**eplicated **D**ata **T**ype_ (CRDT) is a new type of data structure[^1] that can be replicated across multiple instances in a network with the following guarantees:

    {{1}}
1. A replica can be updated independently, concurrently and without coordinating with other replicas.
2. Inconsistencies can be resolved automatically.
3. Although replicas may have different state, they are guaranteed to eventually converge.

    {{2}}
__Task:__ Implement an distributed counter

    {{3}}
``` ascii
Alice 👩‍💻

[0]---------*-->[5]--[+1 = 6]--------*-->[8]-- - - - - - - - - - - - 
           /            \           /          \
          A              V         A            \
         /                        /              \
[0]---[+5 = 5]-----------------[+2 = 7]-- - - - --*- - - - - - - - - -

Bob 👨🏾‍💻
```

    {{4}}
__Solution:__ Use Sets and Unions instead... 

    {{5}}
``` ascii
Alice 👩‍💻

{(a,0)}----------*-->{(a,0),(b,5)}->{(a,1),(b,5)}---*-->{(a,1),(b,7)}
                /                         \        /   
               A                           V      A   
              /                                  /
{(b,0)}---{(b,5)}----------------------------{(b,7)}-----------------

Bob 👨🏾‍💻
```

    {{6}}
<section>

__ Implementations__

- [Automerge](https://automerge.org)
- [__Yjs__](https://docs.yjs.dev)

</section>


[^1]: The CRDT concept was defined in 2011 by Marc Shapiro, Nuno Preguiça, Carlos Baquero and Marek Zawirski.

      See also: https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type





### Enter

go to: [Freiberg-Classroom](https://LiaScript.github.io/course/?https://raw.githubusercontent.com/LiaPlayground/Freiberg-Research-Seminar-2024/main/README.md#22)

select >> Share >> Classroom >> GunDB >> Freiberg

---

[qr-code](https://liascript.github.io/course/?eyJiYWNrZW5kIjoiR1VOfGZ8aHR0cHM6Ly9wZWVyLndhbGxpZS5pby9ndW4iLCJjb3Vyc2UiOiJodHRwczovL3Jhdy5naXRodWJ1c2VyY29udGVudC5jb20vTGlhUGxheWdyb3VuZC9GcmVpYmVyZy1SZXNlYXJjaC1TZW1pbmFyLTIwMjQvbWFpbi9SRUFETUUubWQiLCJyb29tIjoiRnJlaWJlcmcifQ==#22)


### Trying


What is the name of the language you have been learning today.

[[LiaScript]]

Is it possible that browsers can communicate directly with each other?

[(X)] Yes
[(X)] It depends
[( )] No

#### Questions

How would you rate the distributed approach?

[(good)]         It is quite good
[(ok)]           It is ok
[(bad)]          It is bad
[(intermediate)] Well, it depends
[(no way)]       No way
[(undefined)]    I don't know...

---

Share your feelings:

<script run-once="true">
LIA.classroom.subscribe("wave", (msg) => {
    const icon = document.createElement("span")
    icon.innerHTML = msg
    icon.classList.add("fall")
    icon.style.left=(Math.random() * 100) + "%"
    icon.style.zIndex = 10000
    document.body.appendChild(icon)
    icon.addEventListener('animationend', function() {
        icon.remove();
    });
})
console.log("subscription")
</script>

<script input="button" run-once="true" modify="false">
if (LIA.classroom.connected){
    LIA.classroom.publish("wave", "👋")
}

"👋"
</script>
@wave(❤️) @wave(👎) @wave(👍) @wave(💀) @wave(❓)

## Remote Labs

__Original Edrys:__ https://github.com/edrys-org/edrys

![Original Edrys](https://raw.githubusercontent.com/edrys-org/edrys/main/docs/stations/structure.png)



    {{1}}
__Edrys-Lite:__ https://cross-lab-project.github.io/edrys-Lite/


