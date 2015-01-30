---
title: "About"
layout: default
---

<h1><a href="/">How to Start a Startup</a> <a href="https://www.facebook.com/groups/556336557801913/" class="btn btn-primary btn-sm"> Join the community </a></h1>
<h3> Sam Altman <a href="https://twitter.com/sama" class="twitter-follow-button" data-show-count="false" data-show-screen-name="true">Follow @sama</a></h3>
<hr />

<div class="row">
  <div class="col-sm-6">
    <h2 class="page-header">
      Fall 2014
    </h2>
    <h3>Everything we know about how to start a startup, for free, from some of the world experts.</h3>
    <p>
    CS183B is a class we taught at Stanford.  It’s a sort of one-class business course for people who want to start startups.
    </p>
    <p>
    Videos of the lectures, associated reading materials, and assignments are all available here.  There are 20 videos, some with a speaker or two and some with a small panel.   It’s be 1,000 minutes of content if you watch it all.
    </p>
    <p>We cover how to come up with ideas and evaluate them, how to get users and grow, how to do sales and marketing, how to hire, how to raise money, company culture, operations and management, business strategy, and more.</p>
    <p>
    You can’t teach everything necessary to succeed in starting a company, but I think we were able to teach a surprising amount.  We’ve tried to take some of the best speakers from the past 9 years of Y Combinator dinners and arrange them in a way that will hopefully make sense.
    </p>
    <p>
      We did this because we believe helping a lot of people be better at starting companies will be good for everyone.  It is hopefully valuable even for people who don’t want to start startups.
    </p>
    <p>
    Talks like these have really helped Y Combinator founders create their companies.  We hope you find it helpful too!
    </p>
    <p> -Sam </p>
    <hr>
    <h2 class="page-header">
      Hosting Viewing Sessions
    </h2>
    <p>
    Hundreds of meetups have been held around the world to bring people together to watch and discuss the videos. You can see the list of sessions that have previously been held 
    <a href="https://docs.google.com/spreadsheets/d/1P5xh1t0SOUlVmFkLKPk07DO4dWzM3B9bUWFctWEk1bY/edit#gid=0">here</a>. <br />
    Many viewers found it valuable to have a group to discuss the ideas from the lecture videos, as well as to discuss their own startup ideas. If you want to organize a viewing session in your area or at your university, feel free to do so at the pace you choose.
    
    </p>
  </div>
  <div class="col-sm-6">
    <h2 class="page-header">
    Materials and Schedule
    </h2>
    <a href="http://www.youtube.com/playlist?list=PL5q_lef6zVkaTY_cT1k7qFNF2TidHCe-1">Videos as a Youtube playlist</a>, or <a href="https://itunes.apple.com/us/course/how-to-start-a-startup/id951932247"><strong>podcasts</strong> through Stanford's iTunes U.</a> <br />
    <a href="/lists/projects/">Optional Projects</a> <br />
    Lecture pages below include related readings, slide decks, and lecture transcripts.
    <table class="table table-striped table-bordered top-margin">
      <tr>
        <td>Date</td>
        <td>Speaker</td>
        <td>Topic</td>
      </tr>
      {% for course in site.courses %}

      <tr>
        <td>{% if course.lecno <= 20 %}<a href="/courses/{{ course.slug }}">{% endif %}
          {{ course.date|remove:'"' }}{% if course.lecno <= 20 %}</a>{% endif %}
        </td>
        <td>
          {% for speaker in course.speakers %}
            <strong>{{ speaker.speaker_name }}</strong>{% if speaker.speaker_name != "TBA" %}, {% endif %}
            <em>{{ speaker.speaker_title }}</em>
            <br>
          {% endfor %}
        </td>
        <td>
        {% if course.lecno <= 20 %}<a href="/courses/{{ course.slug }}">{% endif %}
            {{ course.topic}}{% if course.lecno <= 20 %}</a>{% endif %}

        </td>
      </tr>
      {% endfor %}
    </table>
  </div>
</div>
