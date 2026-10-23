# Hi, I'm Asadullah 👋

Full-stack developer with 3.5 years of experience working with legacy and modern .NET, React, and Angular. I've collaborated remotely with engineering teams in the UK and Germany.

## Core technical skills

- **Backend:** C#, .NET 6, .NET Framework, REST APIs, multithreading
- **Frontend:** React, TypeScript, Angular
- **Engineering:** API integrations, reusable components, rate-limit handling, unit testing (MSTest, FakeItEasy), cross-runtime compatibility (.NET 6 and .NET Framework 4.8)
- **Current focus:** React, Node.js and TypeScript for full-stack work

## A project I'm particularly proud of: Webex Presence Connector

Our operator consoles showed real-time availability indicators for contacts on platforms such as Cisco Jabber and Microsoft Teams. Webex had no external presence webhook or equivalent for our use case, so I built a .NET component that polls the Webex People API for contact availability. It was integrated into both a web app and a desktop app.

**What I worked through:**

- Polled within a limit of 300 requests per minute (about 5 per second), batching requests in parallel.
- Handled `429` responses by waiting, then carrying unfinished contacts into the next batch.
- Targeted both .NET 6 and .NET Framework 4.8 so it could share code with existing engines and connectors.
- Reached 100% unit test coverage, and the tests exposed tight coupling that I refactored away.

📖 Read the full write-up, including the lessons I've learnt: [Webex Presence case study](https://github.com/asad-au-ullah/case-studies/blob/main/webex-presence-polling.md)

## Find me

- [LinkedIn](https://www.linkedin.com/in/asadullahehsan)
- [Case studies](https://github.com/asad-au-ullah/case-studies)

I'm available immediately for full-stack engineering opportunities and remote collaboration.
