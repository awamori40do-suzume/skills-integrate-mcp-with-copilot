# Proposed Issues for skills-integrate-mcp-with-copilot

Below are suggested issues based on features seen in other extracurricular-related projects. Copy the title and description into your GitHub repository's Issues page to create them.

1. **Add “Mergington HS clubs” FastAPI-style frontend**
   
   Inspired by [christopherLangSlalom/mhs-extracurricular-activities](https://github.com/christopherLangSlalom/mhs-extracurricular-activities), which implements a FastAPI-based website for the fictional school.

   *Goals:*
   - Serve a basic HTML/JS UI from the API.
   - Provide endpoints for listing clubs, events and student sign-ups.

2. **Support a student planner / college-admissions tracker**
   
   The [extracurricular-planner](https://github.com/mayhazali/extracurricular-planner) project keeps a record of a student’s activities for résumé/college use.

   *Add:* model and UI for tracking activity history, exporting a summary report.

3. **Static marketing/“portfolio” pages**
   
   Several repos (e.g. `Longwood-Webmasters`, `TheQuack`, `MCCurriculars.github.io`, `baohuy-website`) are simple HTML sites advertising/explaining clubs.

   *Add:* a static section or separate `docs/` site describing what the system is and how to use it.

4. **Mobile-client prototype**
   
   There are macOS/Swift clients in `Find-my-EA`/`Found-my-EA`.

   *Issue:* design a simple mobile/web-app client that talks to our API (even if it’s just a stub).

5. **Extracurricular recommendation engine**
   
   See [Scholarr](https://github.com/karthikm15/Scholarr) and `findECs` for ideas about suggesting activities based on interests.

   *Feature request:* add basic recommendation logic (e.g. “students like X also join Y”) or tag-based filtering.

6. **Community-hub / match-making platform**
   
   The `LaunchForce-Scholars` and `Khoja` projects are hubs where students post events/opportunities and others join.

   *Add:* a “post an activity” form and a simple notification/subscription mechanism.

> ⚠️ Note: the empty repository `dyespring/…_dyespring` contained no code, so no issue could be derived from it.