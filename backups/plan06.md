# Maker100 Leaders Robotics
## Decentralized Edge AI Education for Global Technological Empowerment
### AI for Good — Geneva 2026 | Jeremy Ellis | ~15 minutes

---

## REVISED ABSTRACT

**Session Title:**
Maker100 Leaders Robotics: Student-Led Edge AI Education for the Global South

**Session Description:**
How can we equip youth — particularly in underserved regions — to become active creators rather than passive consumers of artificial intelligence? This keynote presents a pilot proposal for an open-source, zero-lecture robotics and Edge AI curriculum designed for six Global South schools, targeting students in grades 9–12 with hardware costs of approximately $200 USD per student.

Built on over three decades of classroom experience, the Maker100 Leaders Robotics course pairs hands-on hardware challenges with affordable microcontrollers ($8–40 USD) to bridge the digital divide. Two core protocols structure the course: the *Analog Firewall*, where students design code summaries and circuit diagrams on paper before touching hardware, and *Lead Three*, a peer-teaching system where the first student to solve each challenge must teach three others. Together these protocols build a self-sustaining classroom culture — one where the teacher is intentionally the least important part.

The course features a browser-native Sovereign AI Engine (webmcu-ai) that runs complete machine learning pipelines — vision, sound, and motion classification — entirely on-device, without cloud subscriptions or high-speed internet. Local LLMs deployed as Progressive Web Apps serve as private lab assistants, giving students access to AI without surveillance. The session includes live demonstrations of both on-device ML training and offline local LLM inference, and closes with a direct call to the student leaders in the room to calculate the cost of running this pilot at their schools and take ownership of making it happen.

---

## PRESENTATION SCRIPT

---

### OPENING — THE RED WIRE STORY
*(~2 minutes)*

I want to start with a story from my robotics class.

A three-person team was falling apart over their final project — a robot arm with IoT sensors and a tiny vision ML loop. The leader was brilliant. The pre-engineer was meticulous. And yet the system kept failing — working one moment, collapsing the next.

Beside them stood the third student. Quiet. Barely passing. Never the one who thought he belonged in the "smart group."

After another failure, he spoke up gently: *"What if the red wire isn't working?"*

The leader froze. The pre-engineer sighed. But they tried it — swapped to a different 3.3V line.

Instantly, the entire robot came alive. Smooth. Stable. Perfect.

The breakthrough didn't come from expertise. It came from inclusion. From giving space to the voice no one expected to matter.

Now imagine a world where only a handful of powerful cloud companies get to decide how we solve society's hardest problems. That's a world with only two students at the table.

We need the third student. We need the unexpected insight. The simple truth the experts miss.

Democratizing AI isn't optional. It's how we keep the future from failing because of a bad VCC line.

And for the record — in my class we never throw away equipment students call broken. But that day, we held a small ceremony... and tossed that red wire straight into the garbage.

---

### WHO I AM AND WHY I'M HERE
*(~1.5 minutes)*

I am Jeremy Ellis. I have taught technology for over 30 years in British Columbia, Canada.

I founded the GitHub organization webmcu-ai — a framework for fully on-device machine learning training. I help co-chair the AiEng4D Show and Tell, where Global South university students present their TinyML and Edge AI projects online.

Today I am presenting a pilot project to bring my student-led robotics course to the Global South — and I am asking the student leaders in this room to make it happen.

---

### THE PROBLEM — AND THE STUDENTS WHO SOLVE IT
*(~1.5 minutes)*

Students today are looking at an uncertain future. They see artificial intelligence changing every industry.

They have a choice: ride along with technology built by others, or learn how it works and become the people who build what comes next.

Throughout my career I have watched that choice play out in classrooms. And I've learned something important.

I don't teach pre-engineers — students who naturally love math and physics. They teach me.

I also don't teach leaders. I put students into situations where they discover they already are leaders.

Leaders are students who look outward while digging deeper. They are not always the top academic. They are sometimes the quiet one in the back, asking about the red wire.

---

### THE COURSE — MAKER100 LEADERS ROBOTICS
*(~3 minutes)*

This is not an easy course.

Students solve 40 to 60 robotics, machine learning, sensor, actuator, and IoT challenges — and then teach others their solutions.

No full lectures.

Students record all 60-plus assignments on a public or private chart, solved in any order.

**The Rule of Lead Three:** If you are the first person to solve an assignment, you must teach three others. Those three are responsible for helping three more. The highest marks — 90 to 100 percent — come from building that culture of helping.

I am completely comfortable with ten students earning 100 percent. It hurts no one — and it massively improves communication, confidence, and the tone of the classroom.

**The Analog Firewall:** The class always starts here. Code is summarized on paper before loading onto a microcontroller. Circuit diagrams are drawn by hand and checked by another student before wiring. Power is connected only after a second check.

