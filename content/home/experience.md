---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: R&D Software Engineer 
    company: Qualcomm Institute
    company_url: ''
    company_logo: QI
    location: United States
    date_start: '2023-04-01'
    description: |2-
        Responsibilities include:
        
        * Deployed Docker containers for CI development via Github actions for testing infrastructure, and managed testing on the cloud.
        * Implemented inter-process communication in Rust using USRP radios for multi-threaded radio scheduling software with TCP.
        * Developed a $6 million data security system for U.S. intelligence (IARPA), for detection of unknown devices.
        * Designed a Rust classifier which achieved greater than 80% accuracy across 8 different signals over-the-air.
        * Contribution published to MILCOM ’23 for signal detection and localization of wireless activity using software defined radios.
        
  - title: Software Development Engineering Intern
    company: Amazon
    company_url: ''
    company_logo: amzn
    location: United States
    date_start: '2022-06-01'
    date_end: '2022-09-01'
    description: |2-
        Responsibilities include:
        
        * Spearheaded a data traffic management project using AWS services, to develop from scratch, with Buyer Risk Prevention team.
        * Designed a Typescript back-end tool to enable traffic control on over 2000 transactions/second per order for real-time and historical data point collection, obtained from buyer receipts, by moving data between DynamoDB and SQS queues.
        * Built a REST API with API Gateway for routing data to custom Lambda functions to start/stop/pauses data traffic between buyer
        receipts and AWS Step Functions for ML data processing.
        * Enabled 50 to 100 developers to efficiently and instantly modify traffic patterns, and save at least 2-3 hours of wait-time per
        processed receipt where previously, engineers were unable to independently modify traffic without permission.
  
  - title: Engineering Intern
    company: Nagasaki University
    company_url: ''
    company_logo: nu
    location: Nagasaki
    date_start: '2021-05-01'
    date_end: '2021-08-01'
    description: |2-
        Responsibilities include:
        
        * Utilized DeepLabV3 network to detect sick trees at 95% accuracy, enabling automatic tree hazard inspections in Nagasaki City.
        * Designed and implemented iOS software, using core ML, for iPhone cameras to be used in real-time image segmentation.
        * Research published to Japan Society of Civil Engineers, which drew over 5000 attendees including Japan Railways (JR) officials.

  - title: FPGA Research Intern
    company: University of Toronto
    company_url: ''
    company_logo: uoft
    location: Canada
    date_start: '2020-05-01'
    date_end: '2020-10-01'
    description: |2-
        Responsibilities include:
        
        * Designed an FPGA debugger IP core which enabled log/drop/injecting data into any memory mapped data stream to locate bugs
        across multiple FPGAs while keeping resource costs under 11%; research was funded by Alibaba, Xilinx, and Fidus Systems.
        * Implemented hardware logic for Xilinx MPSoC, and proved a practical extension to debugging with memory-mapped interfaces.
        * Coauthored a paper published to FPGA ’21 and delivered a presentation to over 150 research associates from the field.
        
  - title: Robotics Research Intern
    company: Hong Kong University of Science and Technology
    company_url: ''
    company_logo: hkust
    location: Hong Kong
    date_start: '2019-06-01'
    date_end: '2019-08-01'
    description: |2-
        Responsibilities include:
        
        * Introduced a novel user interface for an appearance-based eye tracking algorithm to enable hands-free robotic control.
        * Designed a threaded Python interface for an eye-gaze controlled (via webcam) robot simulated in several ROS environments.
        * Improved navigation times up to 26% by mapping eye-gaze to coordinates on a monitor displaying the environment, allowing for
        directions to be inferred; this allowed users to issue motor commands by just gazing at a desired destination in their field of view.
        * Coauthored a paper published to EMBC ’21, the world’s largest international conference for biomedical engineering research.

design:
  columns: '2'
---
