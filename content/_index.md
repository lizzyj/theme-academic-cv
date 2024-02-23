---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ABOUT ME

      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: EXPERIENCE
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: COMMERCIAL DESIGNER + INTERN
          company: Jones Pierce Architects
          company_url: ''
          company_logo: org-gc
          location: Atlanta
          date_start: '2023-05-01'
          date_end: ''
          description: |2-
              * Assessed the extent of water damage and learned technical waterproofing details for remediation work.
              * Assisted in preparing Special Administrative Permit (SAP) documents that included life safety assessments of projects.
              * Generating various calculations needed for zoning, planning and building department criteria.
              * Helped with marketing efforts to compile projects and relevant information for a new website.
              * Assisted with materials to be submitted for awards competitions.
        - title: COORDINATOR + BANQUET SERVER
          company: Events Catering
          company_url: ''
          company_logo: org-x
          location: Roswell
          date_start: '2022-03-01'
          date_end: ''
          description: |2-
              * Proactively anticipated and met the diverse needs of clients, while demonstrating strong interpersonal skills.
              * Effectively communicated between different banquet teams, ensuring seamless coordination and collaboration.
              * Contributed to the planning and execution of various events, showcasing organizational and logistical skills for event success.
  
  - block: portfolio
    id: projects
    content:
      title: PORTFOLIO
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: CONTACT ME
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: elizmariejohnson@gmail.com
      phone: (404)-543-4642
      address:
        region: Metro Atlanta Area
      contact_links:
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
