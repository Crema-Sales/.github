<div align="center">

# ☕ Crema

### *A CRM built for the rep, not the dashboard.*

**[cremasales.com](https://cremasales.com)** · **[Crema-CRM monorepo](https://github.com/Crema-Sales/Crema-CRM)**

</div>

---

## The Pour

Every legacy CRM was built to surveil reps... to count activities, audit deals, generate forecasts for someone other than the person closing the business. Reps spend roughly a quarter of their week actually selling. The rest is typing into a database.

We're done with that.

**Crema is an open-source CRM and autonomous sales agent** built around a different conviction: the tooling should work *for* the rep, not against them.

- **Ambient capture** — the browser extension watches Gmail, Outlook, LinkedIn, and Teams, and writes the activity log itself. You don't type.
- **An agent in the loop** — a Cloudflare-deployed AI agent that drafts replies, schedules follow-ups, researches prospects, and acts on your behalf with one click.
- **A coffee theme that isn't decoration** — because we built this in Portland, and we wanted to enjoy the work.

## The Story

A 6-hour hackathon project by **<a href="https://www.linkedin.com/in/pedramamini/">Pedram Amini</a>**, **<a href="https://www.linkedin.com/in/alexhessler/">Alex Hessler</a>**, and **<a href="https://www.linkedin.com/in/jonirvinedotcom/">Jon Irvine</a>** for **Code TV's <a href="https://www.youtube.com/watch?v=JP-NoMViz6c">Greenfield Games Episode 3</a>** — May 2026, Portland, Oregon. You can <a href="https://www.youtube.com/watch?v=xcix53FQmTg">view a video walkthrough</a> of the creation or read <a href="https://pedsidian.pedramamini.com/Claude/Blog/2026-06-18-greenfield-games-post-mortem">Pedram's technical post-mortem</a> which provides further details about the approach we took.

The brief we set ourselves: ship a CRM and autonomous sales agent so dialed-in that no competitor... past, present, or any foreseeable future... could match what we put together in the hackathon window. Set a bar nobody's stepping over. That was the whole ethos. Knock it out of the park, or don't bother.

We ran the parallel-agent workflow on **[Maestro](https://runmaestro.ai)** to keep a dozen AI coding agents in flight at once without losing the plot. That's how a three-person team built and shipped a full CRM + Chrome extension + Cloudflare agent stack in a quarter of a day.

The coffee theme isn't a coat of paint. Portland is third-wave coffee country and we built this in cafes. *Crema* is the golden layer of foam that crowns a perfect espresso pull — the rich part that floats on top. That's what we wanted this product to feel like.

## What's Here

**[Crema-CRM](https://github.com/Crema-Sales/Crema-CRM)** — the monorepo. Cloudflare Workers agent backend, Chrome extension, shared schemas, and data tooling.

## Brewed By

**Pedram Amini** · **Alex Hessler** · **Jon Irvine**

Portland, Oregon · 2026
