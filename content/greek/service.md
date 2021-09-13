---
title: "Service"
description: "this is meta description"
bg_image: "images/feature-bg.jpg"
layout: "service"
draft: false
#to add it back change menu5 to menu
menu5:
  main:
    parent: "More"
    name: "Service"
    weight: 1
  footer:
    name: "Service"
    weight: 3

########################### about service #############################
about:
  enable : true
  title : "Creative UX/UI Design Agency"
  content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptate soluta corporis odit, optio
          cum! Accusantium numquam ab, natus excepturi architecto earum ipsa aliquam, illum, omnis rerum, eveniet
          officia nihil. Eum quod iure nulla, soluta architecto distinctio. Nesciunt odio ullam expedita, neque fugit
          maiores sunt perferendis placeat autem animi, nihil quis suscipit quibusdam ut reiciendis doloribus natus nemo
          id quod illum aut culpa perspiciatis consequuntur tempore? Facilis nam vitae iure quisquam eius harum
          consequatur sapiente assumenda, officia voluptas quas numquam placeat, alias molestias nisi laudantium
          nesciunt perspiciatis suscipit hic voluptate corporis id distinctio earum. Dolor reprehenderit fuga dolore
          officia adipisci neque!"
  image : "images/company/company-group-pic.jpg"


########################## featured service ############################
featured_service:
  enable : true
  service_item:
    # featured service item loop
    - name : "Interface Design"
      icon : "ion-erlenmeyer-flask"
      color : "primary"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

    # featured service item loop
    - name : "Product Branding"
      icon : "ion-leaf"
      color : "primary-dark"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

    # featured service item loop
    - name : "Game Development"
      icon : "ion-lightbulb"
      color : "primary-darker"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."


############################# Service ###############################
service:
  enable : true
  label : "Μαθετε Περισσοτερα"
  title : "Οι Υπηρεσιες μας"
  description : "Παρέχουμε εξατομικευμένες υπηρεσίες αναλυτικής στην εταιρία σας, ώστε να σας βοηθήσουμε να λάβετε καλύτερες αποφάσεις να να μεγιστοποιήσετε το κερδος σας"
  service_item:
    # service item loop
    - icon : ion-pie-graph #ionicon pack v2 : https://ionicons.com/v2/
      name: Business Intelligence
      content: "Οι δείκτες που χρειάζεστε, όταν τους χρειάζεστε με τα τελευταία διαδραστικά dashboards"

    # service item loop
    - icon : ion-cloud #ionicon pack v2 : https://ionicons.com/v2/
      name: Data Engineering 
      content: "Τέλος εποχής για spreadsheets τύπου excel. Όλα σας τα δεδομένα σε ένα μέρος, με ασφάλεια στο cloud"

    # service item loop
    - icon : ion-arrow-graph-up-right #ionicon pack v2 : https://ionicons.com/v2/
      name: Data Science
      content: "Με τη χρήση της τεχνιτής νοημοσύνης στην εταιρία σας μπορείτε να προετοιμαστείτε για το μέλλον σήμερα"

     # service item loop
    - icon : ion-university #ionicon pack v2 : https://ionicons.com/v2/
      name: Σεμινάρια
      content: "Έχετε ήδη ομάδα; Αναλαμβάνουμε την εξατομικευμένη εκπαίδευση του προσωπικού σας για οποιοδήποτε θέμα αναλυτικής"

    # # service item loop
    # - icon : ion-headphone #ionicon pack v2 : https://ionicons.com/v2/
    #   name: Logo Design
    #   content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

    # # service item loop
    # - icon : ion-leaf #ionicon pack v2 : https://ionicons.com/v2/
    #   name: Development
    #   content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

    # # service item loop
    # - icon : ion-planet #ionicon pack v2 : https://ionicons.com/v2/
    #   name: Brand Identity
    #   content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

    # # service item loop
    # - icon : ion-earth #ionicon pack v2 : https://ionicons.com/v2/
    #   name: Brand Identity
    #   content: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut"

############################# call to action #################################
cta:
  enable : true
  # call to action content comes from "_index.md"
---
