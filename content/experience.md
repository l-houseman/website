---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: resume-skills
    content:
      title: Skills
      username: me
  - block: markdown
    content:
      title: Certifications
      text: |
        <div class="row">
          <!-- Certification 1 -->
          <div class="col-12 col-sm-6 mb-3">
            <div class="featurette">
              <div class="featurette-icon"><i class="fab fa-aws"></i></div>
              <h3>AWS Certified Solutions Architect</h3>
              <p>Issued by Amazon Web Services</p>
            </div>
          </div>
          <!-- Certification 2 -->
          <div class="col-12 col-sm-6 mb-3">
            <div class="featurette">
              <div class="featurette-icon"><i class="fab fa-google"></i></div>
              <h3>Google Cloud Professional</h3>
              <p>Issued by Google Cloud</p>
            </div>
          </div>
        </div>
    design:
      columns: '1'
  - block: resume-awards
    content:
      title: Awards
      username: me
#  - block: resume-languages
#    content:
#      title: Languages
#      username: me
---
