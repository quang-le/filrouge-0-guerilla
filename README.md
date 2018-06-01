# Fil Rouge
*created on 01/06/2018 by quang-le*
*last update 01/06/2018*

1. Description
Learning project divided in 6 phases, spread out throughout the BeCode training. The project simulates working for clients on specific tasks. Although the projects are not really commissioned by clients, we work in a setting as realistic as possible, with set deadlines and real associations used as dummy clients.
 1. Phase 1 "Guerilla style"
 Create a one-pager answering clients problems in 6 hours. *Done on 30/05/2018* [Full briefing](https://github.com/becodeorg/lovelace-2/blob/master/Projects/fil-rouge/phase-1.md);
 2. Phase 2 "Managed-style"
 Study demand
 3. Phase 3
 Design of one-pager, v.2
 4. Create a multi-page website
 5. Develop a back-office (CMS)
 6. Mobile application/PWA

[Full description](https://github.com/becodeorg/lovelace-2/tree/master/Projects/fil-rouge)

2. Outcomes
 
 1. Phase 1

  1. The client

   1. Presentation
   CTV Medias is a belgian non-profit active in media education. They offer trainings and workshops aimed at improving people's digital media skills and their critical skills. Basically, they want to support people in becoming digitally literate, active, critical citizens.

   CTV Medias works with young and elderly people, as well as people with disabilities. They organize their own trainings and workshops but also work on demand.

   They are recognized as a permanent education (Education Permanente) by the Fédération Wallonie Bruxelles, which means they receive public funding and their action has to meet certain strict criteria.

   2. Digital presence
    For the exercise, I was notified they had a presence on [Guide Social](https://www.guidesocial.be/ctv/), which is a platform for Belgian non-profits active in the social sector. 
    Browsing through the information, I found out they had a [website](http://www.ctv.be/cms/) that had been updated in 2018.

   * Website: [http://www.ctv.be/cms/](http://www.ctv.be/cms/)
   * Guide Social: [https://www.guidesocial.be/ctv/](https://www.guidesocial.be/ctv/)
   * Social networks: [Twitter](https://twitter.com/ctvmedias), [Vimeo](https://vimeo.com/ctvmedias), [LinkedIn](https://www.linkedin.com/in/ctvmedias/), [Facebook](https://www.facebook.com/pages/CTV-M%C3%A9dias/478169852230983?fref=ts)
   * Youtube: [https://www.youtube.com/channel/UCOewGujkwx_5hIy6bojkzIQ](https://www.youtube.com/channel/UCOewGujkwx_5hIy6bojkzIQ)
   * Web-tv: [http://www.webtele.be/](http://www.webtele.be/)

  2. Working methodology
  
  The gist of the exercise was to provide:
  * a one-pager
  * within a strict 6 hours time limit

   1. Analyze website and select content

  My first step was to browse through all the [Guide Social](https://www.guidesocial.be/ctv/) page, then the [website](http://www.ctv.be/cms/) to answer 4 questions:
  * What do they do?
  * Which content needs to be kept?
  * How much content do I need to cut out or rephrase?
  * How many graphic resources (logo, pictures) do they have?

    I figured out I could synthesize the useful content as:
  * Who they are
  * What they do: trainings, workshops, school projects
  * Show some productions: photos, videos
  * Press coverage
  * link to partners
  * An agenda
  * Contact info

  2. Choose a template and re-organize information

  At first, I started to try and figure out the best way to put it all in one page. For example, I thought a word cloud might be a good way to keep some key words important to the client, while chopping off some unnnecessary text.
  
  Then I started to look for a template, that would fit my initial idea on [https://html5up.net/](https://html5up.net/) and on [templated.co](https://templated.co/). At that point, I realized that browsing for the right template might eat up too much time, so I decided to settle for a template that would meet 3 requirements:
  - Provide a way to put images next to text
  - Have some variety in the layout
  - Be sober in the sense that it should allow a moderate amount of text to be easily readable (not just 2 or 3 lines)

  So I chose [Caminar](https://templated.co/caminar). 

  3. Adjust working method and objectives
  At this stage, I started stuggling with the template, as I found it hard to navigate the css, and tricky to modify it. I was considering dropping the theme and coding everything myself from scratch. However, [Sammuel Janssens](https://github.com/SammuelJ), advised me to use the Google Chrome inspector, as it displays css properties and the line where it is encoded.

  The template proved useful, but still not flexible enough to do everything I had in mind in the timeframe I had. So I reviewed the criteria of the exercise and decide to:
  - Aim to finish 1 hour earlier, to have time to deploy the site and to have a small buffer
  - Drop some intended features of the site.

  4. Go for it
  In the end I would aim to implement:
  * Who they are
  * What they do: trainings, workshops, school projects
  * Show some videos (not enough usable photos)
  * Contact info

  Content-wise, I had to cut and rephrase the presentation (Who they are). I also had te rephrase and re-organize "what they do" as it wasn't clear in the original website (overlapping categories). I also wanted to implement an agenda, but dropped the idea, as I couldn't find a way to visually integrate it to the template, and the last agenda update on the website was from 2017.

  5. Result
  
  The one-page has been deployed on [http://ctv-medias.tk/](http://ctv-medias.tk/)
  Here's how it looks:
  ![alt-text](https://github.com/quang-le/filrouge-0-guerilla/blob/master/prntscrn/Capture%20du%202018-06-01%2011-31-01.png)
   ![alt-text](https://github.com/quang-le/filrouge-0-guerilla/blob/master/prntscrn/Capture%20du%202018-06-01%2011-31-16.png)
   ![alt-text](https://github.com/quang-le/filrouge-0-guerilla/blob/master/prntscrn/Capture%20du%202018-06-01%2011-31-27.png)  

  3. Learning outcomes
   1. Technical
   
   Images formats: .jpg is for photos, . gif is for animated images, .svg is good icons and scalable items, .png is good if there's not many colors
   2. Way of working