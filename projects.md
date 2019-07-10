---
layout: page
title: Projects
---
Ah, the infamous projects page each software developer's website needs. I will only be listing a few selected projects here. You can start by visiting my [Freelancer](https://www.freelancer.com/u/livingincode.html) and [Github](https://github.com/shahidkhaliq) profiles to check out some of the projects I have completed and those I'm currently working on. If you'd like to talk to me about any of my projects or if you need my expertise for one of your own, don't hesitate getting in touch with me personally ([LinkedIn](https://www.linkedin.com/in/shahidkhaliq), [Facebook](https://www.facebook.com/shahidkhaliq13), [Email](mailto:s3khaliq@uwaterloo.ca?Subject=Hi%20Shahid!)).

<ul>
	<li>
		<a href="/public/kvstore.pdf" target="_blank"><b>KVStore:</b></a> This project was done as part of my Advanced Topics in Operating Systems graduate course in my first term at the University of Waterloo. I was in a team of three and the idea behind the project was to build an RDMA-based distributed shared memory key-value store. I implemented the store in C++ on top of an RDMA library written by one of my group mates. The key-value store supported multiple data block sizes to conserve memory and used cuckoo hashing to counter against hash collisions. A lot of thought went into designing the data storage scheme such that processes executing on different servers could access the shared memory simultaneously without any coordination.
	</li>
	<br/>
	<li>
		<a href="https://youtu.be/RSlZ23rdSfk" target="_blank"><b>Model VR:</b></a> A virtual reality enabled collaborative 3D model editor which allowed users six directional hand movements. It was written in Unity 3D and worked with Google cardboard and Razer Hydra motion controllers. Users could join virtual rooms and create 3D models collaboratively around themselves in virtual space. I worked mostly on the collaboration module and used remote procedure calls for most of the required functionality. This project was selected as one of the top three final year projects of the Software Engineering batch of 2016 by the faculty of SEECS, NUST.
	</li>
	<br/>
	<li>
		<b>MICR Reader:</b> This project was done for one of my clients on Freelancer. The aim was to read Magnetic Ink Characters from the bottom of bank cheques. I used a .Net wrapper of the very popular Tesseract OCR engine. I found the training data for it on Google groups. I needed to preprocess the image before passing it to the Tasseract engine. I used the ImageProcessor library for that. Increasing the contrast a bit can really improve OCR!
	</li>
	<br/>
	<li>
		<b>Stanford's Pintos Projects:</b> I'm currently doing these projects in my free time. I've completed the first one but I had to take down the public repository from Github at Stanford's request because apparently it makes it easier for their students to cheat. Fortunately, I still have the code with me and can provide it on request (not to students!).
	</li>	
	<br/>
	<li>
		<b>MulProx: </b> I did this project as part of my Distributed Computing course in my seventh semester at university. It was a fairly simple project. The idea was to create a P2P overlay network with each
		node acting as an HTTP proxy. An HTTP request from a node in the overlay network would be sent to another random node and then get bounced around the overlay network a random number of times before eventually reaching the destination server. The reply would follow the same chain backwards.
	</li>
	<br/>
	<li>
		<b>Reliable UDP in Python:</b> This was my project for the Computer Networks course in my fifth semester. We had to make UDP reliable by creating an application layer protocol on top. I did this by selective repeat and my project was one of the few which passed additional secret tests developed by the teacher (we were given five tests initially). You can find the repository for this project on my Github.
	</li>
	<br/>
	<li>
		<b>Kernel Patch for Linux (Incomplete):</b> This project was done for my Operating Systems class and was mostly a failure. Our aim was to develop a Linux kernel patch which added system calls to the Linux kernel allowing user applications to recover deleted files or to do the opposite by making them unrecoverable. Unfortunately, we underestimated the time and effort required for this project. We later realised that we should have developed a kernel module instead (would have been easier and makes more sense). I mention this project here because even though we accomplished nothing, I learned a lot about Linux kernel patching and compilation and file formats such as NTFS and EXT4. That knowledge on it's own means a lot. We scored well in the project when we presented all we had learned and the reasons (problems and complexities) for our failure.
	</li>
	<br/>
	<li>
		<b>Rideshare (Carpooling website):</b> This was a small website project for the Web Engineering course in my fifth semester. I developed a website from scratch using Bootstrap. The back end was written in PHP.
	</li>
	<br/>
	<li>
		<b>Web based learning management system:</b> I was in a team of ten people for this project. I was actually leading a sub team of five. Our aim was to create a better version of the learning management system in use at our university. I'm proud to say we succeeded. The project was done for the Software Design and Architecture course in my fourth semester. We used the PHP MVC Laravel Framework for it. The responsibility of my team was to work on all the controllers in the project. The models were very bare bones so a lot of the logic had to be implemented in the controllers. Major features were:
		<ol>
			<li>Complete teacher/student portal</li>
			<li>Attendance marking</li>
			<li>Grades marking</li>
			<li>Course contents</li>
		</ol>
	</li>
	<br/>
	<li>
		<b>Mood based music player:</b> This project was done for my Data Structures and Algorithms class in the third semester of my study. It was a big project with a web service and an android
		application. You basically told the application what your mood was and the application got a list of songs from the server to play on your phone. But it wasn't as simple as that. For any given song,
		the webservice would check if it existed in it's database. If it didn't, the webservice would crawl the web looking for the song's lyrics. When found, it would analyze them by running an algorithm which would classify the song in a mood. We had a database of words ranked by emotion. For example, the word 'love' was a 10 in romantic mood. There are cases where this didn't work. But surprisingly enough, it did work most of the time. With our limited knowledge back then, we couldn't avoid the drudgery of ranking a few hundred frequently used words on the basis of what context they were mostly used in. A few notable features of the project were:
		<ol>
			<li>A web service (web crawler, classification algorithm)</li>
			<li>A frontend on the web (administrator panel for word ranking, approving the algorithms classification of a song and general statistics)</li>
			<li>An android app (music player)</li>
		</ol>
	</li>
	<br/>
	<li>
		<b>Remote PC Control Software:</b> This was one of my first major projects. It was done for my Object Oriented Programming class in the second semester of my study. 
		The project was mostly done because I had no better idea at the time and I could have experimented in a lot of different areas with this one. I used Qt framework and 
		made use of a lot of things which hadn't been taught to us in class back then. These included networking and threading for example. The use case of the project was that parents
		could monitor their childrens activities on computers. It was a big project with the following features:
		<ol>
			<li>Keystroke logging (even when the server is down)</li>
			<li>Fully functional remote file manager (download, upload, delete, move, etc.)</li>
			<li>Live screenshot capture</li>
			<li>Remote program execution</li>
			<li>System command execution</li>
			<li>Simple chat (because why not!)</li>
		</ol>
	</li>
</ul>