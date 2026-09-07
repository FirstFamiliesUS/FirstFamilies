---
layout: default
title: Home
permalink: /
custom_color: navy
scroll_top_btn:
  enable: true 

# Hero Section
hero:
  subtitle: Welcome to First Families in the United States
  title: '<span class="display-4">Promoting the Posterity!</span>'
  buttons:
    - label: Explore Now
      url: "#"
      class: btn btn-lg btn-primary rounded-pill me-2
    - label: Contact Us
      url: "#"
      class: btn btn-lg btn-outline-primary rounded-pill
  background_image: /assets/img/photos/bg11.webp




# Facts Section
facts:
  subtitle: Company Facts
  title: We are proud of our works
  counters:
    - count: 100+
      text: Surnames
    - count: 50+
      text: Events
    - count: 15+
      text: Certificates awarded

# Testimonials Section
testimonials:
  image: /assets/img/photos/tm1.webp
  testimonials_list:
    - text: "Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Vestibulum ligula porta felis euismod semper."
      name: Coriss Ambady
      position: Financial Analyst
    - text: "Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Vestibulum ligula porta felis euismod semper."
      name: Cory Zamora
      position: Marketing Specialist
    - text: "Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Vestibulum ligula porta felis euismod semper."
      name: Nikolas Brooten
      position: Sales Manager



# Team Section
team:
  subtitle: Our Team
  title: Save your time by choosing our professional team.
  text: Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
  image: /assets/img/photos/about24.webp
  image2x: /assets/img/photos/about24@2x.webp
  features:
    - text: Aenean eu leo quam ornare curabitur blandit tempus.
    - text: Nullam quis risus eget urna mollis ornare donec elit.
    - text: Etiam porta sem malesuada magna mollis euismod.
    - text: Fermentum massa vivamus faucibus amet euismod.



# Call to Action Section
cta:
  title: We are trusted by over 5000+ clients. Join them now and grow your business.
  button:
    label: Get Started
    url: "#"
    class: btn btn-primary rounded-pill
---

<div class="content-wrapper">
  <header class="wrapper bg-gray">
    {% include components/navbar/navbar.html 
        classList="fancy navbar-light navbar-bg-light caret-none"
        fancy=true
        logoAlt="logo-dark"
        otherClassList="w-100 d-flex ms-auto"
        otherSocial=true
    %}
  </header>
  <!-- /header -->

  {% include components/sections/demo17/hero.html %}
  
  <section class="wrapper bg-gray">
    <div class="container">
      <div class="card shadow-none my-n13 my-md-n15 my-lg-n17">
        <div class="card-body py-12 py-lg-14 px-lg-11 py-xl-16 px-xl-13">
          

<!-- POSTERITY IMAGE -->
<div class="text-center mb-10">
  <img src="{{ '/assets/images/xtELN-cropped.jpg' | relative_url }}" 
       alt="First Families image" 
       class="img-fluid rounded shadow">
</div>


<!-- GOOGLE CALENDAR EMBED -->
<div class="text-center mb-10">
  <iframe src="https://calendar.google.com/calendar/embed?src=firstfamiliesusa%40gmail.com&ctz=America%2FNew_York" 
          style="border: 0; max-width: 100%;" width="800" height="600" frameborder="0" scrolling="no"></iframe>
</div>



          {% include components/sections/demo17/services.html %}
          {% include components/sections/demo17/strategy.html %}
          {% include components/sections/demo17/facts.html %}
          {% include components/sections/demo17/testimonials.html %}
          {% include components/sections/demo17/case-studies.html %}
          {% include components/sections/demo17/team.html %}
          {% include components/sections/demo17/why-choose.html %}
          {% include components/sections/demo17/cta.html %}
        </div>
      </div>
    </div>
  </section>
</div>

{% include components/footer/footer.html 
    style="three-column"
    container_padding="pt-20 pt-lg-21 pb-7"
    bg_color="bg-dark" 
    text_color="text-inverse"
%}
