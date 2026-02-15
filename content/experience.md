---
title: "Erfahrung"
date: 2023-10-24
type: landing

design:
  spacing: "5rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
      headings:
        Erfahrung: "Erfahrung"
    design:
      # Hugo date format
      date_format: "January 2006"
      # Education or Experience section first?
      is_education_first: false
  - block: resume-awards
    content:
      title: Auszeichnungen
      username: me
  - block: features
    content:
      title: "Mitgliedschaften"
      text: ""
      items:
        - name: "PKN - Psychotherapeutenkammer Niedersachsen"
          description: "seit 2019"
          icon: "custom/pkn"
        - name: "DPtV - Deutsche PsychotherapeutenVereinigung"
          description: "seit 2023"
          icon: "custom/dptv"
        - name: "DeGPT - Deutschsprachige Gesellschaft für Psychotraumalogie"
          description: "seit 2026"
          icon: "custom/degpt"
          icon_pack: "custom"
          icon_class: "membership-icon"
    design:
      columns: "3"
      background:
        color: "gray-50"
  # - block: resume-skills
  #   content:
  #     title: Mitgliedschaften
  #     username: me
  #- block: resume-languages
  #  content:
  #    title: Languages
  #    username: me

---

