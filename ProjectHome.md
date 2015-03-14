<b>An open design exercise in interface archaeology,<br>
that decodes the input from a classic Morse telegraph to send twitter messages.</b>
The Tworse Key is a standalone device that connects through a standard LAN cable, the Morse signals are decoded by the built-in Arduino Ethernet board, which delivers the final message though the Twitter API. Please follow <a href='http://twitter.com/tworsekey'>@tworsekey</a> on Twitter to read some example tweets sent from the actual device.

<a href='http://flattr.com/thing/984810/Tworse-Key'>
<img src='http://api.flattr.com/button/flattr-badge-large.png' alt='Flattr this' border='0' title='Flattr this' /></a>

<a href='http://www.youtube.com/watch?feature=player_embedded&v=V9KckRf_MKo' target='_blank'><img src='http://img.youtube.com/vi/V9KckRf_MKo/0.jpg' width='640' height=360 /></a>

This project is fully documented in order to illustrate the Open Design process for beginners, who are aiming to realize a simple but appealing Arduino project. Apart from reading the input from the Morse switch, the device also provides basic auditory and visual feedback, which have been integrated using a very elementary circuit. The source code, hardware schematics and building instructions are therefore available under the according free licenses. (cc-by-sa) 2012 by <a href='http://modin.yuri.at/'>Martin Kaltenbrunner</a>, <a href='http://www.interface.ufg.ac.at/'>Interface Culture Lab</a>, <a href='http://www.ufg.ac.at/'>Kunstuniversität Linz</a>

<img src='http://modin.yuri.at/tworsekey/tworsekey_total.jpg' width='400' height='300'>
<img src='http://modin.yuri.at/tworsekey/tworsekey_total_inside.jpg' width='400' height='300'>
<br />

<b>software requirements:</b>
<ul><li><a href='http://arduino.cc/en/Main/Software'>Arduino 1.0</a> (or later)<br>
</li><li>Twitter <a href='http://arduino-tweet.appspot.com/'>library</a> by <a href='http://twitter.com/NeoCat'>@NeoCat</a>
</li><li>the latest <a href='https://code.google.com/p/tworsekey/downloads/list'>TworseKey</a> sketch for Arduino provided here.</li></ul>

<b>hardware requirements:</b>
<ul><li>Morse Key (search on <a href='http://www.ebay.com/sch/i.html?_nkw=morse+key'>Ebay</a>)<br>
</li><li><a href='http://arduino.cc/en/Main/ArduinoBoardEthernet'>Arduino Ethernet</a> board (or alternatively an Arduino plus Ethernet shield)<br>
</li><li>piezo buzzer for auditory feedback<br>
</li><li>50 Ohm resistor to connect the buzzer<br>
</li><li>RGB LED (common anode) for visual feedback<br>
</li><li>10k Ohm resistor to connect the LED (reducing its brightness)</li></ul>

<b>additional requirements:</b>
<ul><li>a RJ45 ethernet cable<br>
</li><li>9V Battery + connector (for internal use)<br>
</li><li>5V power supply (for external use)<br>
</li><li>USB FTDI cable to program the Arduino Ethernet board<br>
</li><li>a wooden box to mount the electronics and Morse key<br>
</li><li>various cables and soldering equipment</li></ul>

<b>schematics:</b><br />
<img src='http://modin.yuri.at/tworsekey/tworsekey_schematics.png' width='640' height='400'><br />
The according <a href='http://fritzing.org/'>Fritzing</a> sketch is included in the source code.<br>
<br>
<b>references:</b><br />
In a typical case of convergent evolution, there already exist similar projects by <a href='http://instamatique.com/lea/about.html'>Lea</a> and <a href='http://homepage.mac.com/joester5/art/'>Joe McKay</a>: <a href='http://instamatique.com/lea/Ditter.html'>Ditter</a> was first exhibited in late 2009 at a Pittsburgh art gallery, similar to the <a href='http://homepage.mac.com/joester5/art/tweetagraph.html'>Tweetagraph</a> prototype from early 2011 that decodes the input from a Morse key to send Twitter messages through a Processing sketch. Joe also documented and published his code on his web page, and although the Tworse Key was developed independently, you may consider it an evolution of the earlier projects, which again emphasizes the Open Design principle. The major improvement compared to Ditter and the Tweetagraph is the standalone design of the final Tworse Key device. David Bern also sent in an earlier <a href='http://www.arrl.org/files/file/QEX_Next_Issue/May-Jun_2010/Bern.pdf'>experiment</a>, where he explains how to hook up a Morse telegraph to a computer emulating a PS/2 keyboard.<br />

<b>selected media coverage:</b>
<ul><li>Telegraph key makes for a fantastic Twitter input <a href='http://hackaday.com/2012/01/31/telegraph-key-makes-for-a-fantastic-twitter-input'>Hackaday</a>, 31.01.2012<br>
</li><li>Typing too easy for you? Try posting to Twitter via morse code <a href='http://thenextweb.com/shareables/2012/01/31/typing-too-easy-for-you-try-posting-to-twitter-via-morse-code/'>The next Web</a>, 31.01.2012<br>
</li><li>Tweet in Morse code with Tworse Key <a href='http://news.cnet.com/8301-17938_105-57370514-1/tweet-in-morse-code-with-tworse-key/'>CNET</a>, 02.02.2012<br>
</li><li>모스 부호로 트위터 해봤어요? <a href='http://www.zdnet.co.kr/news/news_view.asp?artice_id=20120203085517'>ZDNet Korea</a>, 02.02.2012<br>
</li><li>Tworse Key lets you tweet in Morse code, <a href='http://www.theverge.com/2012/2/2/2765802/tworse-key-morse-code-twitter'>The Verge</a>, 02.02.2012<br>
</li><li>Morsen ist das neue Twittern,  <a href='http://de.engadget.com/2012/02/02/tworse-key-morsen-ist-das-neue-twittern-video/'>Engadget DE</a>, 02.02.2012<br>
</li><li>Twitternde Morsetaste,  <a href='http://www.heise.de/mach-flott/meldung/Twitternde-Morsetaste-1427399.html'>Heise</a>, 03.02.2012<br>
</li><li>Now You Can Tweet in Morse Code,  <a href='http://gizmodo.com/5881995/now-you-can-tweet-in-morse-code'>Gizmodo</a>, 03.02.2012<br>
</li><li>Tworse Key: Post to Twitter using morse code,  <a href='http://newslite.tv/2012/02/03/tworse-key-post-to-twitter-usi.html'>Newslite</a>, 03.02.2012<br>
</li><li>Twittern wie im 19. Jahrhundert,  <a href='http://futurezone.at/digitallife/7288-twittern-wie-im-19-jahrhundert.php'>futurezone</a>, 06.02.2012<br>
</li><li>Tweeting in Morse Code,  <a href='http://arduino.cc/blog/2012/02/07/tweeting-in-morse-code/'>Arduino Blog</a>, 07.02.2012<br>
</li><li>Microblogging and the telegraph: Victorian Twitter, <a href='http://www.economist.com/blogs/babbage/2012/02/microblogging-and-telegraph'>The Economist</a>, 15.02.2012<br>
</li><li>Now tweet using the Morse Code, <a href='http://www.sunday-guardian.com/technologic/now-tweet-using-the-morse-code'>The Sunday Guardian</a>, 11.03.2012</li></ul>




