<template>
  <div class="ui text container" style="font-size: 1.25em">
    <br />
    <h2 class="ui header">How to use?</h2>
    <p>Select a department, and a course and hit the add button. The combinations will be generated automatically. You can also filter out certain instructors as they appear in the results. Additionally, clicking on the timetable will filter-out that specific time. Use Next and Prev arrows for navigating through all combinations.</p>

    <h2 class="ui header">Note!</h2>
    <p>Important note! Data is scraped from public STARS Offerings pages. There is no guarantee data is up-to date. And not all courses have updated their schedules yet. Read blow for more info. </p>

    <br />
    <h2 class="ui header">History</h2>
    <p>The original Scheduler was created in 2010 by <a href="https://www.linkedin.com/in/mustafaakin/">Mustafa Akın</a> and <a href="https://www.linkedin.com/in/semih-sahin-39612b37/">Semih Şahin</a> to aid course selection for the students and teachers, as a Java standalone desktop application. </p>

    <p>In 2011, Mustafa created a web version of Scheduler by coming to terms with BCC to provide a real-time API instead of scraping public data, with the help of Abdullah Atalar. Since then, it has been used by 100.000 unique users throughout the years, which of many are graduated from Bilkent. <small>I'm still a PhD Candidate though and working at Atlassian.</small></p>

    <p>Scheduler was donated to Bilkent IEEE in 2014 to continue hosting, bug-fixes and feature development. It continued well until 2020 when BCC closed the APIs. BCC has never been cooperative at the most basic level for over last ~10 years and now the access is completely cut off. Scheduler SHOULD BE inside Stars, but it is unfortunately not. It's a very basic code.</p>

    <p>This modern version is created by Mustafa in 2-days and the source code is available on Github. It's hosted via Netlify and works on only static data. If it changes, it is manually updated by Mustafa. The data collection does not cause a load to STARS, since the actions are delayed.</p>

  </div>
</template>