---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        INS
        Research Group
      image:
        filename: cicek.png
      text: |
        <br>
        Welcome to KTH Intelligent Network Systems Research Group! We are a passionate team of researchers dedicated to advancing the field of Intelligent Network Systems. Explore our latest news and meet the team to learn more about our work.
  
  # - block: collection
  #   content:
  #     title: Research Areas
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: 'research-areas'
  #       exclude_featured: true
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: asc
  #     page_type: research
  #   design:
  #     view: card  # Use 'list' view for a simple list of titles
  #     columns: '1'
  #   params:
  #     title_style: link  
  # - block: markdown
  #   content:
  #     title: Recent Publications
  #     subtitle: ''
  #     text: >
  #       <script src="https://bibbase.org/show?bib=https%3A%2F%2Fbibbase.org%2Fnetwork%2Ffiles%2Fr2Pvn6jcg63gpfeZq&noBootstrap=1&jsonp=1"></script>
  #   design:
  #     columns: '1'


  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        Welcome to the INS Research Group at KTH! We are a passionate team of researchers dedicated to advancing the field of Intelligent Network Systems. Explore our latest news and meet the team to learn more about our work.

        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---