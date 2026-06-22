# Maker100 Leaders Robotics
## Decentralized Edge AI Education for Global Technological Empowerment
### AI for Good, Geneva 2026 | Jeremy Ellis | ~15 minutes

---

## REVISED ABSTRACT

**Session Title:**
Maker100 Leaders Robotics: Student-Led Edge AI Education for Global Technological Empowerment

**Session Description:**

How do we equip youth, particularly in underserved regions, to become active creators rather than passive consumers of artificial intelligence? This keynote presents an actionable blueprint to bring an open-source, zero-lecture robotics and Edge AI curriculum to the Global South, targeting students in grades 9–12 with an ultra-affordable hardware stack. Built on over three decades of classroom experience, the Maker100 Leaders Robotics framework pairs 40–60 hands-on, asynchronous hardware challenges with an entry-level $15 USD ESP32S3 microcontroller kit, expanding seamlessly into a full physical stack of sensors, actuators, and IoT modules to bridge the digital divide.

The course eliminates the need for specialized instructors, cloud fees, or stable internet by relying on three core protocols to build a self-sustaining classroom culture. First, the Analog Firewall enforces computer-free, paper-based conceptual design before students touch hardware. Second, the Lead Three social protocol decentralizes knowledge transfer, requiring the first student who solves a challenge to peer-teach three others. Third, open-source LLMs are deployed offline as Progressive Web Apps (PWAs) to serve as private, surveillance-free debugging TAs.

Embedded within the course is the Sovereign AI Engine (webmcu-ai), a browser-native framework running complete machine learning pipelines—including vision, sound, and motion classification—entirely on-device via WebSerial. Featuring live demonstrations of on-device ML training and offline local inference, this session shifts the paradigm of tech education. It concludes with a direct leadership challenge to the youth in the room to take ownership, calculate the costs, and activate this open-source pilot in their own communities, proving that impactful global tech leadership begins by mastering physical micro-hardware.



## PRESENTATION SCRIPT

---

### THE RED WIRE STORY

I want to start with a story from my robotics class.

A three-person team was falling apart over their final project, a robot arm with IoT sensors and a tiny vision ML loop. The leader was brilliant. The pre-engineer was meticulous. And yet the system kept failing, working one moment, collapsing the next.

Beside them stood the third student. Quiet. Barely passing the course.

After another failure, he spoke up gently: *"What if the red wire isn't working?"*

The leader froze. The pre-engineer sighed. You could feel the tension, but, he said, that is an easy test, and swapped to a different red 3.3V breadboard wire.

Instantly, the entire robot came alive. Smooth. Stable. Perfect.

The breakthrough didn't come from expertise. It came from inclusion. From giving space to the voice no one expected to matter.

Now imagine a world where only a handful of powerful cloud companies get to decide how we solve society's hardest problems. That's a world with only two students at the table.

We need the third student. We need the unexpected insight. The simple truth that experts miss.

Democratizing AI isn't optional. It's how we keep the future from failing because of a bad VCC line.

And for the record, in my class we never throw away equipment students call broken. But that day, we held a small ceremony... and tossed that little red wire straight into the garbage.

---

### WHO I AM AND WHY I'M HERE

I am Jeremy Ellis. I have taught technology for over 30 years in British Columbia, Canada.

I founded the GitHub organization webmcu-ai, a framework for fully on-device machine learning training. I help co-chair the AiEng4D Show and Tell, where Global South university students present their TinyML and Edge AI projects online.

Today I am presenting a pilot project to bring my student-led robotics course to the Global South, and I am asking the student leaders in this room to help make it happen.

---

### THE PROBLEM, AND THE STUDENTS WHO SOLVE IT

Students today are looking at an uncertain future. They see artificial intelligence changing every industry.

They have a choice: ride along with technology built by others, or learn how it works and become the people who build what comes next.

Throughout my career I have watched that choice play out in classrooms. And I've learned something important.

I don't teach pre-engineers, students who build things and love the complexity of math and physics. They teach me.

I also don't teach leaders. Leaders are students who look outward while digging deeper.  I put students into situations where they discover they are leaders.

---

### THE COURSE, MAKER100 LEADERS ROBOTICS

This is not an easy course.

Students solve 40 to 60 robotics, machine learning, sensor, actuator, and IoT challenges, and then teach others their solutions.

No full lectures. Students or the teacher record all 60-plus assignments on a public or private chart, solved in any order.

**The Rule of Lead Three:** If you are the first person to solve an assignment, you must teach three others. Those three are responsible for helping three more. The maximum mark of 90% gets closer to 100% as that classroom tone of collaboration increases.

I am completely comfortable with ten students earning 100 percent. It hurts no one, and it massively improves classroom tone, communication, confidence, and joy.