Why? Because thinking before acting is a professional habit. And because a hardware failure caught on paper costs nothing. A hardware failure caught after a short circuit can cost everything.

**LLMs as lab assistants:** Students learn to ask AI for help, understand the answer, verify it, improve it, and eventually build their own tools. AI becomes a debugger and a tutor — not a replacement for understanding.

Once assignments are complete, students do Level 1 and Level 2 final projects. Level 1 is a course pass. Level 2 earns the higher mark. Multiple people are expected to reach the top grade.

The course is at **github.com/hpssjellis/maker100-leaders-robotics** — open source, free, and continuously updated.

---

### LOCAL AI — WHY IT MATTERS
*(~1.5 minutes)*

Teenagers are already using AI assistants. The question is whether they understand these tools — or become dependent on them.

Why not load an LLM locally using an installable webpage — a Progressive Web App?

A computer becomes a private AI lab assistant without sending every question and every piece of student data somewhere else.

> **Demo: Local Gemma 2B and 12B via PWA**

Privacy alone makes this worth doing. But the deeper idea is this: if advanced AI requires a few enormous companies, most people become consumers. If we can put AI tools into classrooms everywhere, students become creators.

---

### ON-DEVICE MACHINE LEARNING — THE FULL PIPELINE
*(~2 minutes)*

The industrial approach to machine learning is to send your data to the cloud and receive a trained model back.

But what if the entire pipeline could run on the microcontroller itself?

Many would say that's impossible — TensorFlow Lite is too large, the hardware too constrained. But I wanted to understand it from first principles. With the help of LLMs, I built the entire training and inference pipeline from scratch on the XIAO ML Kit.

I must acknowledge Vijay Reddi — a member of AiEng4D — whose tinyTorch project and mlsysbook.ai inspired that from-scratch philosophy.

The XIAO ML Kit is built around the Seeed Studio XIAO ESP32S3 Sense — a microcontroller that costs under $15 USD. That price matters. A school can equip a classroom without a massive grant. A student can experiment. A teacher can replace broken parts.

We have working pipelines for:
- Vision classification
- Vision object detection with XY coordinates
- Anomaly detection
- Sound classification
- Motion classification

The first WebSerial training system took 147 versions. That is also part of the lesson. Real technology is not created perfectly the first time. You build. You test. You improve. You learn.

> **Demo: webmcu-ai on-device training and inference**

---

### THE PILOT PROPOSAL — YOUR LEADERSHIP CHALLENGE
*(~2 minutes)*

This is where the presentation changes direction.

Maker100 Leaders Robotics needs the leaders in this room — you — to calculate the cost of running this pilot at your school and find the funding.

You are in one of the best places on the planet to do that.

Here is what you need:

- At least **three pre-engineers** willing to work hard
- **3 to 30 students**, grades 9 to 12
- **~$200 USD per student** to start; ~$50 USD each year for replacement parts. Yes, we break things. That is part of learning.
- Access to a **computer lab** — ideally with a 3D printer
- A teacher willing to complete every assignment alongside the students

If your teacher is willing to learn and complete the work, I will support that class three times during the first course: at the start for safety, in the middle when students hit problems they cannot solve alone, and near the end for the most challenging Level 2 assignments.

Calculate your student count, calculate your total cost, and solve the funding problem. That is not my job. But knowing where the money comes from is your first real leadership challenge.

---

### WHAT I LEARNED FROM STEPPING BACK
*(~1 minute)*

Last year I took a semester off. I was not there to quickly solve my students' problems. They struggled — but they learned deeper.

From that class, two students received over $100,000 scholarships: one the Schulich, one the Loran.

That taught me something important. I am the least important part of this course. The hardware, Lead Three, the Analog Firewall, the classroom culture, and the curriculum — those are the important parts.

No strain, no gain — cognitive, social, emotional, or physical.

---

### CLOSING
*(~1 minute)*

In one year, we meet again. Some schools will have tried. All will have struggled. Some students will have created things none of us expected.

The question is simple: **Which schools will be able to stand here, with data, and show us what their students built?**

That question is not for me.

It is for the leaders in this room.

We need the third student at the table. We need the voice no one expected. We need the person who sees the simple truth the experts miss.

Don't let the future fail because of a bad VCC line.

Thank you.

---

## TIMING GUIDE

| Section | Time |
|---|---|
| Opening — Red Wire Story | 2:00 |
| Who I Am and Why I'm Here | 1:30 |
| The Problem and the Students | 1:30 |
| The Course — Maker100 | 3:00 |
| Local AI + Demo | 1:30 |
| On-Device ML + Demo | 2:00 |
| Pilot Proposal | 2:00 |
| What I Learned Stepping Back | 1:00 |
| Closing | 1:00 |
| **Total** | **~15:30** |

*Adjust demo time as needed — cut or expand the on-device ML demo to fit the room.*
