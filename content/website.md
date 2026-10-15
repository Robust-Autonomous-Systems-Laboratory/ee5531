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
- **Secondary button:** See past student work →
- **Photo caption:** A Clearpath Jackal, one of the course platforms.

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
- **Heading:** Built for engineers headed into autonomy

### Card: Real robots
Clearpath Jackals and TurtleBot3s with LiDAR and IMUs. Not just simulation: algorithms are developed in Gazebo and validated on hardware.

### Card: The industry toolchain
ROS 2, Nav2, SLAM Toolbox, Gazebo, RViz2, Python, and Git: the skills named in robotics and AV job postings.

### Card: The math behind autonomy
Probabilistic sensor models, Bayesian filtering (EKF/UKF), occupancy-grid mapping, and path planning, derived first and then implemented.

### Card: A portfolio you can show
Every project is a public GitHub repository with code, documentation, maps, and video. Exactly what today's employers expect.

## Section: Course structure
<!-- Organized around the OODA loop (Observe, Orient, Decide, Act). Each step has a stage
     name, a heading, topics, and one learning outcome. The flyer has a one-line version. -->
- **Eyebrow:** Course structure
- **Heading:** Organized around the OODA loop
- **Intro:** Every autonomous system runs the same cycle: **observe** the world, **orient** within it, **decide** what to do, and **act**. The course works through that loop one stage at a time. Each stage moves from theory to a ROS 2 implementation to validation on hardware, and builds on the stage before it. The semester ends by closing the full loop on a mobile robot.

### Step 01 · Observe: Sensing & sensor models
LiDAR, IMU, and wheel odometry. Noise characterization, the beam model, and calibration.
- **Outcome:** characterize a sensor statistically and build the measurement model an estimator needs.

### Step 02 · Orient: State estimation & mapping
Dead reckoning, the Bayes filter, EKF and UKF, occupancy grids, and SLAM.
- **Outcome:** estimate a robot's pose under uncertainty and map a real space.

### Step 03 · Decide: Planning
Costmaps and keepout zones, global path planning, and behavior trees for mission logic and recovery.
- **Outcome:** plan collision-free paths and specify how a robot responds when a plan fails.

### Step 04 · Act: Control & integration
Local controllers and trajectory tracking in Nav2, then closing the loop on the Clearpath Jackals.
- **Outcome:** integrate the full stack and evaluate its performance on an autonomous mission.

## Section: Student work
- **Eyebrow:** Past student work
- **Heading:** LiDAR SLAM of Husky Plaza
- **Paragraph:** Last spring, students processed LiDAR data recorded on campus with the MOLA SLAM framework and published the result as an interactive point cloud: about 2 million points, colored by elevation.
- **Viewer button:** Load the interactive 3D viewer
- **Links:** Open full screen ↗ · See the code ↗

## Section: Hardware & tools
- **Eyebrow:** Platforms & software
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
- **Heading:** Registration
- **Details:**
  - **Course:** EE5531 Introduction to Robotics
  - **Term:** Spring 2027
  - **Lecture:** Monday & Wednesday, 1:00–1:50 PM
  - **Project time:** Monday, 2:00–3:50 PM
  - **CRN:** 12485 / 12486
  - **Instructor:** Dr. Jeremy Bos · jpbos@mtu.edu
  - **Prerequisites:** FOSS101 or equivalent experience
  - **Who should take it:** Students who have completed a BS in Robotics Engineering at Michigan Tech, and anyone with experience in Linux, Python (or C++), and version control who wants to know the whys and hows of autonomous systems.
- **Callout:** **The course runs only with sufficient enrollment.** Register early.
- **Button:** Download the flyer (PDF)

## Section: Footer
Offered by the [Robust Autonomous Systems Laboratory](https://github.com/Robust-Autonomous-Systems-Laboratory), Michigan Technological University.
