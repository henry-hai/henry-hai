# Henry Hai Nguyen

Full Stack Developer at Pacific Life, building React and Material UI applications on AWS.
MSWE candidate at UC Irvine, graduating December 2026.

I'm also a Full-Stack Engineer at TCP, and I built the Python pipeline behind ArtHouse
Studio's inbound leads. I boxed for UC Irvine and finished a national semi-finalist.

### Selected work

**[Barber Booking](https://github.com/henry-hai/barber-booking)**
A booking platform for a practice with 300+ clients. The booking API runs on AWS
serverless: API Gateway in front of Python Lambdas that block duplicate bookings with a
DynamoDB conditional write and send confirmation emails through Resend, with secrets in
Parameter Store and one SAM stack per stage. The first booking after idle dropped from
51 s to 2.2 s, with 131 pytest tests against mocked AWS. The Next.js site and a
password-protected React dashboard deploy to S3 behind CloudFront. Live at
[henryhaistudio.com](https://henryhaistudio.com).

**Trauma Guidelines Co-Pilot**, MSWE capstone sponsored by UCI Health
A clinical RAG assistant for a UCI Health trauma surgeon, built by a 4-person team. I built
the React and TypeScript clinician UI, with inline [n] citations that open the cited
guideline and page, and turned a teammate's prototype into the FastAPI answer service. A
Claude Sonnet grounding verifier, chosen from a live test of four model pairings, withholds
answers it can't support. 21 API and UI tests.

**[Fairmark](https://github.com/henry-hai/fairmark)**
A Python pricing engine for a CFTC-regulated prediction exchange. It compares Kalshi prices
to no-vig Pinnacle fair value after fees and runs Monte Carlo simulation to estimate each
set's chance to finish positive. The live demo runs on Cloudflare Pages and Workers KV, fed
by a rate-limit-aware Python poller, with 129 tests. Demo at
[fairmark-app.pages.dev](https://fairmark-app.pages.dev).

**[arthouse-ops](https://github.com/henry-hai/arthouse-ops)**
A Python service that runs weekly on scheduled GitHub Actions, unifying about 18,800
WordPress form entries into one Google Sheet through a custom PHP REST plugin and tagging
each message by category, sentiment and summary with the Claude API. It surfaces the
roughly 140 messages that need a person out of about 18,000.

### Stack

JavaScript, TypeScript, Python, Java, SQL
React, Material UI, Next.js, Node.js, FastAPI
AWS (Lambda, API Gateway, DynamoDB, S3, CloudFront), Docker, GitHub Actions, PostgreSQL
Claude API, RAG pipelines

### Before software

14 years as a barber, running my own book. It's where the booking platform came from, and
most of what I know about shipping something people use every day.

### Reach me

[henryhai.nguyen99@gmail.com](mailto:henryhai.nguyen99@gmail.com) | [LinkedIn](https://www.linkedin.com/in/henryhai99) | [Portfolio](https://henryhai.vercel.app)
