---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 11

title: Contact
subtitle: Information regarding my email and location. In case of  appointment, please do it by Google Calendar inviting me to my email.

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
 # form:
#    provider: netlify
 #   formspree:
#      id:
 #   netlify:
      # Enable CAPTCHA challenge to reduce spam?
  #    captcha: true

  # Contact details (edit or remove options as required)
  email: christian.salas@uchile.cl
  #phone: 888 888 88 88
  address:
    street: Av. Santa Rosa 11315
    city: La Pintana
    region: Santiago
    postcode: '(Chile)'
    country: Chile
    country_code: CL
 # Choose a map provider in `params.yaml` to show a map from these coordinates
  coordinates:
    latitude: '-33.5696275'
    longitude: '-70.6319216'
  directions: Enter Building 1 and take the stairs to Office 13 on the second floor.
  office_hours:
    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendar.google.com/'
#  contact_links:
#    - icon: twitter
#      icon_pack: fab
#      name: DM Me
#      link: 'https://twitter.com/cseljatib'
#    - icon: video
#      icon_pack: fas
#      name: Zoom Me
#      link: 'https://zoom.com'

# design:
#   columns: '2'
design:
  background:
    # Name of image in `assets/media/`.
    image: matt-mcnulty-nyc-2nd-ave.jpg
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.7
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true
  
---
