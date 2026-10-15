<!--
WEBSITE TEXT: the source of truth for the wording on index.html.

How to use:
  * Edit any text below, then commit and push. Ask Claude to "update the site" and the
    changes will be carried into index.html.
  * Keep the "## Section:" headings. They map each block to a part of the page.
  * You can add, remove, or reorder items within a list (cards, roadmap steps, chips, details).
  * **bold** and *italic* are carried over. Links use [text](url).
  * Anything in an HTML comment like this one is a note and won't appear on the page.
-->

# EE5531 Website Text

## Section: Page title & link preview
- **Browser tab title:** EE5531 Introduction to Robotics | Michigan Tech
- **Search/share description:** Graduate course in autonomous systems: sensor models, state estimation, mapping, planning, and control with ROS 2 and Nav2 on real robots. EE5531 alumni work at May Mobility, Torc Robotics, General Motors, Toro, Qualcomm, and across the autonomous vehicle industry.
- **Share card title:** EE5531 Introduction to Robotics: Wanted, Future Autonomy Stack Engineers
- **Share card text:** Sensor models, state estimation, mapping, planning, and control on real robots with ROS 2 and Nav2. Alumni at May Mobility, Torc, GM, Toro, and Qualcomm.

## Section: Top navigation
Course · Structure · Student work · Details

## Section: Hero
- **Eyebrow:** Michigan Tech · Spring 2027
- **Headline:** *Wanted:* Future Autonomy Stack Engineers.
- **Lede:** In **EE5531 Introduction to Robotics** you transform raw sensor streams into autonomous movement. You will build software to map environments, estimate position under uncertainty, and navigate physical platforms using algorithmic foundations standard in industry.
- **Primary button:** Register: CRN 12485 / 12486
- **Secondary button:** See what students built →
- **Photo caption:** One of the course's Clearpath Jackals, on campus.

## Section: Alumni band
- **Label:** Where EE5531 alumni work now
- **Employers:**
  - May Mobility
  - Torc Robotics
  - General Motors
  - Toro
  - Qualcomm
- **Footer line:** …and throughout the autonomous vehicle sector.

## Section: Why take it
- **Eyebrow:** Why take it
- **Heading:** Robotics the way industry does it

### Card: Real robots
Clearpath Jackals and TurtleBot3s with LiDAR and IMUs. Not just simulation: you'll calibrate their sensors, map real rooms on campus, and send them out on autonomous missions.

### Card: The industry toolchain
ROS 2 Jazzy, Nav2, SLAM Toolbox, Gazebo, RViz2, Python, and Git. If you've read an autonomy job posting, you've seen this list.

### Card: The math behind autonomy
Derive a Kalman filter, then watch it pull a drifting robot back on track. Sensor models, Bayesian filtering, occupancy grids, and path planning, all on real data.

### Card: A portfolio you can show
Every project is a public GitHub repository with code, maps, and video. Exactly what today's employers expect.

## Section: Course structure
<!-- Organized around the OODA loop (Observe, Orient, Decide, Act). Each step has a stage
     name, a question heading, topics, and a concrete hands-on task. The flyer has a one-line version. -->
- **Eyebrow:** Course structure
- **Heading:** Observe. Orient. Decide. Act.
- **Intro:** Every autonomous system, from a delivery robot to a self-driving truck, runs the same loop. The course builds it one stage at a time: learn the theory, implement it in ROS 2, then prove it works on a real robot. By the end of the semester, your code runs the whole loop.

### Step 01 · Observe: What is my sensor really telling me?
LiDAR, IMU, and wheel encoders. Noise models and calibration.
- **Hands-on:** put a robot in front of a wall at 0.5–2 m, record thousands of LiDAR returns, and measure exactly how your sensor gets it wrong.

### Step 02 · Orient: Where am I, and what's around me?
Dead reckoning, the Bayes filter, EKF and UKF, occupancy grids, and SLAM.
- **Hands-on:** watch odometry drift, fix it with a Kalman filter, then map a real lab with SLAM Toolbox.

### Step 03 · Decide: How do I get there?
Costmaps, keepout zones, global planners, and behavior trees for recovery.
- **Hands-on:** configure Nav2 to route around obstacles and no-go zones, and to recover when the robot gets stuck.

### Step 04 · Act: Make it happen on hardware
Local controllers, trajectory tracking, and full-stack integration.
- **Hands-on:** run your full stack on a Clearpath Jackal on an autonomous mission, with no joystick. Performance is scored.

## Section: Student work
- **Eyebrow:** What students built last spring
- **Heading:** Husky Plaza, in 3D
- **Paragraph:** Students took LiDAR data recorded on campus, ran it through the MOLA SLAM framework, and published the result as an interactive point cloud: about 2 million points, colored by height. Look closely to spot the trees, the building, and the people.
- **Viewer button:** Load the interactive 3D viewer
- **Links:** Open full screen ↗ · See the code ↗

## Section: Hardware & tools
- **Eyebrow:** What you'll work with
- **Heading:** Hardware & tools
- **Chips:**
  - Clearpath Jackal
  - TurtleBot3
  - 3D LiDAR
  - IMU
  - ROS 2 Jazzy
  - Nav2
  - SLAM Toolbox
  - Gazebo
  - RViz2
  - Python
  - Git & GitHub

## Section: Course details
- **Eyebrow:** Course details
- **Heading:** Sign up for Spring
- **Details:**
  - **Course:** EE5531 Introduction to Robotics
  - **Term:** Spring 2027
  - **Lecture:** Monday & Wednesday, 1:00–1:50 PM
  - **Project time:** Monday, 2:00–3:50 PM
  - **CRN:** 12485 / 12486
  - **Instructor:** Dr. Jeremy Bos · jpbos@mtu.edu
  - **Prerequisites:** FOSS101 or equivalent experience
  - **Who should take it:** Students who have completed a BS in Robotics Engineering at Michigan Tech, and anyone with experience in Linux, Python (or C++), and version control who wants to know the whys and hows of autonomous systems.
- **Callout:** **The course runs only if enough students enroll.** If you want it to run, register early and tell a friend.
- **Button:** Download the flyer (PDF)

## Section: Footer
Offered by the [Robust Autonomous Systems Laboratory](https://github.com/Robust-Autonomous-Systems-Laboratory), Michigan Technological University.
