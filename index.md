---
title: "CS183B: How to Start a Startup"
layout: default
---

<div class="jumbotron">
  <h3>
    By Sam Altman <a href="https://twitter.com/sama" class="twitter-follow-button" data-show-count="false" data-show-screen-name="false">Follow @sama</a>
    <div class="fb-follow" data-href="https://www.facebook.com/sama" data-width="150" data-height="30" data-colorscheme="light" data-layout="standard" data-show-faces="true"></div>
  </h3>
  <h4>Featuring: Mark Zuckerberg, Peter Thiel, Marc Andreessen, Reid Hoffman, Marissa Mayer, and more</h4>
  <button class="btn btn-warning btn-lg"><span class="glyphicon glyphicon-envelope"></span>  Sign Up</button> and <button class="btn btn-primary btn-lg"> Join the community </button>
</div>
<div class="row">
  <div class="col-sm-6">
    <h2 class="page-header">
      Fall 2014
    </h2>
    <b> Everything we know about how to start a startup, for free, from some of the world experts. </b>
    <p></p>
    <p>
    CS183B is a class we’re teaching at Stanford.  It’s designed to be a sort of one-class business course for people who want to start startups.
    </p>
    <p>
    Videos of the classes, associated reading materials, and assignments will all be available here.  There will be 20 videos, some with a speaker or two and some with a small panel.   It’ll be 1,000 minutes of content if you watch it all.
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
    Videos will be uploaded every Tuesday and Thursday. Hundreds of universities are organizing groups to watch the videos together, as well as peer evaluate the projects. See if your university
    <a href="">already has a group</a>, and if not, apply to be a leader.
    </p>
  </div>
  <div class="col-sm-6">
    <h2 class="page-header">
    Course Schedule
    </h2>
    <table class="table table-striped table-bordered">
      <tr>
        <td>Date</td>
        <td>Topic</td>
        <td>Speaker</td>
      </tr>
      {% for course in site.courses %}
      <tr>
        <td>{{ course.date }}</td>
        <td>
          <a href="{{ course.url|remove:'index.html' }}">{{ course.topic}}</a>
        </td>
        <td>
          {% for speaker in course.speakers %}
            <strong>{{ speaker.name }}</strong>,
            <em>{{ speaker.title }}</em>
            <br>
          {% endfor %}
        </td>
      </tr>
      {% endfor %}

      <tr>
        <td>9/23/14</td>
        <td>Introduction</td>
        <td><strong>Sam Altman</strong>, <em>President, Y Combinator</em></td>
      </tr>
      <tr>
        <td>9/25/14</td>
        <td>How to Have Ideas</td>
        <td><strong>Paul Graham</strong>, <em>Title here</em></td>
      </tr>
      <tr>
        <td>9/30/14</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>10/2/14</td>
        <td>Building product, talking to users, and growing</td>
        <td>Drew Houston</td>
      </tr>
      <tr>
        <td>10/7/14</td>
        <td>How to evaluate ideas, monopoly theory</td>
        <td>Peter Thiel</td>
      </tr>
      <tr>
        <td>10/9/14</td>
        <td>Early days of big companies</td>
        <td>Mark Zuckerberg</td>
      </tr>
      <tr>
        <td>10/14/14</td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>10/16/14</td>
        <td>How to "do business"</td>
        <td>Marissa Mayer</td>
      </tr>
      <tr>
        <td>10/21/14</td>
        <td>How to raise money</td>
        <td>Marc Andreessen, Ron Conway, Ben Silbermann</td>
      </tr>
      <tr>
        <td>10/23/14</td>
        <td>How to hire and company culture, part I</td>
        <td>Brian Chesky</td>
      </tr>
      <tr>
        <td>10/28/14</td>
        <td>How to hire and company culture, part II</td>
        <td>Patrick and John Collison</td>
      </tr>
      <tr>
        <td>10/30/14</td>
        <td>Sales and marketing</td>
        <td>Aaron Levie</td>
      </tr>
      <tr>
        <td>11/4/14</td>
        <td></td>
        <td>Reid hoffman</td>
      </tr>
      <tr>
        <td>11/6/14</td>
        <td>How to operate</td>
        <td>Keith Rabois</td>
      </tr>
      <tr>
        <td>11/11/14</td>
        <td>How to manage</td>
        <td>Ben Horowitz</td>
      </tr>
      <tr>
        <td>11/13/14</td>
        <td>Engineering organziations</td>
        <td>Bob Lee</td>
      </tr>
      <tr>
        <td>11/18/14</td>
        <td>Hard technology companies</td>
        <td>Elon Musk</td>
      </tr>
      <tr>
        <td>11/20/14</td>
        <td>Mechanics of startups--legal, finance, HR</td>
        <td>Kirsty Nathoo and Carolynn Levy</td>
      </tr>
      <tr>
        <td>12/2/14</td>
        <td>Founder Advice</td>
        <td></td>
      </tr>
      <tr>
        <td>12/4/14</td>
        <td>Closing thoughts, and pitfalls to avoid</td>
        <td>Sam Altman</td>
      </tr>
    </table>
  </div>
</div>
