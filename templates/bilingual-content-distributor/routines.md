# Suggested routines

**Status:** Draft for the template package. Cron times use `America/Los_Angeles`. The getting-started skill should confirm the owner's timezone and posting days before these are created in a live bot. Routines only draft and ask; they never publish.

---

## 1. Monday content plan

- **Name:** Monday content plan
- **Cron:** `0 9 * * 1` (Monday 09:00, America/Los_Angeles)
- **Skill to run:** weekly-content-calendar
- **Prompt:**

```
It is Monday. Draft this week's content calendar for the business using saved memories (name and type, languages, platforms, tone, banned words, posting frequency, closed days) and anything the owner already told you about this week.

Follow the weekly-content-calendar skill: propose only as many slots as their frequency allows, mix themes, flag holidays or local events in the next 2–3 weeks, and list 2–3 backup ideas.

Do not write full platform drafts unless a slot is already fully specified. Do not publish or schedule anything. End by asking which slots the owner wants turned into full drafts, and what photos or facts you still need.
```

---

## 2. Holiday and event look-ahead

- **Name:** Holiday and event look-ahead
- **Cron:** `0 9 * * 4` (Thursday 09:00, America/Los_Angeles)
- **Skill to run:** weekly-content-calendar (coming-up section)
- **Prompt:**

```
Look 2–3 weeks ahead for holidays or common local-business moments that could use a post (for example a public holiday, a well-known awareness day, Mother's Day, a school break, or Chinese-calendar dates such as 春节, 元宵, 端午, or 中秋).

Only suggest what could reasonably fit this business. If a religious or cultural observance might apply, mark it as optional and ask; do not assume the owner's calendar or customers.

For each idea, give: the date, why it might matter, which platforms, a one-line angle, and what you would need from the owner. Do not write full drafts unless they ask. Do not publish anything.
```

---

## 3. Mid-week draft reminder (optional, lighter)

- **Name:** Mid-week draft reminder
- **Cron:** `0 15 * * 3` (Wednesday 15:00, America/Los_Angeles)
- **Prompt:**

```
Mid-week check-in. If this week's calendar has unused slots or a draft still waiting for a photo, a price, or owner approval, list those items in 3–5 short bullets. If nothing is pending, say so in one line and do not invent new promotions.

Ask whether anything last-minute came up (a sell-out, a hours change, a weekend special). Wait. Do not publish anything.
```

Enable this routine only if the owner wants a mid-week nudge. Skip it for very low-frequency posters (one post a week or less).
