---
title: "How to Start a Startup"
layout: default
---
<div class="container">
  <h1>How to Start a Startup</h1>
  <hr />
</div>

<div class="jumbotron">
  <h3>
    By Sam Altman <a href="https://twitter.com/sama" class="twitter-follow-button" data-show-count="false" data-show-screen-name="true">Follow @sama</a>
    <iframe src="//www.facebook.com/plugins/follow.php?href=https%3A%2F%2Fwww.facebook.com%2Fsamaltman&amp;width&amp;height=80&amp;colorscheme=light&amp;layout=button&amp;show_faces=true&amp;appId=178422522168165" scrolling="no" frameborder="0" style="border:none; overflow:hidden; height:20px;" allowTransparency="true"></iframe>
  </h3>
  <h4><strong>Everything we know about how to start a startup, for free, from some of the world experts.</strong></h4>
  <a href="http://eepurl.com/3oe0H" class="btn btn-warning btn-lg"><span class="glyphicon glyphicon-envelope"></span>  Sign Up</a> and <a href="https://www.facebook.com/groups/556336557801913/" class="btn btn-primary btn-lg"> Join the community </a>
</div>
<div class="row">
  <div class="col-sm-6">
    <h2 class="page-header">
      Fall 2014
    </h2>
    <h3>Everything we know about how to start a startup, for free, from some of the world experts.</h3>
    <p>
    CS183B is a class we’re teaching at Stanford.  It’s designed to be a sort of one-class business course for people who want to start startups.
    </p>
    <p>
    Videos of the lectures, associated reading materials, and assignments will all be available here.  There will be 20 videos, some with a speaker or two and some with a small panel.   It’ll be 1,000 minutes of content if you watch it all.
    </p>
    <p>We’ll cover how to come up with ideas and evaluate them, how to get users and grow, how to do sales and marketing, how to hire, how to raise money, company culture, operations and management, business strategy, and more.</p>
    <p>
    You can’t teach everything necessary to succeed in starting a company, but I suspect we can teach a surprising amount.  We’ve tried to take some of the best speakers from the past 9 years of Y Combinator dinners and arrange them in a way that will hopefully make sense.
    </p>
    <p>
      We’re doing this because we believe helping a lot of people be better at starting companies will be good for everyone.  It will hopefully be valuable even for people who don’t want to start startups.
    </p>
    <p>
    Talks like these have really helped Y Combinator founders create their companies.  We hope you find it helpful too!
    </p>
    <p> -Sam </p>
    <hr>
    <h2 class="page-header">
      Following along
    </h2>
    <p>
    <strong>All lecture videos will be uploaded to this site</strong> - at 4 PM Pacific Time, after the in-person lectures every Tuesday and Thursday. Hundreds of universities are organizing groups to watch the 50-minute videos together, as well as peer evaluate the projects. See the list of groups and viewing sessions
    <a href="https://docs.google.com/spreadsheets/d/1P5xh1t0SOUlVmFkLKPk07DO4dWzM3B9bUWFctWEk1bY/edit#gid=0">at
    universities and other organizations</a>.
    If there isn't a viewing session at your university or being hosted at a local organization, you can <a href="https://docs.google.com/forms/d/1txn_v7M-MmrqbCH44lAD4JKcM1iCTHLL1vCrqv2qH9U/viewform">apply to be a leader</a>.
    </p>
    <p>
      In addition to the <a href="http://eepurl.com/3oe0H">mailing list</a> and
      <a href="https://www.facebook.com/groups/556336557801913/">Facebook group</a>,
       a discussion forum to discuss the contents of each lecture and reading is
      <a href="http://startupclass.co">here</a>.
    </p>
  </div>
  <div class="col-sm-6">
    <h2 class="page-header">
    Course Schedule
    </h2>
    <a href="/lists/readings/">Readings posted through 11/11</a>, <a href="https://www.youtube.com/channel/UCxIJaCMEptJjxmmQgGFsnCg/">Videos posted through 10/16</a>
    <br>
    <a href="/lists/projects">Project 2</a> has been posted! Submission will be on <a href="http://www.reddit.com/r/HTSASprojects/">reddit</a>
    <br>
    Videos will be available on Stanford's iTunes U account soon!
    <table class="table table-striped table-bordered top-margin">
      <tr>
        <td>Date</td>
        <td>Speaker</td>
        <td>Topic</td>
      </tr>
      {% for course in site.courses %}

      <tr>
        <td>{% if course.lecno <= 15 %}<a href="/courses/{{ course.slug }}">{% endif %}
          {{ course.date|remove:'"' }}{% if course.lecno <= 15 %}</a>{% endif %}
        </td>
        <td>
          {% for speaker in course.speakers %}
            <strong>{{ speaker.speaker_name }}</strong>{% if speaker.speaker_name != "TBA" %}, {% endif %}
            <em>{{ speaker.speaker_title }}</em>
            <br>
          {% endfor %}
        </td>
        <td>
        {% if course.lecno <= 15 %}<a href="/courses/{{ course.slug }}">{% endif %}
            {{ course.topic}}{% if course.lecno <= 15 %}</a>{% endif %}

        </td>
      </tr>
      {% endfor %}
    </table>
  </div>
</div>
