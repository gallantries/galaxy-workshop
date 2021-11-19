---
layout: event
title: "Spanscriptomics: Single cell analysis using Galaxy"
type: track
site_title: GTÑ
code_of_conduct_url: "https://galaxyproject.org/community/coc/"
event_state: 'wip' # 'wip', 'running' or 'done'
contacts: []
description:
date_start: 2021-11-29
format: async
registration_form:
feedback_form:
certificates: true
lang: en
galaxy_servers:
  - name: Galaxy EU
    url: "https://usegalaxy.eu"
tiaas_keyword: spanscriptomics
tiaas_servers: [eu]
tracking: spanscriptomics
logo: events/spanscriptomics/logo.png
instructors:
#organisers & trainers
  - nomadscientist # TODO: add everybody to CONTRIBUTORS.yaml and here
  - ales-ibt
  - pclo
  - shiltemann
  - hexylena
  - beatrizserrano
  - IrelCM
  - jrr-cpt
  - Lgallegovillar
  - mtbernardi
  - melibleq
  - npalopoli
  - StefyDreptate
#additional trainers
  - pcm32
  - Vinicius Maracaja-Coutinho
  - Eucaliptovni
  - Veronica Olivo Pimentel

schedule:
    day1:
      title: Welcome & Practical Information
      sessions:
        - name: "Get set up for the course"
          type: setup
        - link: meetnjoin_eng

    galaxy-intro:
      title: "Introduction to Galaxy"
      description: "Today we start by introducing the Galaxy Platform"
      sessions:
        - name: "Icebreaker: Introduce yourself in Slack!"
          type: icebreaker
          prompt: "Introduce yourself, tell us where you're joining from, and one thing about your surroundings (e.g. it's snowing outside, there's a squirrel on my porch, my cat is on my keyboard)"
        - link: introduction/galaxy-intro-short/slides
            support_channel: "#galaxy-eng"
        - link: introduction/galaxy-intro-short/tutorial
            support_channel: "#galaxy-eng"

    ngs:
      title: Single Cell
      description: "Here we show you how to analyze your single cell data using Galaxy."
      sessions:
        - link: transcriptomics-scrna-intro-slides
            support_channel: "#scrna-intro-eng"
        - link: transcriptomics/droplet-quantification-preprocessing/tutorial
            support_channel: "#scrna-alevin-eng"
        - link: transcriptomics/scrna-seq-basic-pipeline/tutorial
            support_channel: "#scrna-final-eng"
    done:
      title: "All done?"
      description: "Please feel free to hang around in Slack and talk to us and the rest of the Galaxy community! Thanks so much for joining and we hope you learned a ton!!"
      sessions:

    post-course:
      title: "After the Course"
      description: |
        We'll send you a survey after the course - PLEASE fill it out, as this is crucial for the GTÑ study on the impact of translating bioinformatics materials.
        All the course materials will remain online, so you can continue working on them for as
        long as you want. The only difference will be that you should ask your questions
        on the <a href="https://gitter.im/Galaxy-Training-Network/Lobby">GTN Gitter channel</a>, instead of Slack.

#thisneedslotsofprogramminghelp
      post-course_eng:
        title: "Quieres cambiar idioma?"
        description: |
          Here you can switch to the programmes with resources that were automatically translated (CAT-Español) or translated by humans (HES-Español). Please remember to note this in the post-course survey! This is valuable data!

---

Welcome to the GTÑ Experiment! What is the GTÑ and what is the experiment in this workshop? See our workshop description [here](https://nomadscientist.github.io/galaxy-workshop/events/spanscriptomics/) and our project information [here](todo). You've been allocated to the ENG team. These are all original, English bioinformatics resources. You can find the buttons to switch teams (if you want!) at the bottom of this page. Please make sure to note that you switched in the post-course survey!