**The Analog Firewall:** The class always starts here. Code is summarized on paper before loading onto a microcontroller. Circuit diagrams are drawn by hand and checked by another student before wiring. Power is connected only after a second check.

Why? Because thinking before acting is a professional habit. And because a hardware failure caught on paper costs nothing. A hardware failure caught after a short circuit has a real cost.

**LLMs as lab assistants:** Students learn to ask AI for help, understand the answer, verify it, improve it, and eventually build their own tools. AI becomes a lab assitant, debugger and a tutor, not a replacement for understanding.

Once assignments are complete, students do Level 1 and Level 2 final projects. Level 1 is a course pass. Level 2 earns the higher mark. Multiple people are expected to reach the top grade.

The course is at **github.com/hpssjellis/maker100-leaders-robotics** open source, free, and can be updated.

---

### LOCAL AI WHY IT MATTERS

Teenagers are already using AI assistants. The question is whether they understand these tools, or become dependent on them.

Why not load an LLM locally using an installable webpage, a Progressive Web App?

A student computer becomes a private AI lab assistant without sending every question and every piece of student data somewhere else.

> **Demo: Local Gemma 2B and 12B via PWA**

Privacy alone makes this worth doing. But the deeper idea is this: if advanced AI requires a few enormous companies, most people become consumers. If we can put AI tools into classrooms everywhere, students become creators.

---

### ON-DEVICE MACHINE LEARNING, THE FULL PIPELINE

The industrial approach to machine learning is to send your data to the cloud and receive a fully trained model back.

But what if the entire pipeline could run on the microcontroller itself?

Many would say that's impossible, TensorFlow Lite is too large, the hardware too constrained. But I wanted to understand it from first principles. With the help of LLMs, I built the entire training and inference pipeline from scratch on the XIAO ML Kit.

I must acknowledge Vijay Reddi, a member of AiEng4D, whose tinyTorch project and mlsysbook.ai inspired that from-scratch philosophy.

The XIAO ML Kit is built around the Seeed Studio XIAO ESP32S3 Sense, a microcontroller that costs under $15 USD. That price matters. A school can equip a classroom without a massive grant. A student can experiment. A teacher can replace broken parts.

We have working pipelines for:
- Vision classification
- Vision object detection FOMO with XY coordinates
- Anomaly detection
- Sound classification
- Motion classification

The first WebSerial training system took 147 versions. That is also part of the lesson. Real technology is not created perfectly the first time. You build. You test. You improve. You learn.

> **Demo: webmcu-ai on-device training and inference**

---

### THE PILOT PROPOSAL, YOUR LEADERSHIP CHALLENGE

This is where the presentation changes direction.

Maker100 Leaders Robotics needs the leaders in this room, you, to calculate the cost of running this pilot at your school and to find the funding.

You are in one of the best places on the planet to do that.

Here is what you need:

- At least **three pre-engineers** willing to work hard
- **3 to 30 students**, grades 9 to 12
- **~$200 USD per student** to start; ~$50 USD each year or semester for replacement parts. Yes, we break things. That is part of the learning.
- Access to a **computer lab**, ideally with a 3D printer
- A teacher willing to complete every assignment alongside the students

If your teacher is willing to learn and complete the work, I will support that class three times during the first course: at the start for safety, in the middle when students hit problems they cannot solve alone, and near the end for the most challenging Level 2 assignments. If you instructor is an arduino wiard and already has an EdgeImpulse login, they may want to do the course without contact, and connect next year.

Calculate your student count, calculate your total cost, and solve the funding problem. That is not my job. But knowing where the money comes from is your first real leadership challenge.

---

### WHAT I LEARNED FROM STEPPING BACK

In 30 years teaching I have never had a student win a large scholarship, last year I took a semester off. I was not there to quickly solve my students' problems. They struggled, but they learned deeper.

From that class, two students received over $100,000 canadian dollar scholarships: a grade 12 girl one the Canadian Schulich scholarship, and the other an then grade 11 boy, this year won the Canadian Loran Scholarship.

That taught me something important. I am the least important part of this course. The hardware, the curriculum, the Lead Three, the Analog Firewall, and the classroom culture those are the important parts.

Remember no strain, no  (cognitive, social, emotional, or physical) gain. Those scholarships students were impressive without my course, but the course may have helped them realize how capable they were.

---

### CLOSING

In one year, we meet again. Some schools will have tried. All will have struggled. Some students will have created things none of us expected.

The question is simple: Which leaders will stand here, armed with hard-won data, to tell us what their class built? The schools that succeed here won’t just celebrate their own wins, they will become the blueprint to scale this globally to raise the funds for those who couldn't start today.

First, you build for your community. Then, you lead for the world. That question is not for me. It is for the leaders in this room. We need the third student at the table. We need the voice no one expected. We need the person who sees the simple truth the experts miss.

Don't let the future fail because of a bad red wire.

Thank you.
