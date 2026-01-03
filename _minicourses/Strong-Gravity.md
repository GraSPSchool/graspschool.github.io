---
title: Testing Gravity Where It Is Strong
shortname: Strong Gravity
year: '2025'
langid: 'en'

lecturer:
    name: Prajwal Hassan Puttasiddappa
    suffix: MSc
    affiliation:
        - name: UFES
          website: https://ppgcosmo.cosmo-ufes.org/
          country: Brazil
        - name: U. Oslo
          website: https://www.mn.uio.no/fysikk/english/
          country: Norway

schedule:
    start: 2025-07-14
    end: 2025-07-18
    classes: '5'
    time:
        brt: "10h00"
        utc: "13h00"

workload: '10h'

topics: 
    - "What is strong-gravity regime?"
    - "What are the observables in this regime?"
    - "What are the tools to analyze the data?"
    - "Are these tools independent of assumptions?"
    - "What can we tell about the nature of gravity very close to black holes?"

overview: >
    We explore modern techniques available for tests of gravity using stellar orbits and photon dynamics near the Galactic Center. We will analyze stellar motion and infer orbital parameters using both traditional Bayesian statistics and neural networks. We will also look at the possibility of using black hole shadow measurements to constrain deviations from Schwarzschild geometry. We will learn through hands-on exercises.

prerequisites: >
    Introductory astronomy, basic Python and Mathematica.

bibliography_intro: >
    Detailed notes and codes, along with other references will be provided during the lectures. 

    Stellar Orbits around galactic center: We will use data from the paper "An Update on Monitoring Stellar Orbits in the Galactic Center" or through the catalog <a href="https://vizier.cds.unistra.fr/viz-bin/VizieR-3?-source=J/ApJ/837/30/table5" target="_blank">at this URL</a>.

bibliography:
  - sortkey: gillessen2017stellarorbits
    type: article
    author:
      - name: "S. Gillessen"
      - name: "P. M. Plewa"
      - name: "F. Eisenhauer"
      - name: "R. Sari"
      - name: "I. Waisberg"
      - name: "M. Habibi"
      - name: "O. Pfuhl"
      - name: "E. George"
      - name: "J. Dexter"
      - name: "S. von Fellenberg"
      - name: "T. Ott"
      - name: "R. Genzel"
    title: "An Update on Monitoring Stellar Orbits in the Galactic Center"
    journal: "The Astrophysical Journal"
    volume: "837"
    pages: "30"
    date: 2017-03-01
    doi: "10.3847/1538-4357/aa5c41"
    arxiv: "1611.09144"
    arxivclass: "astro-ph.GA"

  - sortkey: vizier2023galacticcenter
    type: misc
    author:
      - name: "S. Gillessen"
      - name: "P. M. Plewa"
      - name: "F. Eisenhauer"
      - name: "R. Sari"
      - name: "I. Waisberg"
      - name: "M. Habibi"
      - name: "O. Pfuhl"
      - name: "E. George"
      - name: "J. Dexter"
      - name: "S. von Fellenberg"
      - name: "T. Ott"
      - name: "R. Genzel"
    title: "Stellar Orbits in the Galactic Center (J/ApJ/837/30/table5)"
    src: "https://vizier.cds.unistra.fr/viz-bin/VizieR-3?-source=J/ApJ/837/30/table5"
    date: 2017-03-01

  - sortkey: perlick2022bhshadows
    type: article
    author:
      - name: "Volker Perlick"
      - name: "Oleg Yu. Tsupko"
    title: "Calculating black hole shadows: Review of analytical studies"
    journal: "Physics Reports"
    volume: "947"
    pages: "1–39"
    date: 2022-01-01
    doi: "10.1016/j.physrep.2021.10.004"
    arxiv: "2105.07101"
    arxivclass: "gr-qc"

  - sortkey: olmo2023bhshadows
    type: article
    author:
      - name: "Gonzalo J. Olmo"
      - name: "João Luís Rosa"
      - name: "Diego Rubiera-Garcia"
      - name: "Diego Sáez-Chillón Gómez"
    title: "Shadows and photon rings of regular black holes and geonic horizonless compact objects"
    journal: "Classical and Quantum Gravity"
    volume: "40"
    pages: "174002"
    date: 2023-01-01
    doi: "10.1088/1361-6382/aceacd"
    arxiv: "2302.12064"
    arxivclass: "gr-qc"

videorecordings:
    src: https://www.youtube.com/embed/videoseries?si=0Bal_IH8kduj1oyl&amp;list=PLFbVsjW_Z3X7-RcxlnNlgqwRWVUJODx6z

coursetype: intermediate
---