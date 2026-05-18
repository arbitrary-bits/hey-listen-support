# Alerts

Everything about how Hey Listen shows alerts — when they appear, what they look like, and how to interact with them.

---

## The Alert Window

When it's time for an alert, Hey Listen shows a full-screen overlay that's impossible to miss even when you're deep in focus. The alert shows:

- The event title
- The start time
- A live countdown ("Starts in 4 minutes", "Starting now", "Started 2 minutes ago")
- The event description, if one is set (rendered with formatting; links are clickable)
- A **Join Meeting** button, if a meeting link is detected
- Snooze buttons
- A **Dismiss** button

> **Screenshot placeholder:** Full-screen alert with event title, countdown, Join Meeting button, snooze buttons, and Dismiss button

When you dismiss an alert, Hey Listen returns focus to whatever app you were using before.

---

## Alert Timing

### Global Alert Time

Set in **Settings → Alerts**. This is the default number of minutes before an event that an alert appears.

> **Screenshot placeholder:** Alerts tab showing the alert time field and stepper

### Per-Calendar Override

In **Settings → Calendars**, each selected calendar has an **Alert** field next to it. Setting this overrides the global time for all events in that calendar.

> **Screenshot placeholder:** Calendars tab showing per-calendar alert time field with a custom value and Reset button

### Per-Event and Per-Series Override

In the menu bar event list, click an event to open its submenu. The **Set Alert Time** submenu lets you set a custom alert time for just that event occurrence. For recurring events, **Set Series Alert Time** applies to all future occurrences in the series.

> **Screenshot placeholder:** Event submenu showing "Set Alert Time" and "Set Series Alert Time" menus with preset options

### Priority Order

When multiple overrides exist, the most specific one wins:

1. Per-occurrence override (set via **Set Alert Time**)
2. Per-series override (set via **Set Series Alert Time**)
3. Per-calendar override (set in **Settings → Calendars**)
4. Global alert time (set in **Settings → Alerts**)

To remove an override and fall back to the next level, select **Reset to Default** in the **Set Alert Time** or **Set Series Alert Time** submenu.

---

## Screen Mode

Choose where alerts appear using the **Show alerts on** picker in **Settings → Alerts**:

- **Active screen** — alert appears on whichever display your cursor is on
- **All screens** — alert appears on every connected display simultaneously

> **Screenshot placeholder:** Alerts tab with the "Show alerts on" picker visible

---

## Join Meeting

If an event has a detectable meeting link (Zoom, Google Meet, Microsoft Teams, and others), a **Join Meeting** button appears prominently in the alert. Clicking it opens the meeting and dismisses the alert.

> **Screenshot placeholder:** Full-screen alert with Join Meeting button highlighted

### Open in Native Apps

By default, meeting links open in your browser. Toggle **Open Zoom and Teams meetings in native apps** in **Settings → Alerts** to open Zoom and Microsoft Teams links in their desktop apps instead.

---

## Missed Alerts

If your Mac was asleep or the app wasn't running when an alert was scheduled, the alert fires as soon as you wake up or relaunch Hey Listen — provided the event hasn't ended yet.

---

## Alert Preview

Click **Preview an alert** at the top of **Settings → Alerts** to trigger a demo alert. If you have upcoming events on selected calendars, Hey Listen uses a real event; otherwise it shows a placeholder. Snooze and dismiss work normally in the preview.

> **Screenshot placeholder:** "Preview an alert" button at the top of the Alerts tab

---

## Related

- [Snooze](snooze.md) — All snooze options explained
- [Muting](muting.md) — Prevent alerts for specific events or titles
- [Filtering](filtering.md) — Filter by RSVP status, work hours, or all-day events
- [Calendars](calendars.md) — Per-calendar alert time overrides

---

← [Guide Index](README.md)
