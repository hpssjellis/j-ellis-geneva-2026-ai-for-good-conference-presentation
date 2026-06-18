
I am Jeremy Ellis, founder of the GitHub organization webmcu-ai, and I help run the Show and Tell for AIEng4D, where Global South university students present their TinyML 
and Edge AI machine learning projects online.

I have taught technology for over 30 years in BC, Canada, and I am presenting to you a pilot project to bring my student-led Robotics course to the Global South. 
During this hands-on, dopamine-replacement course, students solve 40 to 60 robotics assignments, machine learning, sensors, actuators, IoT problems, and teach others 
their solutions. No full lectures. LLMs are lab assistants. Collaboration is grade-rewarded, but we don't do group work until the very end of the course. An Analog Firewall 
means written code summaries and hand-drawn circuit diagrams before anything touches hardware. On-device ML and cloud ML, with on-device AI assistance or cloud LLMs. 
The entire course is designed for hands-on learning, poor internet, and low cost. Who is interested?

Throughout my teaching career, I have had students solve technology issues as a class. I don't teach pre-engineers, students who do well in math and physics and love 
building things, they teach me. I also don't teach leaders, students who look outward while digging deeper, I put them in situations to do what leaders do. With that in mind:
Maker100 Leaders Robotics needs the leaders in this room to calculate the cost to run this pilot at their school and find the funding. You are in one of the best places on the planet to 
raise funding. For your cost calculation you need at least 3 pre-engineers. Check with your supervisor for help to pick a number of students from 3 to 30 in grades 9-12, calculate hardware from supplier costs, which are 
approximately $200 USD per student to start and $50 USD each year or semester for replacement parts. Yes, we break equipment. Once you have your number of students and the 
years or semesters to run the program, calculate a final cost and solve the funding issue. That is not my job, but be aware of where the money is coming from.
If your teacher wants to learn the technology and is willing to do every assignment, I will help three times during the first course: at the start for safety, 
in the middle to solve problems your students could not solve, and near the end to help with the difficult Level 2 assignments. If your teacher is already an 
Arduino wizard, you can run the first year or semester without any contact. We meet back here next year, and if the results are positive, we look for Global South funding 
for multiple years. This course is hard. You leaders have to want it.

For a break, let's do something different.
I feel that teenagers should not be using cloud LLMs for every little problem. Why not load an LLM locally using an installable webpage called a PWA, a Progressive Web App?
Demo: Gemma4 2B and 12B (10 minutes)

Let's get into the course: Maker100 Leaders Robotics.
Pre-engineers can be leaders, but leaders do not need to be pre-engineers. Pre-engineers don't have to become engineers either, they gain skills that work across many fields. 
Either way, this course will challenge everyone in it.
Record all 60-plus assignments on a public or private chart, solved in any order. The Rule of Lead Three: if you are the first to solve an assignment, you must teach three others, 
and they are responsible for helping three more. The class's highest mark, 90 to 100 percent, comes from the tone of people helping each other. Once the 40 to 60 assignments 
are complete, students do their Level 1 and Level 2 final projects. Level 1 is a course pass; Level 2 earns the higher mark. Multiple people are expected to reach the top grade. 
I am fine with ten students all getting 100 percent, it hurts no one and massively improves pre-engineers' communication skills and the tone of the class.
The class always starts with the Analog Firewall: code is summarized on paper before loading onto a microcontroller, circuit diagrams are drawn by hand and checked by a 
Lead Three before wiring, and power is only connected after a second check. Students are encouraged to plan before they arrive.
Leaders do the assignments and extend them, make them their own, dig deeper, think about applications. That balance between sheer volume of work and the massive real-world 
applications of almost every assignment is the most powerful part of the course.
The course is at github.com/hpssjellis/maker100-leaders-robotics, open source, free, dynamic, and updated as issues are found. It has links to the Maker100 curriculum, 
a dynamic price list, and webmcu-ai.
Students will learn Arduino-style basics, foundational coding, sensors, light, motion, sound, actuators, motors, LEDs, machine learning for vision, sound, and motion, 
and IoT multi-device communication. Some assignments are easy, some are challenging. The faster students finish, the more time they have for final projects, and if they 
finish those, they start another.

So far we have covered: the pilot needing student leaders and funding, local and cloud LLMs, and how students help each other while working independently. But what about ML?
The industrial approach is to send your data to the cloud and have it return your trained model. What if the entire ML pipeline could run on the microcontroller itself?
Most engineers will tell you TensorFlow Lite or PyTorch is too large for on-device training, that quantization from 32-bit to 8-bit is too advanced, that you train offsite 
and only put inference on the machine. But I am not an engineer, I am a decade-long expert in WebAI and TinyML, and with LLM assistance I got the entire pipeline onto the 
XIAO ML Kit from first principles, with no TFLite.
The XIAO ML Kit is built around the Seeed Studio XIAO ESP32S3 Sense, a microcontroller that costs well under $20 USD. That low price is critical for Global South classrooms. 
The base MCU being affordable means a school can equip a full class without a large grant.
Demo: webmcu-ai

What did you just watch? The ability to run the full ML pipeline on a microcontroller. Why does that matter? Because leaders need to understand what is happening to think 
beyond the cloud. The privacy alone is impressive. But I believe a few students will look at that under-2000-line codebase and truly understand how some simple ML works, 
not as a black box, but from the ground up.
We have code for vision classification with a WebSerial-assisted training page, vision object detection with XY coordinates (FOMO), vision anomaly detection, vision 
regression for distance and size, sound classification, and motion classification. We don't yet have WebSerial training pages for all of those, that adds significant 
complexity, but the first one took 147 versions, so they will come.

You have heard about Maker100 Leaders Robotics: a course that is difficult by design, but one that allows students to grow their pre-engineering skills and leadership 
skills while working hands-on with robotics, machine learning, and IoT, entirely on low-cost, low-connectivity hardware.
Thank you.
